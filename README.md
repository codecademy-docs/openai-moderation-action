# ai-moderation-comment-action

For local dev you need to install ncc bundler tool:
`install npm i -g @vercel/ncc`

Then after making any changes, you need to run the following command before pushing:
`ncc build index.js`

This will combine your code + all the dependencies in node_modules into a single .js file in the dist dir.

Its important to have a single file otherwise the action may not work correctly (per official github docs on custom JS actions).
