# transactions3-api
1. App: Write the Heroku URL to your app.
   * [Transaction3 app](https://transactions3-app-andrew-0fe8d1d8e2d3.herokuapp.com/)
3. Running my App (Postman): screenshots of using Postman to do the operations as requested in the instructions
   * [Postman requests](./images/postman)
5. Running my App (Browser): screenshots of using the Browser to use your app (Experiment this, if you are unable, write something in the challenges below)
   * [Browser](./images/browser)
7. Differences: What differences did you note from deploy-app-02-s26 and deploy-app-03-s26?
   * 03 has many more folders that divide the code into smaller sections, which made it much easier to understand.
9. Models: What model code do you prefer, 02's or 03's? (See models and controllers)
    * I prefer 03's code as it is much easier to read and understand. Being broken into multiple smaller parts makes it easier to see what each part of the program does and where to make changes.
11. Challenges: Write the challenges you faced during this exercise and how you solved them
    * I had issues with reopening the container at first. I fixed this by creating a package.json and restarting Docker.
    * I also had an issue with the server starting immediately after opening the container. I fixed this in the Dockerfile, where I changed the CMD from npm run dev to sleep infinity.
    * I also had an issue with connecting to Heroku, which I fixed by deleting package-lock.json and redeploying the application.
13. Questions: Write any questions you still have after this exercise about the code that was here
