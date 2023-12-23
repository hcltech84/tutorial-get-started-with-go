# Tutorial: Get started with Go

- [Tutorial: Get started with Go](https://go.dev/doc/tutorial/getting-started)

## Workflow

The workflow used in this project is as follows:

The first step after creating a Git repository is to create a `0-start` branch from `main`:

```bash
git checkout -b 0-start
```

The second step is to open the [GitHub Issues page](https://github.com/hcltech84/tutorial-get-started-with-go/issues), creating the first issue titled Task Tracking(We'll never close this issue). For the description, write down Task List for this project. For example:

- [ ] Install Go
- [ ] Writing "Hello World" code
- [ ] ...

We only need to do the first and second step once.

Now, to start working on a task in the Task Tracking issue, create a corresponding branch. For example, to start working on the task `Install Go`:

```bash
git:(0-start) git checkout -b 1-task
```

After complete the task `Install Go`, create a PR with the title `Install Go` (same as the task). By doing this, we can now replace the text of the task with `#1` to make a link to the PR on our Task List.
