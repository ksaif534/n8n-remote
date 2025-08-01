# n8n Workflow Automation Repository

This repository contains a collection of n8n workflow automation configurations for various business processes and integrations. These workflows can be imported into your n8n instance to automate tasks, integrate services, and build powerful automation pipelines.

## What is n8n?

n8n is a fair-code licensed workflow automation tool that helps you automate tasks across different services. With a node-based approach, it allows you to connect anything to everything without writing code.

## Workflows Included

### Form Submission Flow

A workflow that handles installation request form submissions with conditional processing based on the preferred installation date.

**Features:**
- Custom form for installation requests
- Date-based conditional processing
- Email notifications
- Discord integration for team notifications

### Gmail Draft Agent

An AI-powered workflow that monitors Gmail for new messages and automatically creates draft responses.

**Features:**
- Gmail integration with OAuth2 authentication
- AI-powered response generation
- Automatic draft creation
- Runs every minute to check for new emails

### LLM Chat Agent

A conversational AI agent powered by Google Gemini that responds to chat messages.

**Features:**
- Webhook-based chat trigger
- Google Gemini integration for natural language processing
- Contextual awareness of current date/time
- Public webhook endpoint for easy integration

### Patient Appointment Scheduler

A medical appointment scheduling assistant that helps patients book appointments through a conversational interface.

**Features:**
- Calendar availability checking
- Appointment creation in calendar
- Conversational booking experience
- Google Gemini integration for natural language understanding
- Timezone handling (UTC+6)

### Send Client Info Conditionally

A flexible client contact form with conditional routing of information based on user selection.

**Features:**
- Customizable client contact form
- Multiple destination options:
  - Google Sheets → Discord
  - Gmail → Discord
  - Google Sheets → Telegram
  - Gmail → Telegram
- Conditional workflow execution based on user selection

### API Scraper To Notion Database

A workflow that fetches data from an external API and stores it in a Notion database.

**Features:**
- HTTP request to fetch data from external APIs
- Data transformation and formatting
- Automatic Notion database page creation
- Structured data storage in Notion

### Restaurant Inventory System

An AI-powered restaurant inventory management system that uses conversational interface to track and update ingredient stock levels.

**Features:**
- Conversational AI interface using Google Gemini
- Airtable integration for inventory database
- Real-time inventory search and updates
- Memory buffer for contextual conversation
- Webhook-based chat trigger for easy access

## Getting Started

### Prerequisites

- An n8n instance (self-hosted or n8n.cloud)
- Required service accounts and API credentials for the integrations you want to use

### Importing Workflows

1. Download the JSON file for the workflow you want to import
2. In your n8n instance, go to Workflows → Import from File
3. Select the downloaded JSON file
4. Configure any required credentials for the nodes in the workflow
5. Activate the workflow

## Customization

Each workflow can be customized to fit your specific needs by modifying the node configurations, adding or removing nodes, or adjusting the conditional logic.

## License

This project is licensed under the terms specified in the repository license file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
