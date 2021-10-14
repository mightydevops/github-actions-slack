Github Action for sending message to Slack

Based on `archive/github-actions-slack` with personal message template.

Required env's:
- env.SLACK_API_TOKEN
- env.SLACK_CHANNEL_ID

Returned:
- message_ts (id) for future progress update without spam in channel
