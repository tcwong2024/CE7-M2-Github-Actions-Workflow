# Github Actions - Workflow

## WorkFlow Exercise
**WorkFlow 1** : Trigger the workflow on push to the main branch.
- Change the name on yml file.

**WorkFlow 2** : Trigger the workflow via github console
- Manually run the workflow 2.

**WorkFlow 3** : Trigger the workflow via github console and using variables inputs

**WorkFlow 4** : Trigger the workflow on push to the main branch and display variables
- Go to github settings > secrets and variables > Actions > Variables tab > Repository variable
- Define 2 varaible "NAME" and "COUNTRY" and enter the value

**WorkFlow 5** : Create new branch and trigger the workflow on pull to the main branch and use github settings > secrets and variables
- Create new branch "workflow-update"
- Checkout new branch "workflow-update" locally
- Push the workflow 5
- Compare & pull request to "main" branch
- Get the variable and display on github actions.

**WorkFlow 6** : Trigger the workflow via github console and using variables inputs
- Create environment for dev and uat
- Push workflow 6
- dev and uat jobs run concurrently.

**WorkFlow 7** : Trigger the workflow via github console and using variables inputs
- Same as workflow 6 but added "needs"
- dev and uat Jobs run in sequential

**WorkFlow 8** : Trigger the workflow via github console and using variables inputs
- Display the ENV_Name and SENSITIVITY_LEVEL for dev and uat
