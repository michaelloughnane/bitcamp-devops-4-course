## {{user.login}} it's time to get ready for the third action 🎉

As with the other actions we wrote, we are going to need to setup a few directories and files.

### :keyboard: Activity: Configure your third action

Let's create our final project directory and install all the necessary dependencies. We will take this a step further near the end of this action and we will show you how to avoid needing to check in `node_modules`.

1. Open the **Terminal** (Mac and Linux) or **Command Prompt** (Windows) on your local machine
2. navigate to the `.github/actions` directory.
3. Checkout the `master` branch
   ```shell
   git checkout master
   ```
4. Update the contents of your Learning Lab repo to your local machine:
   ```shell
   git pull
   ```
5. Checkout the `{{ branch }}` branch you created for this pull request.
   ```shell
   git checkout {{ branch }}
   ```
6. Create a new folder for our actions files. **The full path should be `.github/actions/issue-maker`**.
   ```shell
   mkdir issue-maker
   ```
7. Navigate to the `issue-maker` folder you just created. **The full path should be `.github/actions/issue-maker`**
   ```shell
   cd issue-maker
   ```
8. Initialize a new project:
   ```shell
   npm init -y
   ```
9. Install the **@actions/core** and **@actions/github** dependencies using `npm`:
   ```shell
   npm install --save @actions/core @actions/github
   ```
10. Commit those newly added files,we will remove the need to upload **node_modules** in a later step. Push your changes to GitHub:
   ```shell
   git add .
   git commit -m 'add issue maker dependencies'
   git push
    ```

---

I will respond once you have pushed to this branch.
