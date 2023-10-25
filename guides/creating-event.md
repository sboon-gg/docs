# Creating event

1. Create roles
2. Create form
3. Create a channel under `events` category:
    - inherit permissions from the category
    - first message should have all the crucial information about the event, e.x.:
        > 
            Map: Vung Ro (unreleased)
            Teams: SBOON (US) vs SBOON (NVA)
            Date: 21.10.2023
            Time: 17:00 UTC
            Sign up form:  https://forms.gle/dXFTMNdN5P9PnYF59
            Event link: https://discord.gg/YxDAVkFSEM?event=1158716634761015336 
    - consecutive messages in this channel should be information for all interested parties:
        - tagging @SBOON to remind about signups
        - tagging participants role about event starting, change in details 
    - outdated messages (old tags, &c) should be cleaned to avoid information clutter
4. Create private threads under the channel:
    - [ORG] - tag people you expect to participate in organizing the event
    - [ORG] Applications - place where the form bot will send applications (future)
    - if you need a team chat/bp:
        - [TEAM X] BP
        - [TEAM X] Chat
    - if you need private space for all participants:
        - [ALL] Chat
        - [ALL] BP
5. 
