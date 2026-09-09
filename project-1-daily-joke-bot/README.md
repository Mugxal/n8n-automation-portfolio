# Daily Joke Aggregator (n8n Automation)

## The Problem
My client wanted to start their morning with a laugh, but didn't have time to browse the internet for jokes.

## The Solution
I built an automated workflow that:
1. **Fetches** a random joke from a public API.
2. **Extracts** just the punchline (removes all the messy code).
3. **Routes** the joke based on keywords (IF node logic).
4. **(Future upgrade)** Sends the joke directly to their email/Slack every morning at 8 AM.

## The Technology Used
- **n8n** (Workflow Automation)
- **Chuck Norris API** (Public REST API)
- **IF Node** (Conditional Logic)
- **Set Node** (Data Extraction)

## Visual Workflow
![Workflow Flowchart](./Flowchart.png)

## Key Takeaway
This project demonstrates my ability to pull data from external APIs, clean the data, and implement business logic (IF/THEN routing) using n8n.
