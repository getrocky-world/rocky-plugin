# Rocky

Bring your personal world model to your agent. Rocky creates, manages and guards one living picture of your life and work, built
privately on your Mac from the sources you switch on: the people you know, what you work on, your meetings, commitments and
preferences. Your agent works from it through Rocky, and Rocky asks you before anything is shared beyond your rules or sent.

This plugin connects Claude, ChatGPT, Codex, Cursor and Grok Bot to Rocky's server at `https://mcp.getrocky.world/mcp` and adds the
Rocky skill, which tells the agent what each Rocky tool returns and how asks work: Rocky asks you, and the agent waits and
checks in again until you decide.

## Use it

1. Install Rocky for Mac and sign in (getrocky.world).
2. Add this plugin, then connect Rocky and sign in with your Rocky account.
3. Ask your agent things only you know: "Brief me for my next meeting", "What did I promise this week?", "Where did I leave off?"

The first time an agent reads something, Rocky asks you on your Mac or iPhone: Deny, Allow for 1 hour, or Always. Emails,
WhatsApp messages and calendar invites leave only after you press Send in Rocky.

## Data

The plugin itself stores nothing and contains no code. Your agent sends its requests to `mcp.getrocky.world`, which answers from
your Rocky account under your rules. What Rocky returns goes to the agent you connected.

- Encrypted at rest (AES-256) and in transit (TLS 1.3).
- Rocky only reads the sources you switch on.
- Agents ask Rocky first. Nothing leaves without your yes, unless a rule you set allows it.
- Agents never get your passwords or tokens. Rocky acts for them, after your yes.
- Health, money and passwords are never shared by default. You can change any rule.
- Every access is logged. Revoke any time.
- Processed by leading AI models. Never used to train AI. Never sold.
- Delete everything, any time.

Privacy: https://getrocky.world/privacy. Terms: https://getrocky.world/terms. Support: support@getrocky.world.
Found a vulnerability? security@getrocky.world
