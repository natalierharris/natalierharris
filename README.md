## Hi there 👋

<!--
**natalierharris/natalierharris** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

---

## 🤖 Slash Commands

This repository supports **slash commands** in issue and pull request comments.
Just type a command in a new comment to trigger it.

### Available Commands

| Command | Description |
|---|---|
| `/hello` | Responds with a friendly greeting |
| `/assign` | Assigns the issue/PR to you |
| `/unassign` | Removes you from the assignees |
| `/label <name>` | Adds a label (e.g. `/label bug`) |
| `/unlabel <name>` | Removes a label (e.g. `/unlabel bug`) |
| `/close` | Closes the issue/PR |
| `/reopen` | Reopens the issue/PR |
| `/help` | Lists all available commands |

### How to Use

1. Open any issue or pull request.
2. Write a comment beginning with `/` followed by the command name.
3. The workflow reacts with 👀 to acknowledge receipt, then ✅ on success or ❌ on failure.

### Adding New Commands

All commands are defined in [`.github/workflows/slash-commands.yml`](.github/workflows/slash-commands.yml).
To add a new command, insert an `else if` branch inside the `script:` block following the existing pattern,
then update the `/help` table in that file and the table above.
