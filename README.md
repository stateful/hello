---
runme:
  id: 01J1TBMRJ7VHHB0F9N2SDBKEQE
  version: v3
---

### Stateful Notebook Saving Hello-World

Let's run some commands, and show you how Notebooks work, then you can explore their metadata and sharing/permissions back in the platform web app.

You may notice a `.vscode` directly with `extensions.json` - this instructs VS Code to recommand that you install the `stateful.platform` VS Code extension (if you haven't already). Then you will be prompted to authenticate with the Stateful platform.

For this tutorial to work, you need the [extension installed](https://marketplace.visualstudio.com/items?itemName=stateful.platform) so that the Markdown renders as a notebook and all it's functionality is available.

---

### Step one:
You should see a `▶️ play` button to the left of the command, just click it!

```sh {"id":"01J1TBTVH2HPJNW6SXTTW70RMS","name":"step1-echo-command"}
echo "hello-world"
```

Now you should see terminal output, and the command, output and metadata has already been safely saved to Stateful.

### Step two:
When you `▶️ play` this command, you should see an input prompt pop-up, this is the notebook utilizing the VS Code built in UI for prompts and then storing the value in an environment variable.

```sh {"id":"01J1TCBTA6K6BQ2K1P0FFFGDDF","name":"step2-input-command"}
export YOUR_NAME='New Stateful User'
echo "Welcome to Stateful Notebooks, ${YOUR_NAME}"
```

You should see a welcome, customized with your input in the terminal output.

### What next!?

 - Create a new command cell, by hovering over the area in the notebook you want, and click `+ Code`, write a command and `▶️ play` it.
 - Open the [Stateful Platform](https://platform.stateful.com) to see the commands you ran, complete the setup, and start collaborating with your team.
 - Check out wide range of cool stuff notebooks can do, [Runme docs](https://runme.dev)
