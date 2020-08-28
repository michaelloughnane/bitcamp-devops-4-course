## Configuring a workflow

Actions are enabled on your repository by default, but we still have to tell our repository to use them. We do this by creating a workflow file in our repository.

A **workflow** file can be thought of as the recipe for automating a task. They house the start to finish instructions, in the form of `jobs` and `steps`, for what should happen based on specific triggers.

Your repository can contain multiple **workflow** files that carry out a wide variety of tasks. It is important to consider this when deciding on a name for your **workflow**. The name you choose should reflect the tasks being performed.

_In our case, we will use this one **workflow** file for many things, which leads us to break this convention for teaching purposes._

📖Read more about [workflows](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow#choosing-the-type-of-actions-for-your-workflow)

### :keyboard: Activity: Create a pull request to prepare the repository for actions

1. Create a new workflow file titled `my-workflow.yml` inside of the folders `.github/workflows/` by using the instructions below, or [this quicklink]({{quicklink}}).
   - Go to the [Actions tab]({{ actionsUrl }}).
   - Choose the **Set up a workflow yourself** option, located on the top right hand corner of the screen.
   - Change the name of the file to `.github/workflows/my-workflow.yml`.
2. Commit the workflow to a new branch, you can name it `add-initial-workflow`.
3. Create a pull request titled **Create a workflow**.
4. Supply the pull request body content and click `Create pull request`.

_It is important to place meaningful content into the body of the pull requests you create throughout this course. This repository will stay with you long after you complete the course. It is advisable that you use the body of the pull requests you create as a way to take long lived notes about thing you want to remember._

<details><summary>Suggested body content</summary>

`Workflow files are the recipe for task automation. This is where actions are placed if I want to use them for a task.`

</details>

I'll respond in the new pull request when I detect it has been created.

---

If at any point you're expecting a response and don't see one, refresh the page.
