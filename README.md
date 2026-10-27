# iForgot

Search your likes and saves

iForgot keeps the posts you like and save on X, Instagram, TikTok, RedNote and Douyin in one library. Ask about them in plain words: find the cafés and walks you saved in Tokyo, pull up a recipe you liked, or check what a creator said about a route.

iForgot can search your likes and saves and open a saved post: its text, images, tags, link, platform and date. It can’t change, tag or delete anything, and never sees your passwords, sign-ins to other apps, email or plan. Only what you ask about comes into the chat, and iForgot never sees your chats.

Needs iForgot Plus or Pro (the free trial counts), from the iPhone app. Sign in to iForgot and tap Allow.

## Read only

Agents can look things up in your library. They can’t change it.

**Agents can**

- Search your likes and saves
- Read a post: text, images, tags and link

**Agents can’t**

- Change, tag or delete anything
- See your passwords or sign-ins to other apps
- See your email or plan

## Server URL

```
https://mcp.iforgot.ai/mcp
```

The same for every agent.

## Three ways to add

Each one ends the same: sign in to iForgot and choose Allow.

### One click

Claude only.

1. Choose [Add to Claude](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=iForgot&connectorUrl=https%3A%2F%2Fmcp.iforgot.ai%2Fmcp).
2. In Claude, choose Add.
3. Sign in to iForgot and choose Allow.

### From the app’s directory

ChatGPT, Grok Bot, Muse and WorkBuddy, once iForgot is listed there.

1. Open the app’s apps, plugins, connectors or skills.
2. Search “iForgot” and choose Add.
3. Sign in to iForgot and choose Allow.

### By hand

Works in every agent, today.

1. Copy the server URL.
2. Paste it where the agent takes it.
3. Sign in to iForgot and choose Allow.

## Add it by hand

Where each agent takes the server URL.

### Claude

*Settings › Connectors*

1. In Claude, open Settings › Connectors.
2. Choose Add custom connector and paste the server URL.
3. Sign in to iForgot and choose Allow.

Free Claude plans can add one custom connector.

### ChatGPT

*Developer mode*

1. In ChatGPT’s settings, turn on developer mode.
2. Add a connector with the server URL.
3. Sign in to iForgot and choose Allow.

Developer mode is only on some ChatGPT plans.

### Grok Bot

1. Paste this into a Grok Bot chat:

   ```
   Add a custom MCP server named iForgot at https://mcp.iforgot.ai/mcp
   ```

2. Choose Authorize on the card it shows.
3. Sign in to iForgot and choose Allow.

In Cursor, [Add to Cursor](https://cursor.com/en/install-mcp?name=iForgot&config=eyJ1cmwiOiJodHRwczovL21jcC5pZm9yZ290LmFpL21jcCJ9) fills in the server URL for you.

### Muse

*By Meta · US only*

1. In Muse, open Connectors.
2. Choose Add custom connector and paste the server URL.
3. Sign in to iForgot and choose Allow.

### WorkBuddy

*By Tencent*

1. Paste this config into a WorkBuddy task:

   ```json
   {"mcpServers":{"iforgot":{"url":"https://mcp.iforgot.ai/mcp"}}}
   ```

2. In “专家·技能·连接器”, choose “信任” (Trust) and turn iForgot on.
3. Sign in to iForgot and choose Allow.

## Try asking

Ask in your own words. Your agent looks it up in iForgot, then answers.

- “Find the cafés and walks I saved in Tokyo” — Searches your saves from all five apps.
- “What did trailsbyjun say about the Dolomites route?” — Opens that post and reads it.
- “Find the recipes I liked” — Looks only at your likes.

## If something goes wrong

### It asks you to sign in again

Its access to iForgot ran out. Sign in and choose Allow again. Nothing is lost.

### It says you need a plan

Agents come with Plus and Pro, and the free trial counts. Start or renew in the iPhone app, then ask again.

### Nothing comes back

Agents only see what’s already in your library. Check that the app is connected in iForgot, or try other words.

### You want to disconnect

In iForgot, open Settings › Agents and choose Disconnect, or remove iForgot in the agent’s own settings. Either one ends access at once.

## Still stuck?

Write to support@iforgot.ai. We reply within 2 business days.

- Website: https://iforgot.ai
- Support: https://iforgot.ai/help
- Privacy policy: https://iforgot.ai/privacy
- Terms of service: https://iforgot.ai/terms
- Support email: support@iforgot.ai

## Files

| Folder | |
|---|---|
| [`claude/`](claude/) | Claude |
| [`openai/`](openai/) | ChatGPT |
| [`cursor/`](cursor/) | Cursor |
| [`workbuddy/`](workbuddy/) | WorkBuddy |
| [`brand/`](brand/) | iForgot |

## License

[MIT](LICENSE)
