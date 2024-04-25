# Step 1: Create a GitHub Account If you do not already have a GitHub account, create one at github.com.

# Step 2: Create a GitHub Account If you do not already have a GitHub account, create one at github.com.

> ![Step 2](./images/step2.png "Step 2")

# Step 3: Clone the Repository To clone the repository, go to the repository page on GitHub and click on the “Code” button. This will open a menu with a URL that you can use to clone the repository. Open a terminal window and navigate to the directory where you want to clone the repository. Use the following command to clone the repository:

> ![Step 3](./images/step3.png "Step 3")

# Step 4: Create and Manage Branches Create a new branch called “dev” using the following command:

# Switch to the new branch using the following command:

> ![Step 4](./images/step4.png "Step 4")

### Make changes to the “hello.txt” file by adding the following line to the end of the file:

#### This is a dev branch change.

#### Save the file and close it.

# Step 5: Commit Changes to the Dev Branch

> ![Step 5](./images/step5.png "Step 5")

# Step 6: Push Changes to the Dev Branch Push the changes to the dev branch using the following command:

> ![Step 6](./images/step6.png "Step 6")

# Step 7: Resolve Conflicts Switch back to the main branch using the following command:

> ![Step 7](./images/step7.png "Step 7")

##### Make changes to the “hello.txt” file by adding the following line to the end of the file:

##### This is a main branch change.

##### Save the file and close it.

##### Try to merge the dev branch into the main branch using the following command:

> ![Step 8](./images/step8.png "Step 8")

> ![Step 9](./images/step9.png "Step 9")

# Step 9: Work with Remote Repositories Create a new repository on your local machine using the following command:

#### Add the remote repository using the following command:

#### Fetch the changes from the remote repository using the following command:

#### Create a new branch called “feature” and switch to it using the following commands:

> ![Step 10](./images/step10.png "Step 10") > ![Step 11](./images/step11.png "Step 11") >![Step 12](./images/step12.png "Step 12") >![Step 13](./images/step13.png "Step 13")

# Step 10: Commit and Push Changes to the Feature Branch Add the changes to the feature branch and commit them using the following commands:

> ![Step 14](./images/step14.png "Step 14")

# Step 11: Create a Pull Request Go to the GitHub repository page and click on the “Pull requests” tab. Click on the “New pull request” button. Select the main branch as the base branch and the feature branch as the compare branch. Review the changes and click on the “Create pull request” button.

> ![Step 15](./images/step15.png "Step 15") > ![Step 16](./images/step16.png "Step 16") > ![Step 17](./images/step17.png "Step 17")

# Step 12: Merge the Pull Request Review the pull request and click on the “Merge pull request” button to merge the changes into the main branch.

> ![Step 18](./images/step18.png "Step 18")

# Step 13: Use Git Command Line Tools Open a terminal window and navigate to the directory where you cloned the repository. Use the following command to view the commit history:

> ![Step 19](./images/step19.png "Step 19")

- pull request for latest changes then git log

> ![Step 20](./images/step20.png "Step 20")

- git status

  > ![Step 21](./images/step21.png "Step 21")

- git checkout -b new-branch-name

  > ![Step 22](./images/step22.png "Step 22")

- git branch -d new-branch-name

  > ![Step 23](./images/step23.png "Step 23")

- git revert 5929a7894f66f2657f5b16
  > ![Step 24](./images/step24.png "Step 24") > ![Step 25](./images/step25.png "Step 25") > ![Step 26](./images/step26.png "Step 26")
