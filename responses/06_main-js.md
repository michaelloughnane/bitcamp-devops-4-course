## Time to code 💻

You may have noticed that your workflow has been running every time a change has been made. This is expected since it's trigger is a `push` event.

Hopefully you have also noticed that it fails when it reaches the `hello-action` step.

As we can see from the screenshot, as well as the [Actions]({{actionsUrl}}) tab, the failure occurs because the runner cannot find the action.

Let's fix that by creating the action it is looking for!

### :keyboard: Activity: Hello World

💡All of the following steps take place inside of the `.github/actions/hello-world` directory.

The first iteration of our action will follow the traditional path of logging "Hello World" 👋to the console. We will expand on this as we move forward, for now it's a good test to make sure all of our files are set up correctly 😄

1. Create and add the following contents to the `.github/actions/hello-world/main.js` file:

   ```javascript
   console.log("Hello World");
   ```

2. Save the `main.js` file
3. Commit the changes and push them to the `hello-world` branch:
   ```shell
   git add main.js
   git commit -m 'create main.js'
   git push
   ```

---

I'll respond here once the workflow has completed running. Remember, you need to **push** your changes to trigger it!
