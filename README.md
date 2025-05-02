# ai-pre-sales-research-agent
Automated pre-call research tool that creates actionable insights from LinkedIn and company websites using AI agents

# AI Agent for Sales Pre-Call Research

## Overview
This project explores the power of AI agents by automating the process of researching prospects and companies. Built with Relevance AI, the agent combines insights from LinkedIn profiles and company websites into a single, actionable pre-call report-helping sales reps prepare more effectively for client calls.

## Features
- **Prospect Research:** Scrapes and summarizes LinkedIn profiles from a provided URL.
- **Company Research:** Uses Firecrawl to scrape and summarize information from company websites.
- **Pre-Call Report:** Merges both summaries into a concise report for sales call preparation.

## Tools Used
- [Relevance AI](https://relevance.ai/) (AI agent builder)
- [Firecrawl](https://firecrawl.dev/) (Web scraping tool)

## Agent Configuration File

This repository includes the exported `.rai` agent file, which contains the complete configuration of the AI agent. The `.rai` file allows you to easily import the agent into your own Relevance AI workspace, preserving all settings, tools, and workflow steps.

**How to use the `.rai` file:**

1. Log in to your Relevance AI account.
2. Go to the Agents page in the sidebar.
3. Look for the option to import or upload an agent configuration.
4. Upload the provided `.rai` file to create the agent in your workspace.
5. Once imported, you can review and customize the agent or its tools as needed.

> *Tip: Exporting and importing `.rai` files is a convenient way to back up, share, or transfer agents between environments or team members.*

## Workflow
1. **Input:** Enter a LinkedIn profile URL and a company website URL.
2. **Processing:** 
    - The agent scrapes and summarizes the LinkedIn profile.
    - The agent scrapes and summarizes the company website.
3. **Output:** The agent generates a pre-call report that combines both summaries.

## Try out the AI Agent for yourself!
https://app.relevanceai.com/agents/bcbe5a/09dfa539c1e5-400b-8713-deb82ea3337b/0cfe19bc-e4e0-4fab-bfb1-96d8b4eab455/embed-chat?hide_tool_steps=false&hide_file_uploads=false&hide_conversation_list=false&bubble_style=agent&primary_color=%23685FFF&bubble_icon=pd%2Fchat&input_placeholder_text=Type+your+message...&hide_logo=false&hide_description=false

## How to Use
1. Sign up for Relevance AI and Firecrawl.
2. Import the agent using the provided `.rai` file as described above.
3. Input the LinkedIn and company URLs when prompted.
4. Run the agent to generate your pre-call report.
