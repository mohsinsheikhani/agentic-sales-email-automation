Multi-agent system for generating, selecting, and sending personalized cold sales emails using OpenAI's Agent SDK with automated workflow orchestration

---

## Project Overview

This project demonstrates a sales automation pipeline that leverages multiple AI agents working collaboratively to create and deliver compelling cold outreach emails. The system showcases advanced agentic design patterns including agent collaboration, tool integration, and workflow handoffs.

## System Architecture

The system consists of **5 specialized agents** working in a coordinated workflow:

### Email Generation Agents (3 Agents)
1. **Professional Sales Agent** - Creates formal, serious cold emails with professional tone
2. **Engaging Sales Agent** - Generates witty, humorous emails designed for high response rates  
3. **Busy Sales Agent** - Produces concise, direct emails for time-conscious prospects

### Orchestration Agents (2 Agents)
4. **Sales Manager Agent** - Evaluates all generated emails and selects the most effective one
5. **Email Manager Agent** - Handles formatting, HTML conversion, subject line generation, and email delivery

## Key Features

- **Multi-Style Email Generation**: Three distinct writing styles to match different prospect preferences
- **Intelligent Email Selection**: AI-powered evaluation to choose the most compelling email
- **Automated HTML Formatting**: Converts plain text to professional HTML email format
- **Dynamic Subject Line Generation**: Creates engaging subject lines optimized for open rates
- **SMTP Integration**: Uses Gmail SMTP for reliable email delivery (instead of SendGrid)
- **Workflow Orchestration**: Seamless agent handoffs and tool collaboration
- **Tracing & Monitoring**: Built-in OpenAI tracing for workflow visibility

### Core Technologies
- **OpenAI Agent SDK**: Primary framework for agent creation and management
- **gemini-2.5-flash**: Language model powering all agents
- **SMTP (Gmail)**: Email delivery service
- **Python asyncio**: Asynchronous processing for parallel operations
- **HTML/CSS**: Email formatting and styling

## Email Output Sample

Below is an example of the final formatted email generated and sent by the system:

<img width="1545" height="1497" alt="OpenAI Agent SDK Project - Mohsin Sheikhani" src="https://github.com/user-attachments/assets/4133f9d3-4de7-4fe0-9423-fd0d10d07a76" />

*The system automatically generates professional HTML emails with proper formatting, compelling subject lines, and personalized content tailored to the target audience.*
