---
runme:
  id: 01J1TBMRJ7VHHB0F9N2SDBKEQE
  version: v3
---

### Runme Notebook Saving Hello-World

Let's run some commands, and show you how Notebooks work, then you can explore their metadata and sharing/permissions back in the Stateful cloud.

You may notice a `.vscode` directly with `extensions.json` - this instructs VS Code to recommand that you install the `stateful.runme` VS Code extension (if you haven't already). Then you will be prompted to authenticate with the Stateful cloud.

For this tutorial to work, you need the [extension installed](https://marketplace.visualstudio.com/items?itemName=stateful.runme) so that the Markdown renders as a notebook and all it's functionality is available.

---

### Step one:

In the left sidebar, you should see a Runme icon `[▶️]`, click that then `[Sign in]` which will authenticate you with Stateful cloud so you can `[Save]` terminal artifacts.

### Step two:

You should see a `▶️ play` button to the left of the command (on hover), just click it!

```sh {"id":"01J1TBTVH2HPJNW6SXTTW70RMS","name":"step1-echo-command"}
$ echo "hello-world"
```

Now you should see terminal output, click the `[Save]` button to securely store it's output and metadata in Stateful cloud.

### Step three:

When you `▶️ play` this command, you should see an input prompt pop-up, this is the notebook utilizing the VS Code built in UI for prompts and then storing the value in an environment variable.

```sh {"id":"01J1TCBTA6K6BQ2K1P0FFFGDDF","name":"step2-input-command"}
$ export YOUR_NAME='New Runme User'
$ echo "Welcome to Runme Notebooks, ${YOUR_NAME}"
```

You should see a welcome, customized with your input in the terminal output. Click `[Save]` for this cell.

### What next!?

- Create a new command cell, by hovering over the area in the notebook you want, and click `+ Code`, write a command and `▶️ play` it.
- Create a new Markdown file `exploring.md` with the file explorer and build a new Notebook workflow from scratch.
- Open the [Stateful Cloud](https://cloud.stateful.com) to see the commands you ran, configure your workspace, and start collaborating with your team.
- Check out wide range of cool stuff notebooks can do, [Runme docs](https://runme.dev)
