
# <img src="https://img.freepik.com/free-psd/instagram-application-logo_23-2151544100.jpg" alt="Instagram Logo" width="48"> Basic Instagram 
Basic Instagram is a simplified clone of Instagram built with Flask, SQLite, and React. It demonstrates the core features of modern social media apps like posting, liking, and following, while keeping the codebase approachable for learning and experimentation.

### Table of Contents  
1. [Setting up your local environment](#setting-up-your-local-environment)
2. [Features overview](#features-overview)
3. [Usage](#usage)
4. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
5. [Footnotes](#footnotes)
6. [Credits](#credits)


### Setting up your local environment
1. Clone this repository
2. Navigate to the repository: `cd p3-insta485-client`
3. Make these three files executable: `chmod +x ./bin/insta485install ./bin/insta485db ./bin/insta485run`
4. Run this command inside the repository: `./bin/insta485install`
 - This will create a virtual environment and also install any dependencies needed to run this application
5. Run this command to populate our database initially with random values: `./bin/insta485db create`
7. To run this locally do: `./bin/insta485run`
- This will buld the front end using webpack and also start up a Flask server to handle backend tasks

### Features overview
- Post Photos – Upload images that appear in your personal feed and other people's feed.

- Like & Unlike Posts – Likes on posts update dynamically without refreshing the page.

- Comment on Posts – Add or delete comments to engage with content.

- Follow & Unfollow Users – Build your social network by following others.

- Authentication – Log in with your account.

- Client-Side Rendering – Feed built in React, fetching live data from the Flask backend.

- REST API – Standardized JSON endpoints (/api/v1/posts/, /api/v1/likes/, /api/v1/comments/, etc.) for posts, likes, and comments.

### Usage
Here are some examples of the features implemented in this project.

Double tap to like a post: If the post has not been liked, the user can click twice on the picture of a post, where it will increment the likes and show a heart animation.
![Double tap animation](https://raw.githubusercontent.com/thealvinjg/basic-instagram/refs/heads/main/doubletap.mp4.gif)  

"Explore" page: Users can find other people that they have not followed yet, view their profiles and also follow them.
![Explore page animation](https://raw.githubusercontent.com/thealvinjg/basic-instagram/refs/heads/main/explore_page.mp4.gif)  

Account editing: Users can edit their accounts.
![Account editing animation](https://raw.githubusercontent.com/thealvinjg/basic-instagram/refs/heads/main/edit_account.mp4.gif)  

### Frequently Asked Questions (FAQ)
Q: Do I need Docker to run this?  
A: No, just Python 3.

Q: How do I reset the database?  
A: Run ./bin/insta485db reset. See ./bin/insta485db file for more options.

Q: What stack does this use?  
A: Flask (backend), React (frontend), SQLite (database), Webpack (bundling).

### Footnotes
For information about how to deploy this application, check [Deploy a Flask App to AWS EC2](https://eecs485staff.github.io/p2-insta485-serverside/setup_aws.html).

### Credits
