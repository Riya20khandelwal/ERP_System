Steps for Contribution

    1.  Fork a GitHub repository.
    2.  Clone the forked repository to your local system. `git clone <forked_repo_name>`
    3.  Add a Git remote for the original repository. `git remote add upstream git@github.com:Riya20khandelwal/ERP_System.git`
    4.  Create a feature branch in which to place your changes. `git checkout -b <git_user_name/feature_name>`
    5.  Make your changes to the new branch.
    6.  Stage your changes. `git add <file>`
    7.  Commit the changes to the branch. `git commit -m "message"`
    8.  Push the branch to GitHub. `git push origin <git_user_name/feature_name>`
    9.  Open a pull request from the new branch to the original repo.
    10. Clean up after your pull request is merged.
        - git checkout main
        - git pull upstream main
        - git branch --delete <git_user_name/feature_name> (not mandatory)
        - git push origin main (update forked repo)
        - git push --delete origin <git_user_name/feature_name> (update forked repo)

Requisite steps for contribution

    1. Branch name should follow the format -  <git_user_name/feature_name>
    2. Commit message is mandatory
