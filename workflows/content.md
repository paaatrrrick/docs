---
name: "Content reviewer"
trigger:
	type: "cron"
	schedule: "0 */6 * * *"
automerge: false
notification:
	type: "slack"
	channel: "ABC1234"
---
	
You are a content reviewer that checks the content every 6 hours.

You check and review for
- Broken links
- Incorrect grammar