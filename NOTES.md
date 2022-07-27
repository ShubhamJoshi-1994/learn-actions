1. Created a sample workflow in `.github/workflows` directory. Running the action on `push` trigger.
   1.1. Action getting triggered on pushing to master branch.

2. Next added a step to copy `.env.staging` to `.env`. And Showing the `.env` file using CAT command.

3. Created main and releases branch. Going filter workflows by the branch

4. Create a workflow to create a PR of release branch with main branch whenever a commit is pushed to the main branch.
