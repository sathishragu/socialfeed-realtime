# Social Authenticator Demo

This project is to get feeds from social apps and display in a timeline page with like/unlike share options in realtime.

Time Spent : 30 hrs (2 week assignment)

## Initial Setup

1. Clone the repo: `git clone git@github.com:crabdude/social-authenticator`
2. Install packages: `npm install`
3. Update the database configuration in `config/database.js`
4. Update auth keys in `config/auth.js`
5. Run `npm start`
6. Visit in your browser at: `http://127.0.0.1:8000`

REQUIRED :

[DONE]User can sign in and connect to Facebook and Twitter using passport

[DONE]User can view the last 20 posts on their aggregated timeline

[DONE]The current signed in user will be persisted across server restarts

[DONE]In the home timeline, user can view posts with the user profile picture, username, content, origin social network and timestamp. In other words, data presentation should appear consistent for posts across social network sources.

[DONE]In the timeline, user can like and unlike posts.

[DONE]User can click share in the timeline, and share with a custom message on a separate page.

[DONE]User can click reply in the timeline, and submit a reply on a separate page.

[DONE]User can click compose anywhere, and submit a new post on a separate page.

[DONE]When composing, user can select to which networks to post.

OPTIONAL:

[DONE] User can click a post and view it on a separate page with controls to share, like, and reply.

[NOT DONE] User should be able to unshare their posts.

[NOT DONE] User should be able to delete their posts.

[NOT DONE] Replies should be prefixed with the username and link to the conversation thread.

[NOT DONE] User can click a "Next" button at the bottom to load more

[NOT DONE] Add Google+ support through their Domains API (Request addition to the nodejsboot.camp domain)
