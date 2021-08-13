# Express Boilerplate!

This is a boilerplate project used for starting new projects!

## Set up

Complete the following steps to start a new project (NEW-PROJECT-NAME):

1. Clone this repository to your local machine `git clone BOILERPLATE-URL NEW-PROJECTS-NAME && cd $_ && rm -rf .git && git init`
2. Install the node dependencies `npm install`
3. Move the example Environment file to `.env` that will be ignored by git and read by the express server `mv example.env .env`
4. Edit the contents of the `package.json` to use NEW-PROJECT-NAME instead of `"name": "express-boilerplate",`
5. Hide Secrets (`proccess.env.VARIABLE`)
6. Ensure standard Node.js .gitignore is used
7. Check for minimal logging in production environment
8. Remove unnecessary console logs
9. Ensure sensitive server errors are hidden using middleware
10. Generate different API TOKENS for development and production
11. Specify Node version in package.json
12. Audit packages (`npm audit` | `npm audit --fix`)
## Scripts

Start the application `npm start`

Start nodemon for the application `npm run dev`

Run the tests `npm test`

## Deploying

When your new project is ready for deployment...
1. Add a new Heroku application with `heroku create`
2. Run `npm run deploy` which will push to this remote's master branch.
