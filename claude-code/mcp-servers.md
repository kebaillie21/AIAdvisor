# MCP Servers

MCP (Model Context Protocol) servers that Kristin has connected to Claude Code.

## Active Connections

| Server | Purpose | Tools Available |
|--------|---------|----------------|
| GitHub | Repo management, PRs, issues | push_files, create_pull_request, list_branches, and many more |
| Pocket AI | Conversation search and retrieval | search_pocket_conversations, get_pocket_conversation, search_pocket_actionitems |
| Google Calendar | Calendar management | list_events, create_event, update_event |
| Slack | Messaging | slack_send_message, slack_read_channel, slack_search_public |
| Gmail | Email | search_threads, get_thread, create_draft |
| Google Drive | File access | read_file_content, search_files, list_recent_files |
| Canva | Design | generate_design, get_design, export_design |
| Wix | Website management | ListWixSites, ManageWixSite, WixSiteBuilder |

## How to Add an MCP Server
- Use the `update-config` skill or edit `settings.json` directly
- MCP servers are configured under the `mcpServers` key in settings

## Notes
- Add setup details, auth requirements, and usage patterns as discovered
