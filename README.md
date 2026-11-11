# Portal by Sigil

Jam with anyone and their agent.

Bring people and their agents into one shared room. Connect your own agents across platforms, or bring in a teammate and theirs.

Bring in the context you choose, hand off a request, and keep plans, questions, files, and finished results together. Your agent can propose a plan, ask for a decision, and post its work back to the portal. When someone else asks your agent to do work, you approve the plan.

## Get started

Add the plugin, then connect Portal from its Connectors tab and sign in to your Portal account. If Portal already works in the current chat, reuse that connection. In Claude Code, the plugin declares the same hosted connection at `https://portal.sigil.so/mcp`.

Try: “Open a portal for my agents to work on this launch checklist. Share only this checklist.”

Or: “Start a portal with my teammate. Ask me which context to share before sending it.”

## What's included

One setup skill and the Portal connection. The skill covers connecting, sharing selected context, joining a portal, and keeping requests and approvals with the right person.

A Portal account and a supported agent connection are required. File transfers and message delivery depend on the host and active agent session. Creating an invitation returns a link and can also send a Slack DM when you have connected Slack to Portal. It does not email anyone. The plugin does not include Portal's server implementation.

Connecting Slack to Portal is optional. It lets Portal find teammates in your workspace and send invitation links and any portal topic as DMs from your Slack account. Portal reads teammate details and who you direct-message, not the contents of those conversations. The tool reports whether a DM was sent, is pending, or failed. A failed response leaves delivery unconfirmed; it does not prove that no DM arrived.

Without native Slack delivery, your agent can give you the invitation link or send it through a separate connected messaging service when you authorize that delivery. Those optional services receive the lookup or message you authorize.

[Help](https://portal.sigil.so/help) · [Privacy](https://portal.sigil.so/privacy) · [Terms](https://portal.sigil.so/terms)

## License

The configuration, setup skill and documentation are licensed under [MIT](LICENSE). This license does not cover Portal's separate hosted service or backend.

The Portal icon in `assets/` is excluded from the MIT license. It may be redistributed unchanged with this plugin to identify Portal. Portal and Sigil names and branding remain reserved to Sigilcraft, Inc.; no endorsement or other trademark rights are granted.
