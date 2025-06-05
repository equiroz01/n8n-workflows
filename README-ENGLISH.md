[🌐 Versión en español](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md) | [🌐 English Version](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README-ENGLISH.md)

# 🧠 n8n Workflow Collection

This repository is a **fork** of the original initiative by [@Zie619](https://github.com/Zie619/n8n-workflows), who gathered n8n workflows from various sources, such as:

- The official [n8n.io](https://n8n.io/) site and its community forum.  
- Examples shared publicly on GitHub, blogs, and other websites.

The purpose of this repository is to offer a consolidated resource to inspire you, facilitate your learning, and allow you to reuse workflows in your own n8n projects.


## 📂 Implemented Improvements

- **English Descriptions**: Each `.json` file was analyzed and given a clear description in English based on the actions it performs.  
- **Duplicate Removal**: The unique hash of each file was verified and validated to detect and remove duplicate workflows, ensuring that each workflow is unique in content.  
- **File Renaming**: File names were updated to more accurately describe their main functionality, making them easier to search for and select.


## 🛠 Usage Instructions

To import any workflow into your n8n instance, follow these steps:

1. Open your n8n instance.  
2. Click the “Import” menu (☰ → Import workflow).  
3. Select the desired `.json` file from the `workflows` folder.  
4. Review and adjust credentials or webhook URLs as needed.  
5. Save and run the workflow.  
6. [If you can’t find the workflow you need, you can use this Custom GPT to help you find it or resolve any issues you have with n8n.](https://chatgpt.com/g/g-6840a79abd348191966dd06abd7236c8-asistente-de-flujos-n8n)  
7. You can also chat with this repository using [https://gitmcp.io/DragonJAR/n8n-workflows-es/chat](https://gitmcp.io/DragonJAR/n8n-workflows-es/chat)

## 🖥️ MCP Server (Model Context Protocol)

The MCP server for this repository, so you can interact with this large knowledge base of documented n8n workflows, is:

`https://gitmcp.io/DragonJAR/n8n-workflows-es`

[Here you’ll find instructions on how to use it in Cursor, Claude Desktop, Windsurf, VSCode, Cline, or Highlight AI](https://gitmcp.io/DragonJAR/n8n-workflows-es).

## 🤝 Contribution

If you discovered an interesting workflow or developed one yourself, feel free to contribute to this collection! Just keep in mind:

- **Descriptive Name**: Choose a file name that clearly reflects the workflow’s main function.  
- **Source Mention**: If the workflow comes from another source, include a brief comment at the beginning of the file indicating its origin.

To propose contributions, open a pull request with your new workflow or improvement.


## ⚠️ Notice

All workflows shared here are provided “as is.” **Before using them in a production environment, inspect and test them in a controlled setting**. Make sure you fully understand each node, credential, and link to avoid possible errors or security breaches.


## 📋 Workflow Listing

- [0001-nostr-damus-ai-report.json](workflows/0001-nostr-damus-ai-report.json)
  Description: This automated flow analyzes Nostr content with the hashtag #damus using language models to generate reports and then sends the results via email and Telegram.

- [0002-Gumroad-MailerLite-trigger.json](workflows/0002-Gumroad-MailerLite-trigger.json)
  Description: This automated flow adds a subscriber to MailerLite when a sale occurs on Gumroad and immediately assigns them to a specific group.

- [0003-line-chatgpt-image-flow.json](workflows/0003-line-chatgpt-image-flow.json)
  Description: This automated flow processes image generation requests through the LINE chatbot and stores them in Google Drive as binary files and in a spreadsheet with details including prompts, estimated costs, and relevant information.

- [0004-connectwise-ticket-alerts-to-teams.json](workflows/0004-connectwise-ticket-alerts-to-teams.json)
  Description: This automated flow activates daily between 8 AM and 4 PM to query new tickets in Connectwise with certain conditions, filter out those already notified using Redis, combine them by company or site into HTML messages, and send alerts to Microsoft Teams.

- [0005-google-calendar-outlook-sync.json](workflows/0005-google-calendar-outlook-sync.json)
  Description: This flow synchronizes events between Google Calendar and Microsoft Outlook, automatically creating events in Outlook when they are added in Gmail and deleting them when canceled.

- [0006-airtable-hn-job-scraping.json](workflows/0006-airtable-hn-job-scraping.json)
  Description: This automated flow allows extracting and structuring job offers posted on 'Ask HN: Who is hiring' on Hacker News using the Algolia API.

- [0007-social-media-creator.json](workflows/0007-social-media-creator.json)
  Description: This automated flow allows a chatbot to create content optimized for multiple social networks (X-Twitter, Instagram, Facebook, LinkedIn, Threads, YouTube Shorts) using LLM models and web search tools. It generates posts with specific JSON structures and creates images using external services like pollinations.ai.

- [0008-notion_linkedin_pub.json](workflows/0008-notion_linkedin_pub.json)
  Description: This automated flow posts daily on LinkedIn a selected post from a Notion database, based on the scheduled date and time.

- [0009-multi-agente-ia.json](workflows/0009-multi-agente-ia.json)
  Description: This flow allows maintaining a multi-turn conversation with multiple AI agents based on defined models and configurations, combining their responses and incorporating memory for follow-up.

- [0010-crm-lead-batchdata-calification.json](workflows/0010-crm-lead-batchdata-calification.json)
  Description: This flow verifies and qualifies leads using BatchData to query property details such as estimated value, size, or age, and then automatically updates the lead record in the CRM with this information.

- [0011-totp-generator.json](workflows/0011-totp-generator.json)
  Description: This workflow generates TOTP codes automatically when the 'Test workflow' button is executed.

- [0012-typeform-feedback-route.json](workflows/0012-typeform-feedback-route.json)
  Description: This flow analyzes responses from Typeform forms and classifies them into Google spreadsheets based on whether the numerical value 'usefulness' is greater than or equal to 3.

- [0013-bitwarden-line-sync.json](workflows/0013-bitwarden-line-sync.json)
  Description: This automated flow creates a new group in Bitwarden, gets the list of members from the LINE chatbot to synchronize subscriptions, updates the members within the created group, and finally verifies the result obtained.

- [0014-monitor-verstappen-tweets.json](workflows/0014-monitor-verstappen-tweets.json)
  Description: This flow searches for the latest public and private tweets with the keyword 'Verstappen', then compares those results with an existing list in Airtable to identify and save only new entries, eliminating duplicates.

- [0015-berlin-clima-plivo.json](workflows/0015-berlin-clima-plivo.json)
  Description: This automated flow sends the current weather forecast for Berlin daily at 9:00 AM via a message using Plivo.

- [0016-todoist-task-creator.json](workflows/0016-todoist-task-creator.json)
  Description: This flow allows creating a new task in the Todoist application through a manual trigger.

- [0017-stripe-hubspot-slack.json](workflows/0017-stripe-hubspot-slack.json)
  Description: This automated flow updates a deal in HubSpot to paid when a Stripe invoice is successfully paid and reports the payment and its details via Slack messages.

- [0018-entrevistas-y-participantes.json](workflows/0018-entrevistas-y-participantes.json)
  Description: This flow processes two separate datasets containing information about interviews and their participants, converting each individual entry into an independent object and then merging them based on specific keys.

- [0019-EscrituraJSONBinario.json](workflows/0019-EscrituraJSONBinario.json)
  Description: This automated flow creates sample JSON data, converts it to binary format (Base64), and writes this content to a file.

- [0020-todoist-ai-categorization.json](workflows/0020-todoist-ai-categorization.json)
  Description: This flow automatically organizes Todoist tasks into specific projects using artificial intelligence to categorize them.

- [0021-mock-contacts-to-sheet.json](workflows/0021-mock-contacts-to-sheet.json)
  Description: This flow loads sample contact data from the HubSpot service into a Set and then simulates an 'add row' or similar operation to Google Sheets/Airtable.

- [0022-copper-person-flow.json](workflows/0022-copper-person-flow.json)
  Description: This automated flow creates a record in Copper with the name Harshil and his email, then updates that record by adding a specific phone number, and finally gets the updated details of the person.

- [0023-coda-insert-data.json](workflows/0023-coda-insert-data.json)
  Description: This n8n flow inserts new data into a specific table of a Coda document when manually triggered by a click.

- [0024-iss-position-updates.json](workflows/0024-iss-position-updates.json)
  Description: This automated flow gets the current position of the International Space Station (ISS) every minute from an external API and sends the data to a topic in ActiveMQ.

- [0025-google-slides-thumbnail.json](workflows/0025-google-slides-thumbnail.json)
  Description: This automated flow allows downloading a specific page thumbnail from Google Slides after having previously obtained all slides of the presentation.

- [0026-linkedin-top-sourcer.json](workflows/0026-linkedin-top-sourcer.json)
  Description: This flow allows finding LinkedIn profiles using boolean search techniques from a natural description of the candidate.

- [0027-chargebee-nuevo-cliente.json](workflows/0027-chargebee-nuevo-cliente.json)
  Description: This automated flow allows creating a new customer in Chargebee when the manual task is executed.

- [0028-verificacion-email-deliverable.json](workflows/0028-verificacion-email-deliverable.json)
  Description: This flow verifies if the email 'mcolomer@gmail.com' is valid and deliverable using an external service.

- [0029-mattermost-emelia-trigger.json](workflows/0029-mattermost-emelia-trigger.json)
  Description: This automated flow sends notifications to Mattermost when someone responds in a specific Emelia campaign.

- [0030-iss-monitoring-sqs.json](workflows/0030-iss-monitoring-sqs.json)
  Description: This automated flow checks the position of the ISS satellite every minute via an API and stores the data in variables for later use.

- [0031-webflow-crear-y-actualizar.json](workflows/0031-webflow-crear-y-actualizar.json)
  Description: This flow allows creating and updating an item in a Webflow collection via manual activation.

- [0032-iss-satellite-monitoring.json](workflows/0032-iss-satellite-monitoring.json)
  Description: This automated flow periodically queries the position of the ISS satellite via an API and loads the data into Google BigQuery.

- [0033-ip-location-email.json](workflows/0033-ip-location-email.json)
  Description: This flow checks if the user is in Spain via their IP and sends a welcome email in Spanish or English depending on the detected location.

- [0034-clearbit-persona-buscar.json](workflows/0034-clearbit-persona-buscar.json)
  Description: This flow allows searching for detailed information about a person using their email via the Clearbit API.

- [0035-airtable-mailcheck-validacion.json](workflows/0035-airtable-mailcheck-validacion.json)
  Description: This flow automatically verifies the email of a contact in the database and updates the 'Valid' field in an Airtable table with the result. It first lists Airtable records, then takes the email to perform verification via Mailcheck API.

- [0036-mattermost-notificacion-iniciado.json](workflows/0036-mattermost-notificacion-iniciado.json)
  Description: This workflow uses n8n's automatic start to send a message in the specified Mattermost channel with the exact time of activation.

- [0037-mattermost-trigger.json](workflows/0037-mattermost-trigger.json)
  Description: This reverse flow uses a Mattermost update as input to trigger an event and send the configured message.

- [0038-orbit-member-update.json](workflows/0038-orbit-member-update.json)
  Description: This flow automates the creation and updating of a member in Orbit, adds their tags, creates a custom note for them, and publishes an existing article to their profile.

- [0039-clickup-task-creator.json](workflows/0039-clickup-task-creator.json)
  Description: This automated flow allows creating a task in ClickUp via a manual trigger.

- [0040-screenshot-automation.json](workflows/0040-screenshot-automation.json)
  Description: This automated flow generates screenshots of the webpage https://uproc.io in full and normal mode, uploads them to Dropbox with specific paths, and sends an email with both files attached.

- [0041-filemaker-multi-step.json](workflows/0041-filemaker-multi-step.json)
  Description: This automated flow executes sequential FileMaker actions: first, it creates a record in 'My Form Layout', then it edits the country in the same table, and finally, it queries an existing record.

- [0042-iss-mqtt-flow.json](workflows/0042-iss-mqtt-flow.json)
  Description: This automated flow executes an HTTP call every minute to get the current position of the International Space Station from api.wheretheiss.at, processes the data, and sends it via MQTT to the topic 'iss-position'.


- [0044-gmail-drive-adjunto.json](workflows/0044-gmail-drive-adjunto.json)
  Description: This automated flow extracts messages from Gmail, saves attachments to Google Drive, and then gets the direct link to facilitate access.

- [0045-google-books-automation.json](workflows/0045-google-books-automation.json)
  Description: This automated flow gets information about a specific volume and adds it to a bookshelf in the Google Books API via a sequence of calls with OAuth2 authentication.

- [0046-email-invite-calendar.json](workflows/0046-email-invite-calendar.json)
  Description: This automated flow sends an email invitation to a specific meeting when the 'execute' button is clicked, attaching the corresponding iCal file.

- [0047-calendly-notion-auto.json](workflows/0047-calendly-notion-auto.json)
  Description: This automated flow creates a new record in a Notion database every time an 'invitee' is created in Calendly.

- [0048-notion-mattermost-marketing.json](workflows/0048-notion-mattermost-marketing.json)
  Description: This automated flow checks if a new page in the specific Notion database belongs to the Marketing team and, if so, sends a message to Mattermost with details about the new page.

- [0049-chargebee-event-trigger.json](workflows/0049-chargebee-event-trigger.json)
  Description: This automated flow receives updates for any event in Chargebee.

- [0050-calendly-humantic-personality-analysis.json](workflows/0050-calendly-humantic-personality-analysis.json)
  Description: This automated flow responds to Calendly events (such as the creation of an invitee) to execute personality analysis with Humantic AI and subsequently store the results in a Notion database page.

- [0052-release-content-publisher.json](workflows/0052-release-content-publisher.json)
  Description: This automated flow allows obtaining and publishing all content whose name starts with 'release' using Storyblok.

- [0053-ssl-expiry-checker.json](workflows/0053-ssl-expiry-checker.json)
  Description: This automated flow checks if the SSL certificate for n8n.io has expired and sends a Telegram notification if it has.

- [0054-clickup-trigger.json](workflows/0054-clickup-trigger.json)
  Description: This automated flow is triggered upon receiving updates of any event in the ClickUp tool.

- [0055-line-message-processing.json](workflows/0055-line-message-processing.json)
  Description: This flow analyzes received messages and processes different actions according to their type.

- [0056-aws-transcribe-s3.json](workflows/0056-aws-transcribe-s3.json)
  Description: This flow runs AWS Transcribe on all files found in the S3 bucket 'n8n-docs'.

- [0057-uptime-robot-monitor-management.json](workflows/0057-uptime-robot-monitor-management.json)
  Description: This automated flow uses UptimeRobot to manage web monitors: first, it creates a monitor with the given parameters, then updates it immediately, and finally gets the status of the existing monitor.

- [0058-microsoft-todo-blueprint.json](workflows/0058-microsoft-todo-blueprint.json)
  Description: This flow allows creating and updating tasks in Microsoft To Do via a manual trigger. It starts with the trigger activation that initializes the process. Then it creates a new task (create) specifying details like task list, high importance, and content. Subsequently, it updates that same task using the data returned by the creation to identify it.

- [0059-mattermost-bot-config.json](workflows/0059-mattermost-bot-config.json)
  Description: This workflow initializes and saves the necessary configurations for the Mattermost bot's operation to a binary file.

- [0060-notion-sigalerts.json](workflows/0060-notion-sigalerts.json)
  Description: This automated flow uses the Notion trigger to receive events related to database changes, processes these events through functions, and then updates records in Notion according to detected states (Open, Resolved, Annotated, or No one aware). It also integrates with SIGNL4 to send alerts.

- [0061-flujo-buscar-empresa.json](workflows/0061-flujo-buscar-empresa.json)
  Description: This flow searches and verifies the existence of a company by its name using an external service.

- [0062-active-campaign-account-trigger.json](workflows/0062-active-campaign-account-trigger.json)
  Description: This workflow is triggered when an administrator adds a new account in ActiveCampaign.

- [0063-standup-bot-config.json](workflows/0063-standup-bot-config.json)
  Description: This automated flow allows the standup bot to load a configuration from a local file.

- [0064-twitter-if-trigger.json](workflows/0064-twitter-if-trigger.json)
  Description: This automated flow executes a fixed message on Twitter when activated by a manual click or by the evaluation of a numerical condition that depends on the iteration index ($runIndex), then proceeds to NoOp and Twitter nodes according to the results.

- [0065-telegram-deploy-automation.json](workflows/0065-telegram-deploy-automation.json)
  Description: This automated flow listens to Telegram messages, checks if they contain '/deploy', and if so, extracts the first argument as a version tag. It then triggers an action on GitHub to create a release.

- [0066-pipedrive-crear-deal.json](workflows/0066-pipedrive-crear-deal.json)
  Description: This automated flow creates a new deal in Pipedrive when the manualTrigger is clicked.

- [0067-obtener-registros-dns.json](workflows/0067-obtener-registros-dns.json)
  Description: This automated flow gets the DNS records of a specific domain using n8n.

- [0068-line-chatbot-config-override.json](workflows/0068-line-chatbot-config-override.json)
  Description: This flow allows updating the chatbot configuration via a manual trigger and saving it in binary format.

- [0069-line-weather-kelvin.json](workflows/0069-line-weather-kelvin.json)
  Description: This automated flow sends a weather update message daily at 9:00 AM with the current temperature in Kelvin (Celsius degrees) for Berlin via LINE.

- [0070-114_validar_telefono.json](workflows/0070-114_validar_telefono.json)
  Description: This automated flow verifies if the phone number +34605281220 is valid using a validation process via uProc. It starts with a manual trigger that initiates the flow, then sets a 'phone' variable in the flow data and sends it to a verification service.

- [0071-pipedrive-change-monitor.json](workflows/0071-pipedrive-change-monitor.json)
  Description: This flow monitors all changes in Pipedrive via its webhook and executes automated actions.

- [0072-medium-rss-feed.json](workflows/0072-medium-rss-feed.json)
  Description: This automated flow processes N8N RSS feeds from Medium in batches.

- [0073-hubspot-pagination.json](workflows/0073-hubspot-pagination.json)
  Description: This automated flow gets multiple pages of results from the HubSpot API for contacts.

- [0074-getresponse-contact-update-flow.json](workflows/0074-getresponse-contact-update-flow.json)
  Description: This automated flow allows getting all contacts from GetResponse and updating their campaignId field if the campaign is not equal to 'n8n'.

- [0075-syncro-opsgenie-integration.json](workflows/0075-syncro-opsgenie-integration.json)
  Description: This automated flow allows integrating incidents from the Syncro tool with OpsGenie, creating and closing alerts automatically based on events received by a webhook.

- [0076-google-calendar-status-hue.json](workflows/0076-google-calendar-status-hue.json)
  Description: This flow automatically checks events started in Google Calendar every 5 minutes. Then, it assigns specific colors or states (like '4dw_leading' or 'Lavendar') to a variable called calColor and uses this information to control Philips Hue smart lights via HTTP POST webhooks according to the determined state. Finally, it updates the user's Slack profile with related text and emoji.

- [0077-conversor-json-a-xml.json](workflows/0077-conversor-json-a-xml.json)
  Description: This flow converts JSON data to XML using the 'Set' node to define specific values and responds via a webhook.

- [0078-comida-diaria-recipe.json](workflows/0078-comida-diaria-recipe.json)
  Description: This automated flow searches for recipes on Edamam according to specified parameters, including random diet and health conditions if configured. It then calculates the correct range of recipes to send by email.

- [0079-sheets-to-dropbox.json](workflows/0079-sheets-to-dropbox.json)
  Description: This automated flow reads a spreadsheet every 15 minutes and converts it into an XLS file to upload to Dropbox.

- [0080-shopify-product-alerts.json](workflows/0080-shopify-product-alerts.json)
  Description: This automated flow sends a message when a new product is created in Shopify, both to Twitter and Telegram chat.

- [0081-shopify-pedidos-trigger.json](workflows/0081-shopify-pedidos-trigger.json)
  Description: This automated flow processes the creation of new orders in Shopify to synchronize data with Zoho CRM, create tasks in Trello, and send email communications if the order exceeds a minimum value.

- [0082-shopify-reportes-semanal.json](workflows/0082-shopify-reportes-semanal.json)
  Description: This automated flow runs a report every week at 10:00 AM that collects all Shopify orders, calculates the total number and their sum, adds this data to a Google Sheets spreadsheet, and sends a Slack message with this information.

- [0083-harvest-cliente-ciclo.json](workflows/0083-harvest-cliente-ciclo.json)
  Description: This n8n flow allows creating a client in Harvest via manual execution.

- [0084-telegram-profanity-detector.json](workflows/0084-telegram-profanity-detector.json)
  Description: This automated flow detects and responds with a warning message when inappropriate language (profanity) is identified in messages received by the Telegram bot.

- [0085-n8n_LinkedIn_Interactions_Automation.json](workflows/0085-n8n_LinkedIn_Interactions_Automation.json)
  Description: This automated flow processes LinkedIn interactions (comments and likes) to obtain contact data and update or create new records in Airtable, in addition to adding them to Lemlist and Hubspot.

- [0086-calendly-pipedrive-slack.json](workflows/0086-calendly-pipedrive-slack.json)
  Description: This automated flow is triggered when an invitee is created in Calendly. It creates an activity in Pipedrive with the meeting details and sends a reminder to Slack for the sales team about the meeting, asking them to write their notes.

- [0087-github-backup-flujos.json](workflows/0087-github-backup-flujos.json)
  Description: This automated flow runs jobs every day at 11:59 PM and saves the edited content in JSON files in a GitHub repository.

- [0088-typeform-hubspot-email.json](workflows/0088-typeform-hubspot-email.json)
  Description: This automated flow captures data from a Typeform form, creates or updates contacts in HubSpot, and sends personalized information by email when the prospect shows interest.

- [0089-hubspot-deals-processing.json](workflows/0089-hubspot-deals-processing.json)
  Description: This automated flow processes the properties of a deal in HubSpot, determining if it is high priority or not. It then sends notifications to Slack and saves information in Airtable, in addition to generating presentations in Google Slides.

- [0090-GitHub-issue-autoassign.json](workflows/0090-GitHub-issue-autoassign.json)
  Description: This flow automatically assigns the issue author or whoever is requested in a conversation.

- [0091-steam-cloudflare-phishing-monitor.json](workflows/0091-steam-cloudflare-phishing-monitor.json)
  Description: This flow verifies domains on Steam to detect if they are hosted on Cloudflare using dig commands and sends email alerts when potential phishing sites are identified.

- [0092-segment-track-event.json](workflows/0092-segment-track-event.json)
  Description: This flow allows manually sending an event to Segment when activated by the 'execute' button.

- [0093-pokemon-rate-limiter.json](workflows/0093-pokemon-rate-limiter.json)
  Description: This flow checks usage limits per minute and hour via Redis, queries Pokémon data from Airtable, and uses webhooks to process responses.

- [0094-zendesk-ticket-flow.json](workflows/0094-zendesk-ticket-flow.json)
  Description: This automated flow allows creating a ticket in Zendesk via manual activation.

- [0095-sequential-http-post.json](workflows/0095-sequential-http-post.json)
  Description: This flow allows manually starting execution, getting all customer data from storage, splitting it into individual batches, and sending each via an HTTP POST request to the JSONPlaceholder API.

- [0096-news-hacker.json](workflows/0096-news-hacker.json)
  Description: This automated flow collects titles and URLs of news from Hacker News, exports them as a CSV or Excel file, and sends an email notification.

- [0097-netlify-to-airtable.json](workflows/0097-netlify-to-airtable.json)
  Description: This automated flow captures Netlify form submissions and automatically adds them to a specific table in Airtable.

- [0098-line-chatbot-memory.json](workflows/0098-line-chatbot-memory.json)
  Description: This automated flow allows a message received on the webhook to be used to create a resource in Netlify using dynamic data.

- [0099-crear-contacto-drift.json](workflows/0099-crear-contacto-drift.json)
  Description: This flow allows creating a contact in the Drift platform manually by clicking the trigger.

- [0100-zulip-send-private-message.json](workflows/0100-zulip-send-private-message.json)
  Description: This flow allows sending a private message in Zulip via a manual trigger.

- [0101-github-issue-auto-assignment.json](workflows/0101-github-issue-auto-assignment.json)
  Description: This automated flow automatically assigns GitHub issues to the person who created or commented on them when no one is assigned.

- [0102-google-calendar-meetings-slack.json](workflows/0102-google-calendar-meetings-slack.json)
  Description: This automated flow queries Gmail calendar events and compares them with today to send a list of scheduled meetings via Slack.

- [0104-vero-profile-creation.json](workflows/0104-vero-profile-creation.json)
  Description: This manual flow allows creating user profiles in Vero through direct execution, using the parameters defined in the Vero node.

- [0105-invoicing-textract-s3.json](workflows/0105-invoicing-textract-s3.json)
  Description: When the button is clicked, a 'Rechnung.jpg' file is uploaded to the S3 folder and then Amazon Textract processes it.

- [0106-google-drive-email-alert.json](workflows/0106-google-drive-email-alert.json)
  Description: This automated flow sends an email when a file is created in a specific Google Drive folder.

- [0107-salesmate-company-creator.json](workflows/0107-salesmate-company-creator.json)
  Description: This flow allows creating a company entry in the Salesmate system via a manual trigger when clicked.

- [0108-hubspot-trigger-para-chatbot.json](workflows/0108-hubspot-trigger-para-chatbot.json)
  Description: This automated flow uses the HubSpot trigger to initiate and update contact data with information obtained from Clearbit via the email address.

- [0109-ph-discord-rank.json](workflows/0109-ph-discord-rank.json)
  Description: This automated flow queries the Product Hunt API every hour to get the most upvoted projects and sends the formatted details in a message to Discord.

- [0110-info-uplead-company.json](workflows/0110-info-uplead-company.json)
  Description: This automated flow allows obtaining detailed information about a specific company using the UpLead service.

- [0111-onfleet-tasks-from-spreadsheet.json](workflows/0111-onfleet-tasks-from-spreadsheet.json)
  Description: This flow loads an Excel file from a local path and uses it to create tasks in Onfleet.

- [0112-lem-list-carga.json](workflows/0112-lem-list-carga.json)
  Description: This flow allows loading contact data from Dropcontact into a Google sheet and then transferring them as leads to Lemlist.

- [0113-webhook-html-response.json](workflows/0113-webhook-html-response.json)
  Description: This basic flow sets up a webhook that listens to the 'my-form' route and responds with HTML that includes Bootstrap.

- [0114-flujo-tareas.json](workflows/0114-flujo-tareas.json)
  Description: This flow allows getting all tasks of a specific flow via a manual trigger.

- [0115-facebook-profile-changes-mattermost.json](workflows/0115-facebook-profile-changes-mattermost.json)
  Description: This automated flow sends a Mattermost notification when a user updates their Facebook profile.

- [0116-typeform_lead_workflow.json](workflows/0116-typeform_lead_workflow.json)
  Description: This automated flow allows a chatbot to process leads from Typeform and perform operations in Airtable: if the contact does not exist, it creates it; if it already exists, it updates its fields. It also sends Slack notifications when a lead is added or updated.

- [0117-calendly-dropcontact-notion-integracion.json](workflows/0117-calendly-dropcontact-notion-integracion.json)
  Description: This automated flow allows integrating Calendly events with the DropContact system and storing the data in a Notion database.

- [0118-slack-error-alert.json](workflows/0118-slack-error-alert.json)
  Description: This automated flow sends a notification message to the Slack node when an error occurs in the 'Error Trigger' workflow.

- [0119-close-date-automation.json](workflows/0119-close-date-automation.json)
  Description: This automated flow checks if a close date exists and, if not, sets it to three weeks later.

- [0120-customer-data-post.json](workflows/0120-customer-data-post.json)
  Description: This automated flow starts manually with a click, sets an API key, and then gets all person data from the dataStore to send via POST to webhook.site.

- [0121-crm-sync.json](workflows/0121-crm-sync.json)
  Description: This flow synchronizes contacts between Pipedrive and HubSpot by obtaining all records from both systems, then uses 'Merge' to combine data when they match by email or name.

- [0122-sync-hubspot-pipedrive.json](workflows/0122-sync-hubspot-pipedrive.json)
  Description: This flow synchronizes contacts between HubSpot and Pipedrive via a cron trigger every minute, using email matches to merge records.

- [0125-flow-trigger-task.json](workflows/0125-flow-trigger-task.json)
  Description: This automated flow is triggered when an update occurs in any specified task.

- [0126-sanitized-invoices-upload.json](workflows/0126-sanitized-invoices-upload.json)
  Description: This flow reads emails from the 'Invoices' mailbox on an IMAP server and processes each attachment, sanitizing the filename to remove special characters, before uploading it to Nextcloud.

- [0127-github-release-to-gitlab-issue.json](workflows/0127-github-release-to-gitlab-issue.json)
  Description: This flow monitors the latest releases of a GitHub repository weekly and checks if a corresponding issue exists in the attached GitLab repository. If there is no match, it automatically creates a new issue.

- [0128-iss-position-firebase.json](workflows/0128-iss-position-firebase.json)
  Description: This automated flow collects the current position of the ISS from an API every minute and stores the data in real-time in a Firebase database.

- [0129-twitter-banner-creator.json](workflows/0129-twitter-banner-creator.json)
  Description: This automated flow allows downloading recent Twitter followers' profiles, processing their avatar images (resizing and cropping), combining them with a background image through multi-stage composition, and finally uploading them as a banner using the OAuth1.0 API.

- [0130-config-impresao.json](workflows/0130-config-impresao.json)
  Description: This automated flow queries printing configuration and fabric roll information to issue labels.

- [0131-limpia_pacotes_telegram.json](workflows/0131-limpia_pacotes_telegram.json)
  Description: This automated flow executes daily SQL queries to clean transport packages in the 'PPM' database and then updates old records to 'DELETE'. Afterwards, it sends a predefined message to the specified chatId.

- [0132-line-chatbot-memory.json](workflows/0132-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation by remembering the name and email of the user who activates it.

- [0133-gitlab-release-outline.json](workflows/0133-gitlab-release-outline.json)
  Description: This flow automatically detects the creation of a new tag in the GitLab 'ci-test' repository and, if it is a release tag, creates an Outline document based on the provided data.

- [0134-tweet-image-jokes.json](workflows/0134-tweet-image-jokes.json)
  Description: This automated flow executes a task every day at 5:00 PM to get graphic jokes from the Blablagues API and then publishes them on Twitter using images.

- [0135-dominio-email-extractor.json](workflows/0135-dominio-email-extractor.json)
  Description: This flow extracts the domain from a provided email using a function.

- [0136-torrent-search-transmission.json](workflows/0136-torrent-search-transmission.json)
  Description: This automated flow searches for torrents on KickassTorrents and Rarbg from a title provided by a POST Webhook request. If a torrent is found, it attempts to add it to the Transmission client for download. If no results are found or a 409 error (conflict) is received, it notifies that the movie is not available.

- [0137-tareas-toggl-alertas.json](workflows/0137-tareas-toggl-alertas.json)
  Description: This automated flow continuously monitors new time entries in Toggl.

- [0138-telegram-receipts-textract.json](workflows/0138-telegram-receipts-textract.json)
  Description: This automated flow allows receiving a document (likely an invoice) via Telegram bot, downloading it, and uploading it to S3 cloud storage. Subsequently, it uses AWS Textract to analyze the text contained in that file and finally saves the extracted results in a specific Airtable table.

- [0139-gdrive-aws-s3-sync.json](workflows/0139-gdrive-aws-s3-sync.json)
  Description: This flow monitors changes in a specific Google Drive file and synchronizes files with the 'mybucket' bucket in AWS S3 through get and upload operations, using a 'merge' node to combine data.

- [0140-onfleet-shopify-task.json](workflows/0140-onfleet-shopify-task.json)
  Description: This automated flow synchronizes the creation of a new fulfillment in Shopify with the corresponding generation of a task in Onfleet.

- [0141-twilio-mautic-form-sms.json](workflows/0141-twilio-mautic-form-sms.json)
  Description: This automated flow receives notifications when a form is submitted in Mautic and sends an SMS confirmation.

- [0142-xml-to-json-dropbox.json](workflows/0142-xml-to-json-dropbox.json)
  Description: This flow takes XML data from a URL, converts it to JSON format using the 'To JSON' node, then updates the message title with the 'Change title' parameter, and finally uploads the JSON content to Dropbox using the specified path.

- [0143-rekognition-google-images.json](workflows/0143-rekognition-google-images.json)
  Description: This automated flow searches for street images from Google and uses AWS Rekognition to analyze them and extract labels. It then combines these results with the original data and saves everything in a Google spreadsheet.

- [0144-funcion-hoy.json](workflows/0144-funcion-hoy.json)
  Description: This flow uses the Function node to get the current date in ISO format and the day of the week.

- [0145-readwise_telegram_sync.json](workflows/0145-readwise_telegram_sync.json)
  Description: This automated flow synchronizes books and articles from Readwise with Telegram, sending summaries and details.

- [0146-baserow-release-feed.json](workflows/0146-baserow-release-feed.json)
  Description: This automated flow collects blog articles about 'release' from baserow.io and generates an XML response that can be used to feed RSS feeds or webhooks.

- [0147-set-variables-flujo.json](workflows/0147-set-variables-flujo.json)
  Description: This flow uses a manual trigger to execute a Set node, which allows defining default values for different variables based on the specified type.

- [0148-daily-weather-spontit.json](workflows/0148-daily-weather-spontit.json)
  Description: This automated flow checks the current weather conditions in Berlin every day at 9 AM and sends a push notification to the user with the current temperature.

- [0150-workflow-spreadsheet-export.json](workflows/0150-workflow-spreadsheet-export.json)
  Description: This n8n flow processes a webhook input containing lists of items, converts these into an Excel file (.xlsx), and responds to the webhook with the spreadsheet as an attachment.

- [0151-line-chatbot-response-token.json](workflows/0151-line-chatbot-response-token.json)
  Description: This flow processes LINE webhook requests, using HMAC SHA256 on a received token and storing the result as 'response_token' to maintain contextualized memory.

- [0152-gdpr-data-deletion.json](workflows/0152-gdpr-data-deletion.json)
  Description: This automated flow handles slash commands in Slack to request data deletion according to GDPR. It validates that the token and email address are present, processes deletions from different services (Paddle, Customer.io, and Zendesk), and then logs these events in an Airtable database.

- [0153-145-traductor-cocinas.json](workflows/0153-145-traductor-cocinas.json)
  Description: This automated flow allows getting cocktail instructions from an API and translating them automatically into Italian.

- [0154-hubspot-company-alerts.json](workflows/0154-hubspot-company-alerts.json)
  Description: This flow is triggered when a new company is created in HubSpot and checks if it has deliverability issues or if its domain is invalid/disposable email, sending alerts via Slack.

- [0155-mattermost-financial-metrics-cron.json](workflows/0155-mattermost-financial-metrics-cron.json)
  Description: This automated flow sends monthly financial metrics from ProfitWell to Mattermost every day at a scheduled time.

- [0156-news-ycombinator-telegram.json](workflows/0156-news-ycombinator-telegram.json)
  Description: This flow periodically checks if the news server response has changed using two identical HTTP requests and a Telegram bot to notify when changes occur.

- [0157-line-syncro-timer-sync.json](workflows/0157-line-syncro-timer-sync.json)
  Description: This automated flow synchronizes time entries in Syncro from a webhook that receives information about phone calls from a chatbot.

- [0159-strava-accountability-checker.json](workflows/0159-strava-accountability-checker.json)
  Description: This daily flow checks that a user has logged enough active time in Strava (minimum defined in accountability hours) and sends motivational emails to their team if they do not.

- [0160-sendy-subscribe-campaign.json](workflows/0160-sendy-subscribe-campaign.json)
  Description: This automated flow allows adding a subscriber to a list and creating/sending a campaign when manually activated.

- [0161-onfleet-driver-signup-alert.json](workflows/0161-onfleet-driver-signup-alert.json)
  Description: This automated flow sends a message to Slack when a new driver is created in Onfleet.

- [0162-crypto-portfolio-updater.json](workflows/0162-crypto-portfolio-updater.json)
  Description: This automated flow updates crypto asset values in an Airtable base every hour with current data from CoinGecko.

- [0163-mock-transactions-sum.json](workflows/0163-mock-transactions-sum.json)
  Description: This flow uses function nodes to generate mocked data with amounts in USD and calculate the total sum.

- [0164-mattermost-airtable-trigger.json](workflows/0164-mattermost-airtable-trigger.json)
  Description: This flow monitors a record in Airtable called 'Data' and sends a notification to the specified Mattermost channel when new information is added.

- [0165-hashtag-tweet-generator.json](workflows/0165-hashtag-tweet-generator.json)
  Description: This flow randomly selects a hashtag from a predefined list, generates a tweet using the OpenAI API, and saves it to an Airtable table.

- [0167-shopify-onfleet-tags-sync.json](workflows/0167-shopify-onfleet-tags-sync.json)
  Description: This automated flow updates the tags of a product in Shopify whenever a delay is detected in an Onfleet task.

- [0168-Onfleet-to-QuickBooks-Invoices.json](workflows/0168-Onfleet-to-QuickBooks-Invoices.json)
  Description: This automated flow creates an invoice in QuickBooks Online when a new task is generated in Onfleet.

- [0169-onfleet-task-from-google-drive.json](workflows/0169-onfleet-task-from-google-drive.json)
  Description: This automated flow creates a task in Onfleet when a specific file in Google Drive is updated.

- [0170-rss-security-monitor.json](workflows/0170-rss-security-monitor.json)
  Description: This automated flow monitors multiple RSS feeds for new content, using a mechanism to avoid duplicate submissions. When new information is detected, it sends notifications to different Telegram accounts according to their category (security, IT, or Microsoft 365).

- [0171-if-condition-checker.json](workflows/0171-if-condition-checker.json)
  Description: This flow takes a predefined JSON output, parses it, and then checks if the value of 'value1' (which is always true in this example) meets the expected condition.

- [0172-slack-file-downloader.json](workflows/0172-slack-file-downloader.json)
  Description: This manual flow downloads a file from the specified URL and sends it to a Slack channel using OAuth2 authentication.

- [0173-sinonimos_aleman_openthesaurus_api.json](workflows/0173-sinonimos_aleman_openthesaurus_api.json)
  Description: This flow allows obtaining synonyms of a term in German using the OpenThesaurus API.

- [0174-adobesign-webhook-data.json](workflows/0174-adobesign-webhook-data.json)
  Description: This automated flow sets up a webhook response that includes the clientID variable and extracts specific data from the JSON body about agreements and participants.

- [0175-pagerduty-incident-flow.json](workflows/0175-pagerduty-incident-flow.json)
  Description: This automated flow allows creating an incident in PagerDuty, updating it, and then getting its details.

- [0176-weather-api.json](workflows/0176-weather-api.json)
  Description: This automated flow allows obtaining weather information (temperature and description) of any city specified via an HTTP request. It collects data from the OpenWeatherMap API and creates two variables: 'temp' for temperature and 'description' for the weather state.

- [0177-youtube-telegram-monitor.json](workflows/0177-youtube-telegram-monitor.json)
  Description: This automated flow checks every 30 minutes if there are new YouTube videos on a specific channel, compares them with already processed IDs to avoid duplicates, and sends a Telegram notification when new content is detected.

- [0178-thehive-case-management.json](workflows/0178-thehive-case-management.json)
  Description: This automated flow allows creating, updating, and getting a case in TheHive through a sequence of connected steps.

- [0179-bubble-data-access.json](workflows/0179-bubble-data-access.json)
  Description: This flow allows making an authenticated HTTP request to access user data from the Bubble API.

- [0180-gitlab-backup.json](workflows/0180-gitlab-backup.json)
  Description: This automated flow allows performing backups of n8n workflows and credentials using Git commands, which are executed periodically or manually.

- [0181-cortex-abuse-detector.json](workflows/0181-cortex-abuse-detector.json)
  Description: This flow analyzes a URL using the Abuse Finder node in Cortex, and then gets the job details using the returned ID.

- [0182-logo-download-script.json](workflows/0182-logo-download-script.json)
  Description: This automated flow downloads an image from a URL and writes it to the local file system.

- [0183-questdb-tabla-datos.json](workflows/0183-questdb-tabla-datos.json)
  Description: This automated flow creates a 'test' table with id and name columns in QuestDB when manually executed.

- [0184-thehive-event-monitor.json](workflows/0184-thehive-event-monitor.json)
  Description: This flow monitors all events in TheHive system and triggers an action when one occurs.

- [0185-datos-binarios-descomprimidos.json](workflows/0185-datos-binarios-descomprimidos.json)
  Description: This automated flow downloads a ZIP file containing binary data and splits it into individual items, each with a single sequence of binary data under the 'data' key.

- [0186-164_Crear-canal-invitar-y-subir-archivo.json](workflows/0186-164_Crear-canal-invitar-y-subir-archivo.json)
  Description: This automated flow creates a Slack channel using a bot, invites the specified users, and then sends a welcome message along with the n8n logo.

- [0187-165_create_update_get_user_iterable.json](workflows/0187-165_create_update_get_user_iterable.json)
  Description: This flow allows creating, updating, and retrieving user information via the Iterable API.

- [0188-kafka-temp-alert.json](workflows/0188-kafka-temp-alert.json)
  Description: This flow receives Kafka messages from the topic_test topic and sends an SMS when the temperature exceeds 50 degrees.

- [0189-url-shortener-stats.json](workflows/0189-url-shortener-stats.json)
  Description: This n8n flow creates a short URL from a provided link and then gets statistics about the performance and reach of that same shortened URL.

- [0190-smart-factory-data-generator.json](workflows/0190-smart-factory-data-generator.json)
  Description: This automated flow generates random temperature and uptime data for an industrial machine, using a fixed name 'n8n_cr8' as an identifier, and sends it periodically via AMQP.

- [0192-reporte-tiempo-hilo.json](workflows/0192-reporte-tiempo-hilo.json)
  Description: This automated flow generates a detailed HTML report from timesheet records for users and tasks.

- [0193-user-request-management.json](workflows/0193-user-request-management.json)
  Description: This automated flow handles user requests from a Typeform form and classifies them into different types (Documentation, Presentation, etc.) to process them appropriately in ClickUp.

- [0194-customer-data-processing.json](workflows/0194-customer-data-processing.json)
  Description: This workflow uses a manual trigger to get customer data from the 'Customer Datastore' and then edits it in a variable using the Set node.

- [0195-ghost-post-automation.json](workflows/0195-ghost-post-automation.json)
  Description: This automated flow allows creating a post in Ghost, updating its status to published, and then getting information about the created post.

- [0196-airtable-insert-update.json](workflows/0196-airtable-insert-update.json)
  Description: This automated flow inserts an initial record into Airtable's Table 1, then lists records filtered by the 'Name' field equal to 'n8n', and finally updates the first found record with the values defined in the Set step.

- [0197-snowflake-table-management.json](workflows/0197-snowflake-table-management.json)
  Description: This automated flow allows creating a table in Snowflake and performing data insertions and updates using previously defined operations.

- [0198-csv-conversion.json](workflows/0198-csv-conversion.json)
  Description: This flow allows you to read a CSV file, process it as a spreadsheet, and convert it to JSON format for storage.

- [0200-users-api-spreadsheet.json](workflows/0200-users-api-spreadsheet.json)
  Description: This flow uses the randomuser.me API to get data and then extracts it in JSON format. Subsequently, it updates a Google spreadsheet with these values and also generates a CSV file.

- [0201-users-data-flow.json](workflows/0201-users-data-flow.json)
  Description: This flow gets random user data from the randomuser.me API, processes it, and stores it in a Google sheet. It also creates a CSV file with that data and prepares an email to attach the JSON.

- [0202-twist-channel-automation.json](workflows/0202-twist-channel-automation.json)
  Description: This automated flow allows creating a new channel in Twist and then sending it a custom notification with an action link to the user.

- [0203-n8n-fecha-dinamica.json](workflows/0203-n8n-fecha-dinamica.json)
  Description: This flow uses Luxon expressions to dynamically calculate and format dates in n8n.

- [0204-clientes-condicion.json](workflows/0204-clientes-condicion.json)
  Description: This flow processes customer data through filters and conditional branches to segment them by country.

- [0205-workflow-merge-demo.json](workflows/0205-workflow-merge-demo.json)
  Description: This flow demonstrates how n8n's Merge node combines data from different sources using different join modes, showing examples from ingredients to band formation.

- [0206-n8n_paginacion_ejemplo.json](workflows/0206-n8n_paginacion_ejemplo.json)
  Description: This automated flow uses HTTP nodes to get data in a structured way (like lists of albums or web pages) and handle responses by creating items.

- [0207-workflow-automatico-mensajes-clientes.json](workflows/0207-workflow-automatico-mensajes-clientes.json)
  Description: This automated flow sends personalized messages to each customer obtained from a data store, waiting briefly between each message to avoid exceeding request limits, and then provides them with a specific URL for their interaction.

- [0208-apod-telegram-daily.json](workflows/0208-apod-telegram-daily.json)
  Description: This automated flow sends NASA's Astronomy Picture of The Day (APOD) every day at 8:00 PM in a message with its title as a caption via Telegram bot.

- [0209-google-search-url-generator.json](workflows/0209-google-search-url-generator.json)
  Description: This flow uses the Webhook node to receive input data, then creates a URL by concatenating those values (first and last letter) to generate a Google search, and finally responds to the webhook showing the generated URL.

- [0210-google-sheets-data-preparation.json](workflows/0210-google-sheets-data-preparation.json)
  Description: This flow processes data from the 'Customer Datastore' node to prepare it before performing an UPSERT operation in Google Sheets. The field format is adjusted: the 'name' field from the input is renamed to 'Full name', and a new 'Created time' field is added with the current date.

- [0211-etl-weekly-google-sheets-mysql.json](workflows/0211-etl-weekly-google-sheets-mysql.json)
  Description: This automated flow executes an insert into MySQL every week using data from Google Sheets.

- [0212-mysql-gsheets-semanal.json](workflows/0212-mysql-gsheets-semanal.json)
  Description: This automated flow executes a SQL query weekly on the books table and writes the result to a Google sheet.

- [0213-google-sheets-process-timer.json](workflows/0213-google-sheets-process-timer.json)
  Description: This automated flow checks every 5 minutes if there are unprocessed rows in a spreadsheet and marks them as such when manually executed.

- [0214-hoja-html-flujo.json](workflows/0214-hoja-html-flujo.json)
  Description: This automated flow reads data from a specific spreadsheet and converts it into an HTML file when a request is received via Webhook.

- [0215-html-sheet.json](workflows/0215-html-sheet.json)
  Description: This automated flow reads data from a Google Sheets spreadsheet and converts it into HTML with table format to respond via webhook.

- [0216-typeform-pipedrive-mapeo.json](workflows/0216-typeform-pipedrive-mapeo.json)
  Description: This automated flow collects data from a Typeform form and integrates it into Pipedrive to automatically create organization, person, and lead records, maintaining the mapping logic between the original format and custom properties.

- [0217-gestionar-correos-eliminar-y-agregar.json](workflows/0217-gestionar-correos-eliminar-y-agregar.json)
  Description: This flow allows getting Gmail messages marked with a specific label, removing that label, and adding a new one.

- [0218-asana-notion-sync.json](workflows/0218-asana-notion-sync.json)
  Description: This n8n flow synchronizes tasks between Asana and Notion via webhooks, creating or updating entries in the Notion database according to changes detected in Asana tasks.

- [0219-company-data-airtable.json](workflows/0219-company-data-airtable.json)
  Description: This flow extracts the logo, icon, and data of a company using Brandfetch, and automatically stores them in an Airtable table.

- [0220-mailchimp-nueva-cita.json](workflows/0220-mailchimp-nueva-cita.json)
  Description: This automated flow searches for new contacts created today in HubSpot, extracts their main properties, and adds them as members to a specific Mailchimp list every day at 07:00.

- [0221-line-mailchimp-sync.json](workflows/0221-line-mailchimp-sync.json)
  Description: This flow synchronizes contacts between LINE and Mailchimp using the HubSpot API.

- [0222-pipedrive-stripe-deal.json](workflows/0222-pipedrive-stripe-deal.json)
  Description: This flow checks if a deal in Pipedrive has been recently won and, if the associated customer does not exist in Stripe, creates it using the provided data.

- [0223-stripe-organization-sync.json](workflows/0223-stripe-organization-sync.json)
  Description: This automated flow seeks to process successful Stripe charges that occurred before the last execution time, searching in Pipedrive for the organization corresponding to each customer and creating a note with the charge details.

- [0224-pipedrive-stripe-product-sync.json](workflows/0224-pipedrive-stripe-product-sync.json)
  Description: This automated flow synchronizes new products from Pipedrive with Stripe via an API and then creates their corresponding price records.

- [0225-pipedrive-datagma-enrichment.json](workflows/0225-pipedrive-datagma-enrichment.json)
  Description: This automated flow uses Pipedrive to track organizations and personnel, enriching their data with information from Datorama such as Investment Fund and web traffic.

- [0226-tradegate-investment-report.json](workflows/0226-tradegate-investment-report.json)
  Description: This automated flow collects investment data stored in a Baserow table and queries current quotes on the Tradegate platform to generate a detailed report that is sent via email using SendGrid.

- [0227-pipedrive-organization-sync.json](workflows/0227-pipedrive-organization-sync.json)
  Description: This flow monitors an Excel file in Google Drive and creates organizations and contact information in Pipedrive based on its content.

- [0228-github-fork-to-pipedrive-lead.json](workflows/0228-github-fork-to-pipedrive-lead.json)
  Description: This flow detects forks on GitHub and creates leads in Pipedrive if the person does not exist.

- [0229-github-pullrequest-pipedrive.json](workflows/0229-github-pullrequest-pipedrive.json)
  Description: This automated flow searches Pipedrive for an existing user based on the email of a PR (Pull Request) creator detected by a GitHub webhook, and if it exists, adds a note to their account.

- [0230-mattermost-channel-onboarding.json](workflows/0230-mattermost-channel-onboarding.json)
  Description: This automated flow creates a Mattermost channel, adds members to it, and then posts a message in that same channel.

- [0231-line-chatbot-context.json](workflows/0231-line-chatbot-context.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation by using user data in personalized messages.

- [0232-agregar-archivo-json-a-hoja-google.json](workflows/0232-agregar-archivo-json-a-hoja-google.json)
  Description: This flow reads a JSON file and adds it to Google spreadsheets.

- [0233-salesforce-sync.json](workflows/0233-salesforce-sync.json)
  Description: This automated flow allows maintaining the relationship between Google Sheets companies and their corresponding data in Salesforce by creating both account and contact records.

- [0234-excel-to-salesforce.json](workflows/0234-excel-to-salesforce.json)
  Description: This automated flow extracts data from Microsoft Excel to search and create records in both account and contact in Salesforce.

- [0235-salesforce-carga-hoja-calculo.json](workflows/0235-salesforce-carga-hoja-calculo.json)
  Description: This flow processes data from a spreadsheet to create records in Salesforce: first, it searches for existing accounts, then creates new accounts if not found, and finally adds contacts linked to them.

- [0236-ard-podcast-scraper.json](workflows/0236-ard-podcast-scraper.json)
  Description: This automated flow extracts episode links from a webpage, then gets and processes the information for each episode to generate a complete RSS feed.

- [0237-firestore-document-management.json](workflows/0237-firestore-document-management.json)
  Description: This automated flow allows creating and updating documents in Google Cloud Firestore.

- [0238-nextcloud-spreadsheet.json](workflows/0238-nextcloud-spreadsheet.json)
  Description: This automated flow allows downloading an Excel file from NextCloud, processing it, and uploading it again to the same location after integrating data.

- [0239-github-issue-notion-sync.json](workflows/0239-github-issue-notion-sync.json)
  Description: This flow synchronizes GitHub Issues events with actions in a Notion database, allowing automatic updating of properties like title and status.

- [0240-shopify-zendesk-sync.json](workflows/0240-shopify-zendesk-sync.json)
  Description: This automated flow synchronizes customer information between Shopify and Zendesk when a contact is updated in Shopify.

- [0241-shopify-zendesk-sync.json](workflows/0241-shopify-zendesk-sync.json)
  Description: This flow checks if a Shopify order already exists in Zendesk. If not found, it creates a new ticket with the order information and updates the flow.

- [0243-google-drive-notion.json](workflows/0243-google-drive-notion.json)
  Description: This automated flow creates a page in a Notion database when a new file is uploaded to a specific Google Drive folder.

- [0244-zendesk-slack-sync.json](workflows/0244-zendesk-slack-sync.json)
  Description: This automated flow synchronizes Zendesk events with messages in Slack via webhooks.

- [0245-workflow-zendesk-asana.json](workflows/0245-workflow-zendesk-asana.json)
  Description: This automated flow checks if an Asana task already exists based on a custom Zendesk field, and updates the ticket with the corresponding information.

- [0246-monday-mautic-automation.json](workflows/0246-monday-mautic-automation.json)
  Description: This automated flow creates an item in Monday.com with the contact's name and email when a new one is saved in Mautic.

- [0247-calendly-mautic-sync.json](workflows/0247-calendly-mautic-sync.json)
  Description: This automated flow synchronizes data from Calendly with Mautic to create or update contacts when a new event is generated.

- [0248-shopify-mautic-contact.json](workflows/0248-shopify-mautic-contact.json)
  Description: This automated flow allows creating a contact in Mautic every time a new customer is created in Shopify.

- [0249-zendesk-github-integration.json](workflows/0249-zendesk-github-integration.json)
  Description: This automated flow synchronizes Zendesk tickets with issues and comments on GitHub.

- [0250-zendesk-jira-integracion.json](workflows/0250-zendesk-jira-integracion.json)
  Description: This automated flow integrates Zendesk and Jira: if a Zendesk ticket already has an associated Jira Issue Key, a comment is added to that existing issue; if it does not exist, a new issue is automatically created in Jira based on the Zendesk ticket.

- [0251-notion-clockify-invoices.json](workflows/0251-notion-clockify-invoices.json)
  Description: This automated flow automatically creates a record in a Notion database every time a new invoice is generated in Clockify.

- [0252-flujo-captura-emails.json](workflows/0252-flujo-captura-emails.json)
  Description: This automated flow processes email responses by categorizing them and executing actions such as creating leads in HubSpot or marking them in Lemlist, in addition to sending notifications via Slack.

- [0253-hubspot-zendesk-company-sync.json](workflows/0253-hubspot-zendesk-company-sync.json)
  Description: This flow synchronizes HubSpot company data with the Zendesk API to keep organizations updated.

- [0254-hubspot-zendesk-sync.json](workflows/0254-hubspot-zendesk-sync.json)
  Description: This automated flow synchronizes data between HubSpot and Zendesk systems, checking if the ticket exists before performing actions like creating or updating contacts and tickets.

- [0255-iss-position-rabbitmq.json](workflows/0255-iss-position-rabbitmq.json)
  Description: This flow sends the updated position of the International Space Station (ISS) to a RabbitMQ queue every minute.

- [0256-github-light-alert.json](workflows/0256-github-light-alert.json)
  Description: This flow activates a switch in Home Assistant to red when there are updates in the GitHub repository.

- [0257-analisis-domini.json](workflows/0257-analisis-domini.json)
  Description: This automated flow takes a list of web domains (divided into batches), queries their content via HTTP requests, asks OpenAI to analyze the text to obtain key properties about value proposition, audience, and sector, and then saves this classified data in a Google Sheets spreadsheet.

- [0258-rabbitmq-sms-alert.json](workflows/0258-rabbitmq-sms-alert.json)
  Description: This flow receives messages from a RabbitMQ queue containing a 'temp' field, and if it exceeds 50 degrees Celsius, sends an SMS alert using Vonage.

- [0259-mysql-export-spreadsheet.json](workflows/0259-mysql-export-spreadsheet.json)
  Description: This flow automates the download of data from a specific MySQL table in Excel format, thus allowing storage of the catalog content.

- [0260-woo-product-flow.json](workflows/0260-woo-product-flow.json)
  Description: This automated flow allows creating a product in WooCommerce, updating its stock, and then getting the created product.

- [0261-mattermost-woocommerce-pedido.json](workflows/0261-mattermost-woocommerce-pedido.json)
  Description: This automated flow sends a message in the specified Mattermost channel when a new order is created in WooCommerce, including the buyer's name and the first product purchased.

- [0262-diagnostico-migracion-n8n.json](workflows/0262-diagnostico-migracion-n8n.json)
  Description: This flow identifies workflows affected by the n8n 0.214.3 migration in nodes with multiple outputs.

- [0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json](workflows/0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json)
  Description: This flow allows creating a subscriber in a specific e-goi list, then modifying some fields (like the name), and finally getting the updated contact details.

- [0264-mattermost-language-inclusion.json](workflows/0264-mattermost-language-inclusion.json)
  Description: This automated flow detects gender-exclusive terms (like 'guys', 'bros') in incoming messages and suggests the use of inclusive language via a predefined message in Mattermost.

- [0265-customer-data-count-set.json](workflows/0265-customer-data-count-set.json)
  Description: This manual flow counts the number of customer records in the n8n Training database.

- [0266-mssql-to-csv.json](workflows/0266-mssql-to-csv.json)
  Description: This flow allows executing a SQL query on the 'SalesLT.ProductCategory' table and saving the result as a CSV file with that name.

- [0267-imagenes-line-merge.json](workflows/0267-imagenes-line-merge.json)
  Description: This automated flow downloads multiple sample images via HTTP requests and merges them into a single result containing all concatenated binary data.

- [0268-uProc_telegram_screenshot.json](workflows/0268-uProc_telegram_screenshot.json)
  Description: This automated flow allows creating screenshots of websites and automatically sending them to a Telegram channel.

- [0269-download-pdf-robot.json](workflows/0269-download-pdf-robot.json)
  Description: This automated flow allows downloading a specific PDF file from Deutsche Bahn when a GET request is received on the webhook.

- [0270-postgres-google-sheets-sync.json](workflows/0270-postgres-google-sheets-sync.json)
  Description: This automated flow listens for updates in the users table and filters them to save only those that do not have @n8n.io in the email.

- [0271-linear-alert-slack.json](workflows/0271-linear-alert-slack.json)
  Description: This automated flow detects urgent incident events in Linear and sends an alert to a specific Slack channel to notify the team.

- [0272-datos-aleatorios.json](workflows/0272-datos-aleatorios.json)
  Description: This workflow performs an HTTP request to an API service to obtain data and saves it in Google Sheets.

- [0273-outlook-automated-email.json](workflows/0273-outlook-automated-email.json)
  Description: This automated flow allows a user to automatically create an email draft in Outlook, attach a downloaded image, and send it.

- [0274-discord-calendar-sync.json](workflows/0274-discord-calendar-sync.json)
  Description: This flow automatically synchronizes events scheduled in Discord to Google Calendar. It detects if an event already exists or is new and proceeds to update or create it respectively.

- [0275-sheets-discord-table.json](workflows/0275-sheets-discord-table.json)
  Description: This automated flow sends a formatted ASCII table message from Google Sheets to a Discord channel when there are changes (new row or update) in the specified spreadsheet.

- [0276-notion-outlook-sync.json](workflows/0276-notion-outlook-sync.json)
  Description: This automated flow synchronizes Outlook calendar events with database pages in Notion by verifying and creating/updating based on the event ID.

- [0277-products-to-xml.json](workflows/0277-products-to-xml.json)
  Description: This flow randomly queries 16 products from a MySQL database and transforms them into two different XML files, maintaining the structure with tags using set functions.

- [0278-paul_graham_essays.json](workflows/0278-paul_graham_essays.json)
  Description: This automated flow allows extracting and summarizing the texts of up to three recent essays published on Paul Graham's website.

- [0279-gmail-appointment-autoresponder.json](workflows/0279-gmail-appointment-autoresponder.json)
  Description: This automated flow processes unread emails to determine if they are appointments and responds appropriately.

- [0280-line-chatbot-agent.json](workflows/0280-line-chatbot-agent.json)
  Description: This automated flow uses a LINE chatbot to handle messages, store context in buffer memory, and access OpenAI's GPT-4o-mini model. It also integrates the SerpAPI tool for web search.

- [0281-llm-chain-ai-agent.json](workflows/0281-llm-chain-ai-agent.json)
  Description: This flow executes an LLM chain to generate responses and uses an AI agent with tools like Wikipedia to improve searches in conversations.

- [0282-llm-output-structured.json](workflows/0282-llm-output-structured.json)
  Description: This flow processes requests with large language models (LLM) to generate structured responses, using an automatic parser that attempts to correct invalid outputs with another LLM model.

- [0283-cadena-q-a.json](workflows/0283-cadena-q-a.json)
  Description: This flow sets up a chain processing to perform question-based searches and answer them, using assignments as input.

- [0284-n8n-chat-conversational.json](workflows/0284-n8n-chat-conversational.json)
  Description: This flow allows the conversation to maintain context with the latest messages thanks to buffer memory storage. It uses search tools (SerpAPI) and Wikipedia to improve agent responses.

- [0285-bitcoin-chat-flow-pinecone.json](workflows/0285-bitcoin-chat-flow-pinecone.json)
  Description: This flow allows loading data from the Bitcoin White Paper from Google Drive into Pinecone using GPT-4o-mini embeddings and answering questions using vector tools.

- [0286-slack-gilfoyle-chatbot.json](workflows/0286-slack-gilfoyle-chatbot.json)
  Description: This n8n flow processes messages in Slack via a Webhook, using the Gilfoyle agent to generate sarcastic and irritable responses on defined topics. The system verifies if the message is human and not bot-generated, uses tools like web search (SerpAPI) and Wikipedia information as needed, and maintains conversation memory using the channel ID as a key.

- [0287-google-drive-summarizer.json](workflows/0287-google-drive-summarizer.json)
  Description: This flow allows downloading and processing a Google Drive file to generate summaries using summarization chains.

- [0288-line-ai-color-bot.json](workflows/0288-line-ai-color-bot.json)
  Description: This automated flow allows a line chatbot to generate responses with specific functions like selecting random colors.

- [0289-mistral-cadena-hf.json](workflows/0289-mistral-cadena-hf.json)
  Description: This flow uses a basic LLM chain connected to Hugging Face's Mistral-7B-Instruct-v0.1 model along with generation options like temperature and penalty.

- [0290-feedback-openai-google.json](workflows/0290-feedback-openai-google.json)
  Description: This automated flow allows collecting customer feedback through a form and using OpenAI to analyze its sentiment. The results, along with the form data, are combined and automatically saved in a Google sheet.

- [0291-telegram-n8n-control.json](workflows/0291-telegram-n8n-control.json)
  Description: This flow allows activating or deactivating n8n workflows via Telegram commands. Messages must start with '/start' or '/stop' followed by the workflow name to perform the corresponding action.

- [0292-snowflake-csv-insert.json](workflows/0292-snowflake-csv-insert.json)
  Description: This flow loads data from a CSV file hosted on Azure Blob Storage, processes it, and then inserts the specified columns into Snowflake's 'users' table.

- [0293-email-validation-flow.json](workflows/0293-email-validation-flow.json)
  Description: This flow automatically verifies the validity of an email address captured via a form and adds the contact to a list if it is valid.

- [0294-twentycrm-eventos-canales.json](workflows/0294-twentycrm-eventos-canales.json)
  Description: This automated flow gets notifications/events from TwentyCRM and distributes them through preferred channels according to the event type.

- [0295-brightdata-screenshot.json](workflows/0295-brightdata-screenshot.json)
  Description: This automated flow allows capturing a web screen using Bright Data Web Unlocker and saving it to a local file.

- [0296-calendario-eventos.json](workflows/0296-calendario-eventos.json)
  Description: This automated flow allows adding events to the Gmail calendar specified manually when starting an execution.

- [0297-imagen-texto-automatico.json](workflows/0297-imagen-texto-automatico.json)
  Description: This automated flow allows downloading an image from the internet and adding text to it.

- [0298-cheems-discord.json](workflows/0298-cheems-discord.json)
  Description: This automated flow sends humorous reminders on Discord every Friday and Thursday morning at 9 AM, plus messages every 30 minutes also using the same webhook.

- [0299-airtable-mailchimp-sync.json](workflows/0299-airtable-mailchimp-sync.json)
  Description: This automated flow synchronizes entries from the Users table in Airtable with a specific Mailchimp list, converting the Email field into a subscriber and using Name as the value for the FNAME field.

- [0300-nextcloud-deck-email.json](workflows/0300-nextcloud-deck-email.json)
  Description: This automated flow reads emails via IMAP, cleans their content, and creates cards in Nextcloud Deck.

- [0301-telegram-journal-reminder.json](workflows/0301-telegram-journal-reminder.json)
  Description: This automated flow sends a Telegram reminder every morning to reflect on the activities performed the previous day.

- [0302-zoom-from-google-calendar.json](workflows/0302-zoom-from-google-calendar.json)
  Description: This automated flow creates Zoom meetings based on filtered events from Google Calendar.

- [0303-google-sheets-sync.json](workflows/0303-google-sheets-sync.json)
  Description: This automated flow reads data from a Google spreadsheet and periodically synchronizes it with the Mailchimp subscriber list.

- [0304-email-xml-to-http-post.json](workflows/0304-email-xml-to-http-post.json)
  Description: This automated flow extracts an email from IMAP, processes the XML content in the first attachment, and sends the data via an HTTP POST request to an API.

- [0305-certificate-email-batch.json](workflows/0305-certificate-email-batch.json)
  Description: This automated flow reads a CSV file, splits it into batches, and uses its content to send emails with previously generated certificates.

- [0306-twake-message-trigger.json](workflows/0306-twake-message-trigger.json)
  Description: This automated flow is manually triggered and sends an empty message to Twake without specifying content or channel.

- [0307-send-sms-from-airtable.json](workflows/0307-send-sms-from-airtable.json)
  Description: This automated flow allows sending SMS using Twilio to numbers and names stored in Airtable.

- [0308-typeform-whatsapp-message.json](workflows/0308-typeform-whatsapp-message.json)
  Description: This automated flow allows receiving new Typeform responses and sending them formatted to WhatsApp using Twilio.

- [0309-twitter-mentions-rocketchat.json](workflows/0309-twitter-mentions-rocketchat.json)
  Description: This flow checks Twitter every minute for mentions of '@n8n_io' and, if new, sends a message to RocketChat with the tweet text and its URL.

- [0310-twitter-monitor.json](workflows/0310-twitter-monitor.json)
  Description: This flow monitors recent mentions of 'n8n_io' on Twitter and posts them to a Mattermost channel.

- [0311-website-stock-alert.json](workflows/0311-website-stock-alert.json)
  Description: This flow periodically checks the content of an HTTP response to determine if it contains 'Out Of Stock', sending notifications on Discord according to the results.

- [0312-wordpress-csv-export.json](workflows/0312-wordpress-csv-export.json)
  Description: This automated flow extracts and exports all WordPress articles to a CSV file.

- [0313-insertar-productos-desde-excel.json](workflows/0313-insertar-productos-desde-excel.json)
  Description: This flow reads an Excel file (.xls), interprets it, and then inserts each row of this file into the 'product' table of a PostgreSQL database.

- [0314-bill-bot.json](workflows/0314-bill-bot.json)
  Description: This automated flow processes invoices received via WhatsApp or Telegram, analyzes details with the Mindee API, stores information in Google Sheets, and sends an SMS notification.

- [0315-icypeas-email-verifier.json](workflows/0315-icypeas-email-verifier.json)
  Description: This automated flow processes lists of emails in batches from a Google sheet, using API credentials for authentication and making HTTP POST requests to the Icypeas platform.

- [0316-icypeas-email-search.json](workflows/0316-icypeas-email-search.json)
  Description: This flow processes real-time search results from Icypeas and stores the email, first name, and last name.

- [0317-phantom-airtable-store.json](workflows/0317-phantom-airtable-store.json)
  Description: This flow allows executing a Phantom Buster operation and storing the structured result in Airtable using the 'append' option.

- [0318-line-chatbot-memory.json](workflows/0318-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using memory and custom tools.

- [0319-fastmail-mailbox-email.json](workflows/0319-fastmail-mailbox-email.json)
  Description: This automated flow gets and processes mailbox and email information from Fastmail's JMAP API.

- [0320-dingtalk-tfs-automation.json](workflows/0320-dingtalk-tfs-automation.json)
  Description: This automated flow sends a DingTalk notification when a new Pull Request is created in Azure DevOps, using MySQL database maps to translate user accounts.

- [0321-airtable-image-automation.json](workflows/0321-airtable-image-automation.json)
  Description: This automated flow searches and updates records in Airtable to add images via URL.

- [0322-notion-bookmark-tracker.json](workflows/0322-notion-bookmark-tracker.json)
  Description: This automated flow receives URLs via a POST webhook and creates them as new pages in a specified Notion database.

- [0323-crm_lead_automation.json](workflows/0323-crm_lead_automation.json)
  Description: This automated flow detects email responses to marketing campaigns, evaluates prospect interest using artificial intelligence, and if interested, creates a new deal in Pipedrive.

- [0324-google-drive-file-share.json](workflows/0324-google-drive-file-share.json)
  Description: This n8n flow allows getting and sharing Google Drive files in public mode via manual execution.

- [0325-binance_telegram_price_alert.json](workflows/0325-binance_telegram_price_alert.json)
  Description: This automated flow monitors price changes on Binance and sends formatted alerts via Telegram when a cryptocurrency experiences a change greater than or equal to 15% (different from the initial mention) in the last 24 hours.

- [0326-spotify-discover-weekly-archiver.json](workflows/0326-spotify-discover-weekly-archiver.json)
  Description: This automated flow archives tracks from the 'Discover Weekly' playlist on Spotify by comparing and adding only songs that are not already present.

- [0327-tron_wallet_monitor.json](workflows/0327-tron_wallet_monitor.json)
  Description: This automated flow queries and processes recent transactions in a TRC20 wallet, displaying formatted information about received tokens.

- [0328-analytics-airtable.json](workflows/0328-analytics-airtable.json)
  Description: This automated flow gets historical web analytics data and stores it in an Airtable table.

- [0329-blog-medium-publisher.json](workflows/0329-blog-medium-publisher.json)
  Description: This automated flow extracts content from WordPress blogs to publish on Medium using HTML and HTTP requests.

- [0330-monday-error-tracking.json](workflows/0330-monday-error-tracking.json)
  Description: This automated flow detects when an error occurs during execution processing, captures its stack trace and message, and then automatically updates an item in Monday.com with this information.

- [0331-eleven-openai-audio-translation.json](workflows/0331-eleven-openai-audio-translation.json)
  Description: This flow executes a process of converting and transcribing French text to speech and then to English.

- [0332-strava-beeminder-datapoint-flow.json](workflows/0332-strava-beeminder-datapoint-flow.json)
  Description: This flow adds a data point in Beeminder when a new activity is created in Strava.

- [0333-bored-api-activity-tool.json](workflows/0333-bored-api-activity-tool.json)
  Description: This flow allows an AI agent to call a subflow to extract information about type and number of participants, then use that information to filter activities via the Bored API and return the combined result in a chatbot response.

- [0334-line-chatbot-memory.json](workflows/0334-line-chatbot-memory.json)
  Description: This automated flow processes chat messages in LINE using contextualized memory to maintain a significant history and calls the specified assistant to generate responses.

- [0335-sendgrid-contact-flow.json](workflows/0335-sendgrid-contact-flow.json)
  Description: This flow allows creating, updating, and getting contact information in SendGrid via the SendGrid node.

- [0336-google-contacts-test.json](workflows/0336-google-contacts-test.json)
  Description: This automated flow allows creating a contact in Google Contacts with n8n's data and then updating and immediately getting that same contact.

- [0337-empresa-noticias-automatizacion.json](workflows/0337-empresa-noticias-automatizacion.json)
  Description: This automated flow seeks to keep informed about the latest news of companies related to each scheduled meeting in the daily calendar, sending a summary by email at the agreed time.

- [0338-hubspot-exact-enrichment.json](workflows/0338-hubspot-exact-enrichment.json)
  Description: This automated flow allows n8n to automatically enrich contact profiles in HubSpot with additional information obtained from the ExactBuyer API.

- [0339-hubspot-engagement-automation.json](workflows/0339-hubspot-engagement-automation.json)
  Description: This automated flow sends follow-up emails to uncontacted contacts in HubSpot using Gmail and logs the engagement.

- [0340-telegram-ai-bot.json](workflows/0340-telegram-ai-bot.json)
  Description: This automated flow allows a Telegram bot to maintain a conversation using the OpenAI GPT-4o-mini model, sending responses with emojis.

- [0341-hubspot-seguimiento-email.json](workflows/0341-hubspot-seguimiento-email.json)
  Description: This automated flow searches for contacts in HubSpot that have been previously contacted and have only had one engagement, to send them a polite follow-up email.

- [0342-lead-verification-madkudu-slack.json](workflows/0342-lead-verification-madkudu-slack.json)
  Description: This automated flow verifies and qualifies leads using Hunter and integrates with MadKudu to send Slack notifications when customer fit exceeds a threshold.

- [0343-validacion-email-madkudu-n8n.json](workflows/0343-validacion-email-madkudu-n8n.json)
  Description: This automated flow validates emails with Hunter and scores leads with MadKudu via a webhook form, sending email alerts only if the score is greater than 60.

- [0344-form-contacto-telegram.json](workflows/0344-form-contacto-telegram.json)
  Description: This automated flow collects emails via a contact form, verifies their validity using Hunter API, and if valid, calculates the customer fit score via MadKudu. The results are sent to Telegram for quick follow-up.

- [0345-google-indexing-sitemap.json](workflows/0345-google-indexing-sitemap.json)
  Description: This automated flow extracts URLs from an XML sitemap and sends them in batches to the Google Indexing API to notify about updates.

- [0346-lead-alertas-n8n.json](workflows/0346-lead-alertas-n8n.json)
  Description: This automated flow monitors new hot companies in HubSpot and sends alerts to a specific user in Slack every 5 minutes.

- [0347-euro-exchange-rate-processor.json](workflows/0347-euro-exchange-rate-processor.json)
  Description: This automated flow gets and processes real-time euro exchange rates via an HTTP request to the European Central Reserve API.

- [0348-mail-api-scraper.json](workflows/0348-mail-api-scraper.json)
  Description: This flow allows extracting email addresses from any website via an HTTP request to a webhook.

- [0349-stoic-twitter-bot.json](workflows/0349-stoic-twitter-bot.json)
  Description: This automated flow allows creating and publishing viral tweets with a personal style about modern stoicism, scheduled randomly every 6 hours.

- [0350-slack-idea-capture.json](workflows/0350-slack-idea-capture.json)
  Description: This automated flow allows a user to send a travel request (slash command) '/idea' in Slack to automatically create a database page in Notion and request additional details.

- [0351-slack-feature-ideas.json](workflows/0351-slack-feature-ideas.json)
  Description: This automated flow allows receiving ideas via Slack commands and adding them to a Google sheet with a link to add details.

- [0352-rss-monitor.json](workflows/0352-rss-monitor.json)
  Description: This flow periodically reviews (every hour) multiple specific RSS feeds, checks if articles were published in the last hour cycle, and sends emails with the news.

- [0353-gmail-archivar.json](workflows/0353-gmail-archivar.json)
  Description: This automated flow archives email messages and threads in the inbox that are not marked as favorites (starred) since the last execution, leaving only the starred ones.

- [0354-todoist-recurring-tasks.json](workflows/0354-todoist-recurring-tasks.json)
  Description: This n8n flow processes tasks from a Todoist project to create new tasks in the inbox daily, based on parameters like specific days and hours. It analyzes task descriptions, checks if they match the current day, generates new tasks, and deletes those that already exist.

- [0355-slack-error-notification.json](workflows/0355-slack-error-notification.json)
  Description: This automated flow sends a Slack notification when a workflow fails, reporting the workflow name and execution URL.

- [0356-sync-n8n-notion.json](workflows/0356-sync-n8n-notion.json)
  Description: This flow automatically synchronizes n8n workflows with the Notion system every 15 minutes.

- [0357-auto-seo-keywords-generator.json](workflows/0357-auto-seo-keywords-generator.json)
  Description: This automated flow receives a query via Webhook, generates related keywords using the Google Suggest API, and formats them for use in SEO research.

- [0358-telegram-error-notification.json](workflows/0358-telegram-error-notification.json)
  Description: This automated flow sends a Telegram notification when an error occurs in another workflow or process.

- [0359-crea_actualiza_y_consulta_usuario_gsuite.json](workflows/0359-crea_actualiza_y_consulta_usuario_gsuite.json)
  Description: This flow creates a user in Google Workspace using the admin node and then updates and gets it to confirm changes.

- [0360-gmail-error-alert.json](workflows/0360-gmail-error-alert.json)
  Description: This automated flow detects errors in other job executions and sends a detailed email to the user via the configured Gmail account.

- [0361-workflow-error-config.json](workflows/0361-workflow-error-config.json)
  Description: This flow updates the error handling configuration in workflows via Postgres and uses predefined variables to exclude certain cases.

- [0362-country-query-formatter.json](workflows/0362-country-query-formatter.json)
  Description: This automated flow queries country data via GraphQL using a code as a parameter, then extracts the country object and converts it into formatted text to be sent via a URL.

- [0363-highlevel-address-verification.json](workflows/0363-highlevel-address-verification.json)
  Description: This automated flow verifies the postal address of new contacts in HighLevel via a verification API and adds a tag depending on whether it is valid or not.

- [0364-documentacion-n8n-automatica.json](workflows/0364-documentacion-n8n-automatica.json)
  Description: This automated flow allows users to generate documentation for their n8n workflows using the OpenAI API.

- [0365-reporte-fallas-telegram.json](workflows/0365-reporte-fallas-telegram.json)
  Description: This flow reviews failed executions of a task in the last week and sends a summary via Telegram.

- [0366-slack-to-clickup-tasks.json](workflows/0366-slack-to-clickup-tasks.json)
  Description: This flow analyzes a JSON file

- [0367-tweets-publicador.json](workflows/0367-tweets-publicador.json)
  Description: This automated flow extracts and publishes the latest Tweets stored in a Google sheet named 'Tweets' every 6 hours.

- [0368-youtube-upload-create-playlist.json](workflows/0368-youtube-upload-create-playlist.json)
  Description: This automated flow allows uploading a video to YouTube and creating a playlist, adding the ID of the newly uploaded video.

- [0369-youtube-description-automation.json](workflows/0369-youtube-description-automation.json)
  Description: This automated flow allows adding a predefined text to the description of all your YouTube videos while maintaining the existing original content and checking if updates are necessary.

- [0370-flujo-confirmacion-transferencia.json](workflows/0370-flujo-confirmacion-transferencia.json)
  Description: This automated flow checks if a record already exists in Grist before creating a new one based on a webhook input with a 'Confirmed' field to ensure the operation is only performed when necessary.

- [0371-telegram-chatbot-ai.json](workflows/0371-telegram-chatbot-ai.json)
  Description: This automated flow allows a Telegram chatbot to generate intelligent responses based on received messages and send those responses along with AI-generated images.

- [0372-xml-to-json-converter.json](workflows/0372-xml-to-json-converter.json)
  Description: This flow allows converting XML files to JSON, has multiple connections, and handles errors with custom HTTP responses.

- [0373-nasa-api-credentials.json](workflows/0373-nasa-api-credentials.json)
  Description: This flow uses a form to dynamically enter the NASA API key, which is then used in the NASA connection node via expressions.

- [0374-crm-address-verification.json](workflows/0374-crm-address-verification.json)
  Description: This flow verifies the validity of the postal address of new contacts imported from Groundhogg CRM using the Lob API. If the result indicates it is deliverable, it adds a tag and updates the contact; if not, it adds another tag and triggers manual or automated actions.

- [0375-email-validation-domain-extraction.json](workflows/0375-email-validation-domain-extraction.json)
  Description: This flow tests email address validation and extracts the domain using n8n's native functions.

- [0376-unsubscribe-mautic.json](workflows/0376-unsubscribe-mautic.json)
  Description: This automated flow allows users to unsubscribe from marketing emails by replying to a specific message in Gmail, integrating with Mautic CRM to manage their data.

- [0377-google_slides_image_replacer.json](workflows/0377-google_slides_image_replacer.json)
  Description: This automated flow allows replacing images in Google Slides presentations via a POST request with parameters like presentation_id, image_key, and image_url.

- [0378-elevenlabs-text-to-speech.json](workflows/0378-elevenlabs-text-to-speech.json)
  Description: This flow verifies input parameters and uses the ElevenLabs API to generate voice responses from the provided text.

- [0379-Keap-Lob-Address-Verification.json](workflows/0379-Keap-Lob-Address-Verification.json)
  Description: This automated flow verifies the postal address of a contact in Keap using Lob via an API, and automatically updates fields or applies tags depending on whether it is deliverable or not.

- [0380-hacker-news-monitor.json](workflows/0380-hacker-news-monitor.json)
  Description: This flow checks every day at 1:00 PM if there are featured 'Show HN' articles on the Hacker News homepage and sends an email with the most recent ones.

- [0381-airtable-seo-metatags.json](workflows/0381-airtable-seo-metatags.json)
  Description: This automated flow searches Airtable for records that do not have a URL or title/metadata description defined and updates those fields with real values extracted from web content.

- [0382-webhook-google-sheets.json](workflows/0382-webhook-google-sheets.json)
  Description: This flow reads data from a specific Google Sheets spreadsheet when a request is received via the webhook.

- [0383-workflow-estado.json](workflows/0383-workflow-estado.json)
  Description: This automated flow executes a main workflow with trigger intervals and checks in Redis if the workflow is currently running to avoid multiple concurrent instances.

- [0384-api-flutterflow-data.json](workflows/0384-api-flutterflow-data.json)
  Description: This n8n flow is used to create an API in FlutterFlow that receives data from a data store (like 'Customer Datastore') and inserts it into a variable before returning it as JSON to the application.

- [0385-convertapi-docx2pdf.json](workflows/0385-convertapi-docx2pdf.json)
  Description: This automated flow downloads a DOCX file from a URL and converts it to PDF using ConvertAPI credentials, then writes it to the file system.

- [0386-ejecuciones_workflow.csv](workflows/0386-ejecuciones_workflow.csv)
  Description: This flow allows getting all workflow execution records and converting them into a CSV file.

- [0387-convertir-docx-a-pdf.json](workflows/0387-convertir-docx-a-pdf.json)
  Description: This automated flow allows converting DOCX files linked from a remote URL to PDF format using ConvertAPI.

- [0388-scrappey-test-schedule.json](workflows/0388-scrappey-test-schedule.json)
  Description: This automated flow schedules a test process at certain intervals to extract data via the Scrappey API.

- [0389-chat-movie-recommendations.json](workflows/0389-chat-movie-recommendations.json)
  Description: This flow allows a conversational AI to interact with MongoDB data via aggregations, maintain context in buffer memory, and log user preferences.

- [0390-convertapi-xlsx-to-pdf-test.json](workflows/0390-convertapi-xlsx-to-pdf-test.json)
  Description: This automated flow allows testing the conversion of XLSX files to PDF using a public API.

- [0391-convertir-pptx-a-json.json](workflows/0391-convertir-pptx-a-json.json)
  Description: This automated flow downloads a demo PPTX file, converts it to PDF using authenticated ConvertAPI, and saves the result as 'document.pdf' on the local system.

- [0392-proteccion-pdf-google.json](workflows/0392-proteccion-pdf-google.json)
  Description: This flow automatically downloads a demo PDF and writes it to disk or uploads it to Google Drive.

- [0393-2310_webpage-to-pdf_test.json](workflows/0393-2310_webpage-to-pdf_test.json)
  Description: This test flow converts the webpage https://n8n.io into a PDF file and saves it as document.pdf.

- [0394-manejador-errores.json](workflows/0394-manejador-errores.json)
  Description: This flow checks if a workflow is active and does not have an error handler configured. If so, it updates its settings by assigning the default error handler ID via an API call.

- [0395-html-to-pdf-automation.json](workflows/0395-html-to-pdf-automation.json)
  Description: This automated flow converts HTML documents to PDF using ConvertAPI.

- [0396-convertapi-jpg-to-pdf.json](workflows/0396-convertapi-jpg-to-pdf.json)
  Description: This automated flow downloads a demo image and converts the JPG file to PDF format using the ConvertAPI.

- [0397-convertapi-pdf-conversion.json](workflows/0397-convertapi-pdf-conversion.json)
  Description: This automated flow downloads a demo file, converts it to PDFA format using the ConvertAPI, and writes the result to a PDFA file.

- [0398-agente-ia-herramientas.json](workflows/0398-agente-ia-herramientas.json)
  Description: This demonstrative flow allows an AI agent to interact with web tools and APIs to provide activities or information via messages.

- [0399-workflow-credentials-agent.json](workflows/0399-workflow-credentials-agent.json)
  Description: This flow allows storing n8n configurations in a SQLite database and querying them via a conversational agent.

- [0400-gmail-attachment-upload.json](workflows/0400-gmail-attachment-upload.json)
  Description: This flow detects new emails in Gmail with attachments, extracts each file individually, and uploads it to the root folder of Google Drive.

- [0401-line-chatbot-memory-automation.json](workflows/0401-line-chatbot-memory-automation.json)
  Description: This automated flow extracts data from specific Webhook nodes in an execution and passes it to the processing node.

- [0402-github-release-monitor.json](workflows/0402-github-release-monitor.json)
  Description: This flow checks the latest releases of selected GitHub repositories daily and sends a Slack notification if a new version is available.

- [0403-stripe-checkout-filters.json](workflows/0403-stripe-checkout-filters.json)
  Description: This automated flow retrieves all Stripe checkout sessions from the last month and allows filtering them based on custom fields like nickname or job_title.

- [0404-systeme-io-contact-flow.json](workflows/0404-systeme-io-contact-flow.json)
  Description: This automated flow collects all contacts and tags from Systeme.io using pagination to handle API limitations.

- [0406-zigbee-backups-schedule.json](workflows/0406-zigbee-backups-schedule.json)
  Description: This automated flow performs weekly backups (every Monday at 2:45 am) via MQTT messages, decodes the JSON response to get the ZIP file, and automatically uploads it to an SFTP server.

- [0407-n8n-totp-authentication.json](workflows/0407-n8n-totp-authentication.json)
  Description: This flow verifies the validity of an entered TOTP code using the provided secret.

- [0408-confluence-template-automation.json](workflows/0408-confluence-template-automation.json)
  Description: This flow automates the creation of a page in Confluence from a predefined template. The base URL and template ID parameters are fixed, while the target space and parent relationships are configured via a set node.

- [0409-todoist-categorizador.json](workflows/0409-todoist-categorizador.json)
  Description: This automated flow takes tasks from the Todoist inbox, discards subtasks, and uses AI to assign them to specific projects based on predefined priorities or tags them as 'other'.

- [0411-backup-n8n-workflows.json](workflows/0411-backup-n8n-workflows.json)
  Description: This automated flow performs backups of n8n workflows to a Bitbucket repository, thus avoiding exceeding rate limits.

- [0412-zendesk-unassigned-tickets-to-slack.json](workflows/0412-zendesk-unassigned-tickets-to-slack.json)
  Description: This automated flow queries unassigned and pending Zendesk tickets, formats their information, and sends a summary message to a specific Slack channel.

- [0413-analisis-multimodal-cv.json](workflows/0413-analisis-multimodal-cv.json)
  Description: This flow analyzes PDF resumes using visual models to detect 'bypass' with hidden prompts, thus preventing candidates from trying to trick the system.

- [0414-passport-photo-validator.json](workflows/0414-passport-photo-validator.json)
  Description: This automated flow verifies the validity of passport photos according to British government criteria using an AI model.


- [0416-zotero-pagination-bibliography.json](workflows/0416-zotero-pagination-bibliography.json)
  Description: This automated flow allows downloading collections and items (articles) from the Zotero API via a loop that handles pagination.

- [0417-image-composite-overlay.json](workflows/0417-image-composite-overlay.json)
  Description: This automated flow allows composing two images, overlaying one on top of the other in the center of the base image.

- [0418-fastmail-masked-email-generator.json](workflows/0418-fastmail-masked-email-generator.json)
  Description: This automated flow allows creating masked email addresses using the Fastmail API. It is initiated by a POST request to a webhook, which processes and generates the requested addresses with the necessary parameters.

- [0419-google-ads-keyword-data.json](workflows/0419-google-ads-keyword-data.json)
  Description: This workflow uses the Google Ads API to get historical data and search volumes for up to 20 keywords.

- [0420-xero-webhook-verifier.json](workflows/0420-xero-webhook-verifier.json)
  Description: This flow verifies the authenticity of incoming Xero webhooks by calculating and comparing the HMAC hash using SHA-256 to ensure integrity and security.

- [0421-alertas-azure-task.json](workflows/0421-alertas-azure-task.json)
  Description: This automated flow periodically checks Elasticsearch for the number of alerts, and if it exceeds a specific threshold (likely 0), it automatically creates an incident in Azure DevOps.

- [0422-image-processing-flow.json](workflows/0422-image-processing-flow.json)
  Description: This flow processes images uploaded to ImgBB, optimizes them with ReSmush.it, and stores the optimized version in ImgBB.

- [0423-spotify-youtube-sync.json](workflows/0423-spotify-youtube-sync.json)
  Description: This flow synchronizes songs between YouTube and Spotify playlists by adding only new ones without duplicates.

- [0424-prism-elastic-alert-email.json](workflows/0424-prism-elastic-alert-email.json)
  Description: This automated flow periodically checks security alerts in an Elastic system and sends emails notifying about detected incidents.

- [0425-n8n-flujos-backup-github.json](workflows/0425-n8n-flujos-backup-github.json)
  Description: This automated flow backs up n8n workflows to a git repository by checking changes and updating files.

- [0426-token-management.json](workflows/0426-token-management.json)
  Description: This flow uses persistent static variables to manage an access token that expires after 1 minute. When the token expires (due to verification in 'if token is valid'), a new one is requested via HTTP and updates the static data.

- [0427-zoom-wordpress-schedule.json](workflows/0427-zoom-wordpress-schedule.json)
  Description: This automated flow schedules a new Zoom meeting every 360 days and updates a WordPress post with its URL.

- [0428-libros-historicos-extractor.json](workflows/0428-libros-historicos-extractor.json)
  Description: This flow extracts information about historical books from Toscrape using Jina.ai and uses the OpenAI ChatGPT model to analyze the data, finally saving the results in a Google sheet.

- [0429-webflow-to-gsheets.json](workflows/0429-webflow-to-gsheets.json)
  Description: This automated flow collects data from form submissions in Webflow and automatically adds them as new rows to a Google spreadsheet.

- [0430-calvin-hobbes-discord-daily-comic.json](workflows/0430-calvin-hobbes-discord-daily-comic.json)
  Description: This automated flow publishes Calvin and Hobbes comic strips on Discord, with Korean translations alongside the original dialogues.

- [0431-blue-sky-rss.json](workflows/0431-blue-sky-rss.json)
  Description: This flow automates the publication of RSS articles converted into BlueSky multimedia posts.

- [0432-meal-plan-generator.json](workflows/0432-meal-plan-generator.json)
  Description: This automated flow generates a random meal plan based on specific recipes for future days and sends it to the Mealie API.

- [0433-github-release-monitor.json](workflows/0433-github-release-monitor.json)
  Description: This automated flow checks the latest n8n releases on GitHub daily, converts any markdown content to HTML, and sends an email notifying if a new version is available.

- [0434-convertkit-list-subscribe-tag.json](workflows/0434-convertkit-list-subscribe-tag.json)
  Description: This manual flow allows adding a subscriber to a ConvertKit list specifically identified by its ID, creating an associated tag, and adding the same existing subscriber in that list to the new tag.

- [0435-openai-supabase-sql-chat.json](workflows/0435-openai-supabase-sql-chat.json)
  Description: This flow allows a user to interact conversationally with a PostgreSQL database on Supabase using OpenAI functions to execute queries and generate responses.

- [0436-cleaner-old-executions.json](workflows/0436-cleaner-old-executions.json)
  Description: This n8n flow checks for old executions and deletes them if they are older than 10 days.

- [0437-youtube-transcript-summary.json](workflows/0437-youtube-transcript-summary.json)
  Description: This flow allows extracting a YouTube video ID from its URL using a regular expression, getting its main data like title and description, concatenating transcripts if available, and sending a formatted message with the summary via Telegram.

- [0438-twitch-stream-checker.json](workflows/0438-twitch-stream-checker.json)
  Description: This flow checks if a specific Twitch user is live streaming by querying their GraphQL API.

- [0439-hn-lookback-bot.json](workflows/0439-hn-lookback-bot.json)
  Description: This automated flow allows reviewing top Hacker News stories from the current day and previous days across multiple years, analyzing them with an LLM model to categorize them into themes using Google Gemini, and sending the formatted summary in Markdown via Telegram.

- [0440-jira_telegram_webhook.json](workflows/0440-jira_telegram_webhook.json)
  Description: This flow sends updates via Telegram according to the type of event in Jira (creation, change, or assignment).

- [0441-youtube-video-summarizer.json](workflows/0441-youtube-video-summarizer.json)
  Description: This automated flow allows getting a YouTube video transcript and generating its summary using language models.

- [0442-transform-image-to-lego-line.json](workflows/0442-transform-image-to-lego-line.json)
  Description: This automated flow allows receiving an image via a LINE webhook, analyzing it with GPT-4O-MINI to create the appropriate prompt in DALL-E 3, generating the allegorized image as if it were made of LEGO, and finally sending this new image to the user via Line.

- [0443-comparativo-llm-pdf.json](workflows/0443-comparativo-llm-pdf.json)
  Description: This automated flow allows testing and comparing the ability of Gemini 2.0 Flash and Claude 3.5 Sonnet models to extract information directly from PDFs using predefined credentials.

- [0444-google-drive-pii-detector.json](workflows/0444-google-drive-pii-detector.json)
  Description: This automated flow detects the creation of new CSV files in Google Drive, identifies columns containing personal data (PII) using OpenAI, deletes those columns, and re-uploads the processed file.

- [0445-sentry-release-flow.json](workflows/0445-sentry-release-flow.json)
  Description: This automated flow allows creating a new version of a project in Sentry and then getting all existing versions.

- [0446-telegram-welcome-bidirectional.json](workflows/0446-telegram-welcome-bidirectional.json)
  Description: This automated flow allows a Telegram bot to send personalized greetings in Spanish when someone joins or leaves a chat, using webhooks.

- [0447-perplexity-ai-chat.json](workflows/0447-perplexity-ai-chat.json)
  Description: This automated flow sends a request to the Perplexity AI API using the provided key, including parameters like prompt and domains for filtering.

- [0448-upwork-jobs-sync.json](workflows/0448-upwork-jobs-sync.json)
  Description: This flow queries recent Upwork jobs using Apify and MongoDB. If the hours are between 2-15, it checks if similar entries already exist by title and budget before inserting them.

- [0449-rankmath-update-product.json](workflows/0449-rankmath-update-product.json)
  Description: This automated flow runs when the user clicks 'Test flow' and updates the SEO metadata of a specific product using the Rank Math plugin API.

- [0450-gitlab-merge-request-flow.json](workflows/0450-gitlab-merge-request-flow.json)
  Description: This automated flow checks if an open merge request with the same branch name exists and, if so, closes it; if it does not exist, it creates a new one.

- [0451-backups-workflow-google.json](workflows/0451-backups-workflow-google.json)
  Description: This automated flow performs periodic workflow backups to Google Drive every 4 hours and deletes the original files to keep storage optimized.

- [0452-wordpress-posts-csv.json](workflows/0452-wordpress-posts-csv.json)
  Description: This automated flow allows getting published WordPress posts in JSON format and subsequently converting them into a CSV file to automatically upload to Google Drive.

- [0453-convertkit-form-subscribe.json](workflows/0453-convertkit-form-subscribe.json)
  Description: This workflow monitors when a new subscriber is added via the specific form number 165198 in ConvertKit.

- [0454-vps-upgrade-email-checker.json](workflows/0454-vps-upgrade-email-checker.json)
  Description: This automated flow daily executes the 'apt list --upgradable' command via SSH on a remote machine and sends an HTML formatted email if there are upgradable packages.

- [0456-keywords-analysis.json](workflows/0456-keywords-analysis.json)
  Description: This automated flow processes keywords from a Google sheet, analyzes them to determine if they contain IT software names using an AI agent, and updates the sheet with the results.

- [0457-vps-resource-monitor.json](workflows/0457-vps-resource-monitor.json)
  Description: This flow checks CPU, RAM, and disk usage on a VPS every 15 minutes via three SSH nodes executed at intervals. If any resource exceeds the 80% threshold, it sends an email with detailed information.

- [0458-google-drive-batch-upload.json](workflows/0458-google-drive-batch-upload.json)
  Description: This automated flow allows uploading multiple files to Google Drive in an organized way via a form that automatically verifies and creates the destination folder.

- [0459-imagen-gen-config.json](workflows/0459-imagen-gen-config.json)
  Description: This n8n flow allows generating custom images from parameters defined in the Set Image Properties nodes.

- [0461-milvus-rag-chatbot-flow.json](workflows/0461-milvus-rag-chatbot-flow.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using PDF documents inserted into Milvus and RAG queries with Cohere embeddings.

- [0462-n8n-blueprint-backoff.json](workflows/0462-n8n-blueprint-backoff.json)
  Description: This flow implements an exponential backoff mechanism to handle rate limiting in the Google Sheets API, retrying an action with exponential time increments between attempts up to a maximum of 5 retries.

- [0463-add-task-google.json](workflows/0463-add-task-google.json)
  Description: This manual flow allows adding a specific Google Tasks task by clicking and executing the corresponding node.

- [0464-telegram-affirmations-daily.json](workflows/0464-telegram-affirmations-daily.json)
  Description: This automated flow executes a script every day at 9 AM to get and send a daily affirmation message via the affirmations.dev API.

- [0465-discord-webhook-message.json](workflows/0465-discord-webhook-message.json)
  Description: This automated flow allows sending a 'Hello World!' message to a Discord channel using webhooks.

- [0466-mattermost-rss-monitor.json](workflows/0466-mattermost-rss-monitor.json)
  Description: This automated flow publishes each new article from an RSS feed to the corresponding Mattermost channel, using Mastodon as an intermediary for verification.

- [0467-signl4-event-processing.json](workflows/0467-signl4-event-processing.json)
  Description: This automated flow processes pending events from the SIG SIGNL4 system every hour, reading previous data stored in a binary file and checking if they have already been resolved to send the corresponding alerts.

- [0468-syncro-clockify-tasks.json](workflows/0468-syncro-clockify-tasks.json)
  Description: This automated flow receives data via webhook and uses it to create tasks in Clockify.

- [0469-telegram-meteogram.json](workflows/0469-telegram-meteogram.json)
  Description: This automated flow allows receiving messages on Telegram about the weather and sending back a report with the current weather description, real temperature, and wind chill for the specified city.

- [0470-postgres-excel-generator.json](workflows/0470-postgres-excel-generator.json)
  Description: This flow executes a query in PostgreSQL to get product names and EAN codes, converts the result into an Excel file, and writes it.

- [0471-line-chatbot-ssh.json](workflows/0471-line-chatbot-ssh.json)
  Description: This automated flow allows a LINE chatbot to interactively request help on SSH commands and execute them on a VPS, using tools like ReAct Agent and the n8n-nodes-base extension.

- [0472-workflow-wordpress-tts.json](workflows/0472-workflow-wordpress-tts.json)
  Description: This automated flow allows getting a WordPress article, generating its summary or transcription with an AI, and converting it to audio to be inserted as multimedia content in the same post.

- [0473-line-chatbot-memory.json](workflows/0473-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation with users by storing and retrieving states.

- [0474-update-youtube-descriptions.json](workflows/0474-update-youtube-descriptions.json)
  Description: This automated flow allows inserting a specific text between two determined lines in the descriptions of all YouTube videos. It first collects all videos, then for each one, it gets its ID and searches for the text to insert based on previously defined variables.

- [0475-nocodebot-multilang.json](workflows/0475-nocodebot-multilang.json)
  Description: This automated flow allows a Telegram chatbot to maintain a contextualized conversation about open-source tools (No-Code) by integrating with a Strapi database.

- [0476-mailerlite-airtable-sync.json](workflows/0476-mailerlite-airtable-sync.json)
  Description: This flow detects when a subscriber is added to a group in MailerLite and automatically saves their name and email in an Airtable table.

- [0477-n8n-workflow-backup-schedule.json](workflows/0477-n8n-workflow-backup-schedule.json)
  Description: This automated flow performs daily backups at 1:30 AM of all n8n workflows into a JSON file and saves it in a specified Google Drive folder.

- [0478-formulario-google-docs.json](workflows/0478-formulario-google-docs.json)
  Description: This automated flow allows the user to send data through a form and have this data used to fill in text in a Google Docs document using the API.

- [0479-ideas-para-post.json](workflows/0479-ideas-para-post.json)
  Description: This automated flow reads ideas from a Google sheet, generates a post for the specified platform using OpenAI, and if it's Twitter, publishes it. It then updates the sheet with the post text.

- [0480-calendar-voice-reminder.json](workflows/0480-calendar-voice-reminder.json)
  Description: This automated flow searches for upcoming appointments and generates synthesized voice reminders to send to attendees.

- [0481-shopify-orders-sync.json](workflows/0481-shopify-orders-sync.json)
  Description: This automated flow gets Shopify orders via API and stores them in Google Sheets.

- [0482-invitaciones-google-sheets-n8n.json](workflows/0482-invitaciones-google-sheets-n8n.json)
  Description: This automated flow compares users in n8n with data from a Google Sheets spreadsheet to send invitations to those who do not exist on the platform.

- [0483-mailchimp-google-sheets-newsletter.json](workflows/0483-mailchimp-google-sheets-newsletter.json)
  Description: This automated flow processes new newsletter subscriptions in Google Sheets and adds them as active contacts in Mailchimp.

- [0484-merge-pdfs-from-urls.json](workflows/0484-merge-pdfs-from-urls.json)
  Description: This flow allows combining multiple PDFs from URLs into a single file using a custom JavaScript function.

- [0485-library-install.json](workflows/0485-library-install.json)
  Description: This automated flow allows installing Node.js libraries (specified as a comma-separated list) by executing npm commands.

- [0486-telegram-chinese-tutor.json](workflows/0486-telegram-chinese-tutor.json)
  Description: This automated flow allows a Telegram chatbot to efficiently practice the Chinese language through multiple-choice exercises, using memory to maintain conversation context.

- [0487-shopify-fulfillment-auto.json](workflows/0487-shopify-fulfillment-auto.json)
  Description: This automated flow searches to filter and obtain pending fulfillment orders in Shopify for digital downloads or gift cards.

- [0488-crear_cliente_segment.json](workflows/0488-crear_cliente_segment.json)
  Description: This automated flow creates a new customer in Customer.io with the custom property 'Name' configured and then immediately adds that customer to a specified segment.

- [0489-line-n8n-assistant.json](workflows/0489-line-n8n-assistant.json)
  Description: This flow implements an AI assistant in n8n that responds to LINE messages using GPT models and MCP tools.

- [0490-mediamarkt-deals.json](workflows/0490-mediamarkt-deals.json)
  Description: This automated flow processes and sends product offers classified by category via web scraping.

- [0491-ai-chat-agent-memory.json](workflows/0491-ai-chat-agent-memory.json)
  Description: This flow uses an AI agent with memory to maintain context during interaction and perform BigQuery queries on shipping data.

- [0492-notion-tasks-slack.json](workflows/0492-notion-tasks-slack.json)
  Description: This flow checks Notion To Dos every hour at 8 am, looks for tasks assigned to user 'NAME', and if any are pending, sends a direct notification on Slack to a specific user.

- [0493-proyectos-coste-missing.json](workflows/0493-proyectos-coste-missing.json)
  Description: This automated flow executes a weekly SQL query to get active external projects with missing budgeted cost and sends personalized emails to different cost center teams based on their names.

- [0494-monitor-alertas-postgres.json](workflows/0494-monitor-alertas-postgres.json)
  Description: This automated flow periodically checks records in the PostgreSQL database where the value is greater than 70 and has not been notified, then updates the status of said records to mark them as notified and informs via SMS using Twilio.

- [0495-gumroad-sale-trigger.json](workflows/0495-gumroad-sale-trigger.json)
  Description: This automated flow is triggered when a sale occurs on Gumroad.

- [0496-gmail-news-to-linkedin.json](workflows/0496-gmail-news-to-linkedin.json)
  Description: This automated flow allows a user to receive Gmail newsletters and use OpenAI to identify top news, summarize them, and generate LinkedIn posts with an intelligent style and subtle humor.

- [0497-incident-integracion.json](workflows/0497-incident-integracion.json)
  Description: This automated flow integrates incident monitoring with tracking in Jira, notifying the team via Mattermost channels.

- [0498-resume-screener.json](workflows/0498-resume-screener.json)
  Description: This n8n flow listens for new emails in Gmail with attachments, extracts text from the PDF, evaluates it using an AI agent based on LangChain and OpenAI, and logs structured results (name, email, LinkedIn, and score) in a Google sheet.

- [0499-tts-generation.json](workflows/0499-tts-generation.json)
  Description: This automated flow allows executing a Python script to generate MP3 audio files based on predefined text and voice.

- [0500-pagerduty-mattermost-update.json](workflows/0500-pagerduty-mattermost-update.json)
  Description: This automated flow allows a system to receive a notification via webhook containing the ID of an incident in PagerDuty. Once the information is received, it automatically updates the incident status to 'acknowledged' and sends a confirmation to the corresponding Mattermost channel.

- [0501-pager-duty-jira-integracion.json](workflows/0501-pager-duty-jira-integracion.json)
  Description: This automated flow updates the status of an incident in PagerDuty and its corresponding issue in Jira, then notifies Mattermost channels.

- [0502-chart-upload.json](workflows/0502-chart-upload.json)
  Description: This flow dynamically creates a line chart from JSON data and uploads it to Google Drive.

- [0503-error-alertas.json](workflows/0503-error-alertas.json)
  Description: This automated flow detects errors in jobs and sends notifications via both SMS and Mattermost.

- [0504-sharepoint-upload.json](workflows/0504-sharepoint-upload.json)
  Description: This automated flow uploads files to Microsoft SharePoint using Graph API.

- [0505-openai-image-generation-edit.json](workflows/0505-openai-image-generation-edit.json)
  Description: This workflow allows generating an initial image using the OpenAI API, converting it to binary format, and then editing it by adding elements like horns using the same API.

- [0506-facebook-lead-to-klicktipp.json](workflows/0506-facebook-lead-to-klicktipp.json)
  Description: This automated flow imports data from Facebook Lead Ads forms and synchronizes it in KlickTipp to start email campaigns.

- [0507-whatsapp-crm-automation.json](workflows/0507-whatsapp-crm-automation.json)
  Description: This automated flow collects data from WhatsApp via a webhook, saves it in a Google sheet, and adds the contact to the CRM with the tag 'New Lead'. Subsequently, it sends an email and a WhatsApp message to welcome the customer.

- [0508-google-autocomplete-letter.json](workflows/0508-google-autocomplete-letter.json)
  Description: This flow combines an initial keyword with all letters of the alphabet to get multiple Google autocompletions and returns the complete list.

- [0509-html-pdf-compress.json](workflows/0509-html-pdf-compress.json)
  Description: This automated flow allows converting an HTML block into a PDF file and compressing it, as well as processing a specific URL to generate another PDF from it.

- [0510-html-pdf-png-conversion.json](workflows/0510-html-pdf-png-conversion.json)
  Description: This n8n flow allows testing HTML to PDF conversion and its subsequent conversion to PNG by clicking the 'Test workflow' button.

- [0511-outlook-jira-ai-tickets.json](workflows/0511-outlook-jira-ai-tickets.json)
  Description: This automated flow monitors email in the Outlook inbox for support tickets, classifies and prioritizes them with artificial intelligence, then creates a ticket in Jira using that structured data. Sticky notes provide instructions and context on how the flow works.

- [0512-web-scraper-structured.json](workflows/0512-web-scraper-structured.json)
  Description: This automated flow allows extracting structured information about web products (name, description, price, rating, and number of reviews) from cleaned HTML pages. It uses Google Sheets to get lists of URLs to process, cleans the content with a Node.js script before sending it to the GPT-4 model via OpenRouter, and finally appends the structured JSON results to another sheet in the document.

- [0513-email-tracking-pixel.json](workflows/0513-email-tracking-pixel.json)
  Description: This automated flow allows detecting when an email is opened by sending a transparent PNG image via webhook, capturing parameters like userId to identify the sender.

- [0515-auto-iniciar-flujos-n8n.json](workflows/0515-auto-iniciar-flujos-n8n.json)
  Description: This flow allows manually starting two execution instances in n8n via the trigger. The description explains that these flows do not start automatically after import, unless they have the 'Auto start' tag and are configured for auto-deploy.

- [0516-email-classification-ai.json](workflows/0516-email-classification-ai.json)
  Description: This flow processes emails, classifies them into specific categories using OpenAI models, and extracts relevant information about candidates.

- [0517-postgres-csv-export.json](workflows/0517-postgres-csv-export.json)
  Description: This automated flow queries data from a specific table (booksRead) in PostgreSQL via a manual trigger and exports the result to a CSV file.

- [0518-google-drive-pdf-to-html.json](workflows/0518-google-drive-pdf-to-html.json)
  Description: This automated flow converts new PDF files saved in Google Drive to HTML and automatically saves them in the same folder.

- [0519-clockify-syncro-timer-sync.json](workflows/0519-clockify-syncro-timer-sync.json)
  Description: This flow synchronizes time entries between Clockify and Syncro via Google Sheets.

- [0520-daily-english-poems.json](workflows/0520-daily-english-poems.json)
  Description: This automated flow sends a random daily poem translated into British English, using the Poemist API and Telegram.

- [0521-mailchimp-subscribe.json](workflows/0521-mailchimp-subscribe.json)
  Description: This manual flow allows subscribing to the Mailchimp list with the specified email and adding predefined fields like FNAME.

- [0522-namecheap-ddns-updater.json](workflows/0522-namecheap-ddns-updater.json)
  Description: This automated flow checks every 15 minutes if the public IP has changed and automatically updates DNS records for multiple subdomains in Namecheap.

- [0523-orlen-factura-automatizada.json](workflows/0523-orlen-factura-automatizada.json)
  Description: This automated flow downloads and processes daily electronic invoices from Orlen's Gmail, uploads them to a Google Drive folder organized by year and month, marks them as read, and notifies via Slack the directory where they have been uploaded.

- [0524-mattermost-instagram-stats.json](workflows/0524-mattermost-instagram-stats.json)
  Description: This automated flow checks Instagram profile statistics (like followers and posts) every day at 8:00 AM and sends the updated data in a formatted message with the current date and time.

- [0525-the-hive-alerts.json](workflows/0525-the-hive-alerts.json)
  Description: This automated flow checks when a new alert is created in TheHive that is not closed. If the condition is met, it sends a notification to SIGNL4 (likely to send an alarm via LINE) with the alert details and also starts an additional process if necessary.

- [0526-webhook-analisis-datos.json](workflows/0526-webhook-analisis-datos.json)
  Description: This flow analyzes a webhook to extract data and generate a response.

- [0527-3-xml-transform.json](workflows/0527-3-xml-transform.json)
  Description: This flow processes and transforms data in XML format by converting an XML string into a structured object.

- [0528-twilio_trigger.json](workflows/0528-twilio_trigger.json)
  Description: This automated flow allows manually executing actions in Twilio via an API using the manual trigger.

- [0529-active-campaign-contact.json](workflows/0529-active-campaign-contact.json)
  Description: This flow allows manually loading user information to ActiveCampaign from n8n.

- [0530-workflow-bloqueo-medio-dev-to.json](workflows/0530-workflow-bloqueo-medio-dev-to.json)
  Description: This automated flow allows sending articles to both the Medium platform and the dev.to API via an HTTP request, using configured credentials for both actions.

- [0531-webflow-form-trigger.json](workflows/0531-webflow-form-trigger.json)
  Description: This automated flow is triggered when a form is submitted on a Webflow webpage and collects the data for processing.

- [0532-hackernoon-extractor.json](workflows/0532-hackernoon-extractor.json)
  Description: This manual flow extracts article titles and links from the Hacker Noon homepage (hackernoon.com) via HTML analysis.

- [0533-digitalocean-create-droplet.json](workflows/0533-digitalocean-create-droplet.json)
  Description: This automated flow creates a Droplet instance on DigitalOcean using specified parameters and authenticating with a personal access token.

- [0534-speech-recognition-wit-ai.json](workflows/0534-speech-recognition-wit-ai.json)
  Description: This automated flow uses the Read Binary File node to read a WAV file at the specified path and sends it to the Wit.ai API via an HTTP POST request for processing.

- [0535-pay-pal-batch-operation.json](workflows/0535-pay-pal-batch-operation.json)
  Description: This flow executes an operation on the PayPal account using the provided batch ID.

- [0536-signl4-test-alert.json](workflows/0536-signl4-test-alert.json)
  Description: This manual flow allows triggering a predefined alert in SIGNL4 by clicking the 'execute' button, sending a sample message and title.

- [0537-shopify-odoo-product-sync.json](workflows/0537-shopify-odoo-product-sync.json)
  Description: This flow automatically synchronizes new products from Shopify with Odoo. It is activated when a product is created in Shopify (event 'products/create') and searches if it already exists in Odoo using the default code. If it does not exist, it creates it; if it already exists, it verifies the product data to perform an update.

- [0538-postgres-query.json](workflows/0538-postgres-query.json)
  Description: This automated flow allows executing a SQL select command in a PostgreSQL database via manual activation.

- [0539-banner-cocktail.json](workflows/0539-banner-cocktail.json)
  Description: This automated flow displays a random cocktail recipe every Friday at 6:00 PM via a message with an image in Rocket.Chat.

- [0540-paypal-billing-plan-activated-trigger.json](workflows/0540-paypal-billing-plan-activated-trigger.json)
  Description: This automated flow allows n8n to receive notifications when PayPal activates a billing plan.

- [0541-github-notifications-monitor.json](workflows/0541-github-notifications-monitor.json)
  Description: This automated flow periodically queries (every minute) user notifications on GitHub and if they exist, sends a formatted summary to a Discord application.

- [0542-asana-tweet-event-trigger.json](workflows/0542-asana-tweet-event-trigger.json)
  Description: This automated flow allows receiving updates when an event related to tweets occurs in Asana.

- [0543-postmark-email-events-trigger.json](workflows/0543-postmark-email-events-trigger.json)
  Description: This flow collects updates for specific Postmark events for emails, such as bounces or opens.

- [0544-n8n-daily-ai-news.json](workflows/0544-n8n-daily-ai-news.json)
  Description: This automated flow searches for articles related to artificial intelligence (AI) using NewsAPI and GNews APIs, merges them, and uses GPT-4 to summarize and translate them into traditional Chinese while keeping technical terms in English.

- [0545-google-page-entity-extraction.json](workflows/0545-google-page-entity-extraction.json)
  Description: This flow analyzes the HTML content of any webpage to extract structured data about entities recognized by Google.

- [0546-thehive-email-iocs.json](workflows/0546-thehive-email-iocs.json)
  Description: This automated flow processes incoming emails via IMAP, analyzes them with Cortex to detect indicators of compromise (IoCs), and creates corresponding observables in TheHive for each identified IoC type.

- [0547-wallabag-ttrss-sync.json](workflows/0547-wallabag-ttrss-sync.json)
  Description: This automated flow is used to save articles marked as starred in TT-RSS to the Wallabag application.

- [0548-telegram-journal-saver.json](workflows/0548-telegram-journal-saver.json)
  Description: This automated flow captures user responses in Telegram to save daily entries in a spreadsheet.

- [0549-github-stars-slack.json](workflows/0549-github-stars-slack.json)
  Description: This automated flow monitors changes in stars of the 'n8n' GitHub repository and sends real-time messages to a Slack channel.

- [0550-zammad-tickets-summary.json](workflows/0550-zammad-tickets-summary.json)
  Description: This automated flow allows querying the number of open and new tickets in Zammad, filtering them by status, and sending a summary to the Zulip support room.

- [0551-manual-aws-sns-trigger.json](workflows/0551-manual-aws-sns-trigger.json)
  Description: This manual flow allows sending a predefined message to a specific AWS SNS topic by clicking the 'execute' button.

- [0552-insertar-valor-mongodb.json](workflows/0552-insertar-valor-mongodb.json)
  Description: This manual flow inserts a specific value into the MongoDB database when executed.

- [0553-aws-ses-email.json](workflows/0553-aws-ses-email.json)
  Description: This automated flow allows sending a predefined email via AWS SES when manually executed.

- [0554-aws-sns-trigger.json](workflows/0554-aws-sns-trigger.json)
  Description: This flow uses an AWS SNS subscription to receive notifications and potentially initiate processes or workflows in response.

- [0555-manual-aws-lambda-test.json](workflows/0555-manual-aws-lambda-test.json)
  Description: This manual flow allows triggering a specific AWS Lambda via a click action.

- [0556-msg91-sms-flow.json](workflows/0556-msg91-sms-flow.json)
  Description: This automated flow allows sending SMS using the MSG91 service via manual activation.

- [0557-facebook_datos_basicos.json](workflows/0557-facebook_datos_basicos.json)
  Description: This flow manually gets the basic personal data (first and last name) of the current user on Facebook via an API call.

- [0558-google-drive-download.json](workflows/0558-google-drive-download.json)
  Description: This automated flow allows downloading a Google Drive file and saving it locally with a specific name.

- [0559-mailchimp-subscribe-alert.json](workflows/0559-mailchimp-subscribe-alert.json)
  Description: This flow activates an action when someone subscribes to the specified Mailchimp list.

- [0560-trigger-cockpit-sample.json](workflows/0560-trigger-cockpit-sample.json)
  Description: This automated flow allows initiating a manual process and immediately connecting it with the Cockpit node to visualize data from the 'samplecollection' collection.

- [0561-flujo-verificacion-email-hunter.json](workflows/0561-flujo-verificacion-email-hunter.json)
  Description: This automated flow verifies the email using the Hunter API when manually activated.

- [0562-mqtt-trigger.json](workflows/0562-mqtt-trigger.json)
  Description: This automated flow receives messages from an MQTT queue when a message is published to the corresponding topic.

- [0563-mailjet-correo-test.json](workflows/0563-mailjet-correo-test.json)
  Description: This manual flow allows sending an email using Mailjet. Predefined text, subject, sender address, and recipient address are included.

- [0564-line-chatbot-memory.json](workflows/0564-line-chatbot-memory.json)
  Description: This flow is triggered when an email is sent via the Mailjet API.

- [0565-mailgun-email-sender-test.json](workflows/0565-mailgun-email-sender-test.json)
  Description: This manual flow allows sending a predefined email message when the 'execute' button is clicked.

- [0566-hacker-news-trigger.json](workflows/0566-hacker-news-trigger.json)
  Description: This automated flow allows manually executing an action to get data from all Hacker News categories.

- [0567-github-monitor-repo.json](workflows/0567-github-monitor-repo.json)
  Description: This flow monitors any activity in the 'n8n-io/n827-docs' GitHub repository via a webhook, using predefined credentials for the API.

- [0568-gitlab-trigger-n8n-docs.json](workflows/0568-gitlab-trigger-n8n-docs.json)
  Description: This flow monitors events in the GitLab n8n-io/n8n-docs repository via a webhook.

- [0569-bitbucket-push-monitor.json](workflows/0569-bitbucket-push-monitor.json)
  Description: This flow is automatically triggered when there is a push event in the 'test' Bitbucket repository.

- [0570-travis-ci-trigger-build.json](workflows/0570-travis-ci-trigger-build.json)
  Description: This manual flow allows initiating a build in Travis CI by clicking, integrating the service in an automated way.

- [0571-acuity-appointment-trigger.json](workflows/0571-acuity-appointment-trigger.json)
  Description: This flow is triggered when a user schedules an appointment via Acuity Scheduling.

- [0572-invoice-ninja-getall.json](workflows/0572-invoice-ninja-getall.json)
  Description: This manual flow allows getting all invoices from the account using the Invoice Ninja API service.

- [0573-invoice-creation-trigger.json](workflows/0573-invoice-creation-trigger.json)
  Description: This automated flow is triggered when an invoice is created in the Invoice Ninja API.

- [0574-clockify-event-poller.json](workflows/0574-clockify-event-poller.json)
  Description: This automated flow periodically monitors the specified Clockify workspace every minute, waiting for any event to occur to trigger subsequent actions.

- [0575-copper-project-trigger.json](workflows/0575-copper-project-trigger.json)
  Description: This automated flow is triggered by a Copper webhook when 'new' events occur in 'project' type resources.

- [0576-eventbrite-order-triggers.json](workflows/0576-eventbrite-order-triggers.json)
  Description: This flow activates an integration when events related to ticket orders occur in Eventbrite, such as creation, update, or refund.

- [0577-rundeck-job-trigger.json](workflows/0577-rundeck-job-trigger.json)
  Description: This flow allows manually initiating the execution of a specific job in Rundeck by clicking the 'execute' button.

- [0578-calendly-eventos-monitor.json](workflows/0578-calendly-eventos-monitor.json)
  Description: This flow monitors Calendly events to receive notifications when a participant is created or canceled in an appointment.

- [0579-jotform-trigger.json](workflows/0579-jotform-trigger.json)
  Description: This automated flow is triggered when a specific JotForm form (ID: 202012795501445) is completed, using authentication credentials with the JotForm API.

- [0580-xero-get-all.json](workflows/0580-xero-get-all.json)
  Description: This manual flow initiates execution to get all items from Xero via OAuth2 authentication.

- [0582-bannerbear-imagen-manual.json](workflows/0582-bannerbear-imagen-manual.json)
  Description: This automated flow allows a user to manually initiate the generation of an image using the Bannerbear service with a specific identifier and predefined parameters for text, color, and background.

- [0583-wordpress-get-all.json](workflows/0583-wordpress-get-all.json)
  Description: This flow allows manually executing an action that gets all articles from a WordPress instance via its API credentials.

- [0584-shopify-order-trigger.json](workflows/0584-shopify-order-trigger.json)
  Description: This active flow is triggered when a new order is created in Shopify via webhook.

- [0585-shopify-get-all-records.json](workflows/0585-shopify-get-all-records.json)
  Description: This flow manually executes the 'execute' trigger which then gets all records from a Shopify account.

- [0586-typeform-seleccion-automatizada.json](workflows/0586-typeform-seleccion-automatizada.json)
  Description: This automated flow allows logging Typeform form selections in Airtable.

- [0587-paddle-coupon-creator.json](workflows/0587-paddle-coupon-creator.json)
  Description: This automated flow allows creating a coupon offer in Paddle using specific parameters.

- [0588-survey-monkey-trigger.json](workflows/0588-survey-monkey-trigger.json)
  Description: This automated flow is triggered when a new response is created in the specific SurveyMonkey survey.

- [0589-zoho-crm-get-all.json](workflows/0589-zoho-crm-get-all.json)
  Description: This manual flow initiates execution to get all records from Zoho CRM via OAuth2 authentication.

- [0590-keap-contact-all.json](workflows/0590-keap-contact-all.json)
  Description: This flow manually activates an execution that gets all contacts from Keap.

- [0591-line-keap-integracion-automatica.json](workflows/0591-line-keap-integracion-automatica.json)
  Description: This automated flow initiates processes in n8n when a new contact is added in Keap.

- [0592-monday-board-data.json](workflows/0592-monday-board-data.json)
  Description: This flow executes a manual action in n8n to get data from a specific board in Monday.com.

- [0593-line-chatbot-memory.json](workflows/0593-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation through persistence in Redis.

- [0594-spacex-graphql-query.json](workflows/0594-spacex-graphql-query.json)
  Description: This manual flow queries the SpaceX API via GraphQL to get details about the latest launches and spacecraft data.

- [0595-box-folder-execution.json](workflows/0595-box-folder-execution.json)
  Description: This flow automatically executes an action on a specific Box folder when the 'execute' button is clicked.

- [0596-cfp-trello-cards.json](workflows/0596-cfp-trello-cards.json)
  Description: This flow selects applicants from a CFP event with a score greater than 15 in Airtable and creates Trello cards from the form information using Bannerbear to generate advertising images.

- [0597-cocktaildb-json-xml-conversion.json](workflows/0597-cocktaildb-json-xml-conversion.json)
  Description: This automated flow converts JSON response data from the CocktailDB API to XML.

- [0598-expense-receipt-automation.json](workflows/0598-expense-receipt-automation.json)
  Description: This automated flow collects receipts via Typeform, extracts relevant information using Mindee, and stores the data in Airtable.

- [0599-box-folder-file-events.json](workflows/0599-box-folder-file-events.json)
  Description: This automated flow is triggered when files or folders are moved or downloaded in a specific Box folder.

- [0600-one-drive-folder-creation.json](workflows/0600-one-drive-folder-creation.json)
  Description: This manual flow allows creating a folder in OneDrive by clicking the 'execute' button.

- [0601-excel-trigger.json](workflows/0601-excel-trigger.json)
  Description: This flow executes a manual process by clicking the start button, which then queries all available data via the Microsoft Excel connector.

- [0602-helpscout-mailbox-fetcher.json](workflows/0602-helpscout-mailbox-fetcher.json)
  Description: This flow allows getting all emails stored in a specific mailbox via integration with HelpScout.

- [0603-jira-trigger-any-event.json](workflows/0603-jira-trigger-any-event.json)
  Description: This flow monitors any event in Jira Software Cloud via a web connection.

- [0604-sms-alert-error-notification.json](workflows/0604-sms-alert-error-notification.json)
  Description: This workflow sends an SMS alert when a specific workflow fails in its execution.

- [0605-mandrill-email.json](workflows/0605-mandrill-email.json)
  Description: This flow allows sending an email using the 'welcomeemailv2' template from the Mandrill node by clicking 'execute'.

- [0606-n8n-rocks-crypto-example.json](workflows/0606-n8n-rocks-crypto-example.json)
  Description: This manual flow allows executing an encryption operation on the string 'n8n rocks!' simply by clicking.

- [0607-manual-execute-date.json](workflows/0607-manual-execute-date.json)
  Description: This automated flow allows the user to manually start a process with the specific date '14/02/2020' using DD/MM/YYYY format.

- [0608-analisis-imagen-http.json](workflows/0608-analisis-imagen-http.json)
  Description: This manual flow allows downloading an image from a specific URL and extracting information about it.

- [0609-trigger-leer-imagen-binaria.json](workflows/0609-trigger-leer-imagen-binaria.json)
  Description: This flow allows loading binary files like images by clicking the trigger.

- [0610-read-images-trigger.json](workflows/0610-read-images-trigger.json)
  Description: This automated flow allows a user to manually initiate an execution, which reads binary files (specifically jpg images) from the /data/lol directory.

- [0611-telegram-cocktails-daily.json](workflows/0611-telegram-cocktails-daily.json)
  Description: This automated flow sends a random cocktail from TheCocktailDB daily at 8:00 PM via a photo with its recipe.

- [0612-workflow-n8n-581.json](workflows/0612-workflow-n8n-581.json)
  Description: This flow starts with a manual trigger, processes data through a function that returns two objects (with IDs 0 and 1), and then uses a conditional node to evaluate if the 'value1' value matches the expected results.

- [0613-manual-trigger-renamer.json](workflows/0613-manual-trigger-renamer.json)
  Description: This flow is manually triggered and then sets a value for the key 'somevalue', which is later renamed to 'newkey'.

- [0614-read-rss-feed.json](workflows/0614-read-rss-feed.json)
  Description: This automated flow allows executing the reading of a specific RSS feed via a manual button.

- [0615-send-email-example.json](workflows/0615-send-email-example.json)
  Description: This manual flow allows sending a predefined email by clicking the execution button.

- [0616-pdf-binario-lector.json](workflows/0616-pdf-binario-lector.json)
  Description: This automated flow, when 'execute' is clicked, reads a locally stored binary PDF file and processes it.

- [0618-flujo-email-imap.json](workflows/0618-flujo-email-imap.json)
  Description: This automated flow allows reading emails from an IMAP server.

- [0619-trigger-workflow.json](workflows/0619-trigger-workflow.json)
  Description: This manual flow allows initiating the execution of another workflow by clicking the button.

- [0620-58_telegram_coktai_random.json](workflows/0620-58_telegram_coktai_random.json)
  Description: This automated flow captures Telegram messages using a webhook. It then makes a GET request to TheCocktailDB API to get a random cocktail and extracts its image and name.

- [0621-crear-tabla-y-insertar.json](workflows/0621-crear-tabla-y-insertar.json)
  Description: This manual flow creates a table in CrateDB if it doesn't exist and then inserts a record with predefined values.

- [0622-crear-tabla-json.json](workflows/0622-crear-tabla-json.json)
  Description: This flow executes a SQL query to create a table named 'test' with id and name columns, then sets a set of values that includes that data.

- [0623-postgres-create-set-insert.json](workflows/0623-postgres-create-set-insert.json)
  Description: This automated flow starts with a manual click that executes a SQL query to create a table called 'test' in PostgreSQL. Then, it takes the output of that creation and uses it as input to set values in the Set node (specifically, it expects to set a numerical value for 'id' and a fixed string for 'name'). Finally, these values are sent to another PostgreSQL operation.

- [0624-mocean-sms.json](workflows/0624-mocean-sms.json)
  Description: This automated flow allows sending a text message (SMS) via the Mocean service through manual activation.

- [0625-facebook_comments_flow.json](workflows/0625-facebook_comments_flow.json)
  Description: This flow gets the most recent messages and comments from posts on a Facebook page according to the initial configuration.

- [0626-github-release-slack-notification.json](workflows/0626-github-release-slack-notification.json)
  Description: This automated flow monitors new releases in the 'Mesdocteurs/mda-admin-partner-api' GitHub repository and sends a notification message on Slack to the 'extranet-md' channel.

- [0627-figma-jira-sync.json](workflows/0627-figma-jira-sync.json)
  Description: This flow detects updates in Figma versions via the Commit plugin webhook and adds a comment to the specific Jira issue JAJ-368 with relevant details.

- [0628-perplexity-research.json](workflows/0628-perplexity-research.json)
  Description: This automated flow searches and extracts information related to a specific query using the Perplexity AI API, formatting the result to get clean content.

- [0629-chatbot-pizza-order.json](workflows/0629-chatbot-pizza-order.json)
  Description: This flow allows a chatbot to handle pizza orders by maintaining conversational memory and using tools like a calculator, product menu, and order history.

- [0630-telegram-bash-automated-response.json](workflows/0630-telegram-bash-automated-response.json)
  Description: This automated flow allows an automatic response to be sent when a message is received on the Telegram bot (bash-dash).

- [0631-manual-github-profile-request.json](workflows/0631-manual-github-profile-request.json)
  Description: This flow allows manually triggering a request to the GitHub API to get a repository profile.

- [0632-slack-github-email-query.json](workflows/0632-slack-github-email-query.json)
  Description: This automated flow queries user information and their latest contributions on GitHub via GraphQL, processes the found emails (filtering those not corresponding to a real user), and sends a formatted message with this data to the specified Slack channel.

- [0633-syncro-ticket-proyecto.json](workflows/0633-syncro-ticket-proyecto.json)
  Description: This flow synchronizes the status of unresolved tickets from an external source with their corresponding projects in Clockify.

- [0634-dos_pasos_google_sheets.json](workflows/0634-dos_pasos_google_sheets.json)
  Description: This automated flow allows the user to initiate manual execution and then append data in Google Sheets.

- [0635-api-reqres-interactions.json](workflows/0635-api-reqres-interactions.json)
  Description: This flow makes a GET request to the reqres.in user API, followed by a POST to create a user, and finally a PATCH to update their job.

- [0636-wp-post-automation.json](workflows/0636-wp-post-automation.json)
  Description: This automated flow creates a new post in WordPress and immediately updates the content afterwards.

- [0637-60_n8n_mysql_purge_older_records.json](workflows/0637-60_n8n_mysql_purge_older_records.json)
  Description: This flow automatically deletes old execution records (older than one month) in the MySQL database to optimize storage.

- [0638-mattermost-chatbot-response.json](workflows/0638-mattermost-chatbot-response.json)
  Description: This automated flow uses a Mattermost webhook to process messages and send notifications with information stored using the Set node.

- [0639-dropbox-http-image.json](workflows/0639-dropbox-http-image.json)
  Description: This n8n flow allows interaction with Dropbox via an HTTP request, first listing files from a directory and then uploading a specific file.

- [0640-helpscout-customer-created.json](workflows/0640-helpscout-customer-created.json)
  Description: This flow specifically listens for the 'customer.created' event in HelpScout using an OAuth webhook.

- [0641-nextcloud-http-image-upload.json](workflows/0641-nextcloud-http-image-upload.json)
  Description: This flow allows downloading an image from an HTTP server and then uploading it to the 'n8n' folder in NextCloud, as well as saving it directly with the specified name.

- [0642-hubspot-trigger-dghert3.json](workflows/0642-hubspot-trigger-dghert3.json)
  Description: This automated flow is a trigger for processing specific events in HubSpot with appId dghert3.

- [0643-email-excuse-notification.json](workflows/0643-email-excuse-notification.json)
  Description: This automated flow analyzes the sender of an email, reads data from a spreadsheet to generate random excuses, and sends both results (the modified original email and Slack notifications) when the sender is Louis Litt.

- [0644-hoja-mautic-sync.json](workflows/0644-hoja-mautic-sync.json)
  Description: This automated flow reads data from a Google Sheets spreadsheet every 5 minutes and sends it as custom fields to Mautic CRM.

- [0645-sse-trigger-n8n.json](workflows/0645-sse-trigger-n8n.json)
  Description: This automated flow uses an SSE trigger node to initiate processes based on events sent from the n8n.io server.

- [0646-nuevo-triage-afinidad-lista.json](workflows/0646-nuevo-triage-afinidad-lista.json)
  Description: This flow is triggered when a new list is created in the Affinity API.

- [0647-contentful-get-all.json](workflows/0647-contentful-get-all.json)
  Description: This automated flow allows getting all content items from a Contentful instance via a manual trigger.

- [0648-unleashed-ordenes-completadas.json](workflows/0648-unleashed-ordenes-completadas.json)
  Description: This manual flow executes a query in the Unleashed system only for completed orders.

- [0649-amazon-s3-upload-list-json.json](workflows/0649-amazon-s3-upload-list-json.json)
  Description: Downloads a file from a URL, uploads it to Amazon S3, and displays all files in the bucket.

- [0650-cocktail-storage.json](workflows/0650-cocktail-storage.json)
  Description: This automated flow allows persistently storing raw data of a random drink obtained from the CocktailDB API by saving it as a JSON file.

- [0651-ejemplo-merge.json](workflows/0651-ejemplo-merge.json)
  Description: This flow analyzes sample data to merge information about name and greeting based on common language.

- [0652-product-feedback-workflow.json](workflows/0652-product-feedback-workflow.json)
  Description: This automated flow collects feedback and ratings about a product via Typeform, stores them in Airtable, and when the score is equal to 7, creates a Trello card with the provided information.

- [0653-bidirectional-sync.json](workflows/0653-bidirectional-sync.json)
  Description: This flow bidirectionally synchronizes data between the MySQL database and Pipedrive CRM.

- [0654-descargar-y-subir-imagen.json](workflows/0654-descargar-y-subir-imagen.json)
  Description: This automated flow allows downloading an image from n8n.io and uploading it directly to an FTP server via the 'execute' button.

- [0655-salesforce-update-and-note.json](workflows/0655-salesforce-update-and-note.json)
  Description: This automated flow allows updating specific fields of a record in Salesforce and adding a note to it, using the ID of the preceding record.

- [0656-teams-automation.json](workflows/0656-teams-automation.json)
  Description: This automated flow allows manually executing a sequence of actions in Microsoft Teams, where first the connection with a predefined team is initiated, then its name is updated, and finally a message is sent to a specific channel.

- [0657-linkedin-automation.json](workflows/0657-linkedin-automation.json)
  Description: This automated flow downloads an image from the specified URL and posts that image to LinkedIn along with a predefined message.

- [0658-demo-n8n-flujo.json](workflows/0658-demo-n8n-flujo.json)
  Description: This flow demonstrates how n8n can use 'function' nodes to generate data and 'switch' nodes to create response paths based on comparisons.

- [0659-error-alert-email.json](workflows/0659-error-alert-email.json)
  Description: This flow detects errors in any node and sends a detailed email to the administrator with information about the error, affected workflow, and technical details.

- [0660-taiga-issue-management.json](workflows/0660-taiga-issue-management.json)
  Description: This automated flow allows creating, updating, and getting an issue in Taiga from a manual trigger.

- [0661-weather-alert.json](workflows/0661-weather-alert.json)
  Description: This automated flow periodically queries the temperature in Berlin and sends a text message notifying to bundle up if the current 'feeling' value is below 18 degrees Celsius.

- [0662-brave-search-chatbot.json](workflows/0662-brave-search-chatbot.json)
  Description: This workflow implements a chatbot that uses GPT-4o and MCP tools to perform web searches on Brave, maintaining contextualized memory.

- [0663-iot-mqtt-influxdb-monitoring.json](workflows/0663-iot-mqtt-influxdb-monitoring.json)
  Description: This automated flow receives data from remote IoT sensors via an MQTT topic 'wokwi-weather', processes and validates temperature and humidity readings, then writes these values in JSON format to an InfluxDB database.

- [0664-tts-openai.json](workflows/0664-tts-openai.json)
  Description: This flow allows text-to-speech conversion via OpenAI's speech synthesis service.

- [0665-pipeline-etl-twitter-sentiment.json](workflows/0665-pipeline-etl-twitter-sentiment.json)
  Description: This automated flow searches for tweets with the hashtag #OnThisDay, inserts the texts into a MongoDB database, and performs sentiment analysis using Google Cloud Natural Language to store score and magnitude metrics in PostgreSQL. If the score is high, it sends a message to Slack.

- [0666-sheets-sync-every-2min.json](workflows/0666-sheets-sync-every-2min.json)
  Description: This automated flow executes an update on two Google sheets every two minutes, using previously read data.

- [0667-taiga-event-trigger.json](workflows/0667-taiga-event-trigger.json)
  Description: This flow listens for events in the specific Taiga project via a webhook trigger.

- [0668-wekan-board-creation.json](workflows/0668-wekan-board-creation.json)
  Description: This automated flow allows a user to manually execute the process of creating Wekan boards, lists, and cards.

- [0669-event-registration.json](workflows/0669-event-registration.json)
  Description: This automated flow allows registering attendees and managing their participation in n8nConf, the no-code conference.

- [0670-n8n-cron-google-sheets-mattermost.json](workflows/0670-n8n-cron-google-sheets-mattermost.json)
  Description: This automated flow executes a task in Mattermost every year on December 17th at 00:00 (UTC), using dynamic values extracted from Google Sheets.

- [0671-weather-processing.json](workflows/0671-weather-processing.json)
  Description: This automated flow processes weather data using the OpenWeatherMap API to get information about temperature, humidity, wind speed, and description.

- [0672-webhook-weather-sync.json](workflows/0672-webhook-weather-sync.json)
  Description: This automated flow receives data via webhook, extracts key information, and stores it in Airtable for later use. Subsequently, it queries the weather of the provided city using OpenWeatherMap API and sends an SMS message to a specific number with the forecast details via Twilio.

- [0673-expense-tracker-mindee-airtable.json](workflows/0673-expense-tracker-mindee-airtable.json)
  Description: This flow allows receiving a webhook with invoice data that Mindee processes and stores in an Airtable table.

- [0674-transformador-array.json](workflows/0674-transformador-array.json)
  Description: This automated flow starts with a node that generates static data in array form and then uses a custom function to transform each element of the array into an individual JSON object.

- [0675-clockify-proyecto-entrada-tiempo.json](workflows/0675-clockify-proyecto-entrada-tiempo.json)
  Description: This automated flow creates a project in Clockify with specific details and then adds a time entry using that project, maintaining context consistency.

- [0676-google-sheets-telegram-batch.json](workflows/0676-google-sheets-telegram-batch.json)
  Description: This flow processes Google Sheets entries in batches and sends each batch to Telegram.

- [0677-mindee-receipt-extractor.json](workflows/0677-mindee-receipt-extractor.json)
  Description: This automated flow processes a receipt image using Mindee to extract structured information and returns the result in JSON format.

- [0678-wufoo-form-submission.json](workflows/0678-wufoo-form-submission.json)
  Description: This automated flow receives updates when a specific form in Wufoo is submitted.

- [0679-bitcoin-monitor-sms.json](workflows/0679-bitcoin-monitor-sms.json)
  Description: This flow checks the price of Bitcoin in euros from CoinGecko every minute and sends an SMS if it exceeds 9000 EUR.

- [0680-firecrawl-markdown-extractor.json](workflows/0680-firecrawl-markdown-extractor.json)
  Description: This automated flow uses FireCrawl to perform web scraping from a provided URL, formatting the result as markdown text for easy use in applications and agents.

- [0681-notion-ai-blog-update.json](workflows/0681-notion-ai-blog-update.json)
  Description: This automated flow reacts to updates in a Notion database using DeepSeek to create SEO articles and publish them both on WordPress and update the original record.

- [0682-sitemap-json-filter.json](workflows/0682-sitemap-json-filter.json)
  Description: This flow reads a sitemap.xml file and extracts all its URLs individually.

- [0683-github-credentials-restore.json](workflows/0683-github-credentials-restore.json)
  Description: This automated flow allows restoring all instance credentials from a GitHub repository.

- [0684-hubspot-contactos-getall.json](workflows/0684-hubspot-contactos-getall.json)
  Description: This automated flow manually initiates obtaining all HubSpot contacts via the 'getAll' node of the 'contact' resource.

- [0685-coffee-bot-mattermost.json](workflows/0685-coffee-bot-mattermost.json)
  Description: This automated flow organizes employees into random groups for virtual coffee sessions every Monday and sends calendar invitations, in addition to announcing the formed groups.

- [0686-language-learning-words.json](workflows/0686-language-learning-words.json)
  Description: This automated flow extracts words from the titles of the top three Hacker News stories, translates them into German, and saves the result. It then sends an SMS with a selection of five German words along with their corresponding English term.

- [0687-medium-publication.json](workflows/0687-medium-publication.json)
  Description: This flow allows publishing articles in a Medium publication.

- [0688-youtube-raindrop-sync.json](workflows/0688-youtube-raindrop-sync.json)
  Description: This automated flow checks the specified YouTube playlist every 30 minutes and adds new videos to Raindrop as bookmarks with a title composed of the owner's name and video title, and tags them 'youtube'.

- [0689-nuevo-producto-slack.json](workflows/0689-nuevo-producto-slack.json)
  Description: This automated flow detects the creation of new products in WooCommerce and sends a notification to a Slack channel.

- [0690-github-sync-n8n.json](workflows/0690-github-sync-n8n.json)
  Description: This flow automatically synchronizes N8N workflows with a file on GitHub via comparison and deferred editing.

- [0691-openai-image-gen.json](workflows/0691-openai-image-gen.json)
  Description: This automated flow uses the OpenAI ImageGen v1 API to edit images and generate a new version based on the provided prompt.

- [0692-disco-alerta-cron.json](workflows/0692-disco-alerta-cron.json)
  Description: This flow automatically checks the disk space of the system root (host) every day at 9:00 AM and 4:00 PM. If it detects that it is above 80%, it sends an SMS alert to Twilio, notifying the exact percentage of use. Otherwise, it takes no action.

- [0693-woocommerce-order-notification.json](workflows/0693-woocommerce-order-notification.json)
  Description: This automated flow sends a Slack notification when a new order is created in WooCommerce, provided the order total is 100 or more.

- [0694-orbit-import-from-sheets.json](workflows/0694-orbit-import-from-sheets.json)
  Description: This automated flow imports member and activity data from Google Sheets to the Orbit platform using OAuth2 credentials.

- [0695-automizy-list-management.json](workflows/0695-automizy-list-management.json)
  Description: This flow automates the creation of a new list in Automizy, adds a contact with a predefined and updated email, then gets all stored contacts.

- [0696-woocommerce-refund-notification.json](workflows/0696-woocommerce-refund-notification.json)
  Description: This flow checks when a WooCommerce order is updated to refunded status and if the total is 100 or more, automatically sends a notification to the 'woo-commerce' Slack channel with specific details.

- [0697-weather-daily-update.json](workflows/0697-weather-daily-update.json)
  Description: This scheduled flow sends a daily Pushcut notification with the Berlin weather forecast.

- [0698-matrix-room-invite.json](workflows/0698-matrix-room-invite.json)
  Description: This automated flow creates a discussion room in Matrix and invites the current user if they are not already invited.

- [0699-zoom-crear-reunion.json](workflows/0699-zoom-crear-reunion.json)
  Description: This automated flow creates a meeting in Zoom using the OAuth2 API via a manual trigger.

- [0700-mautic-woocommerce-sync.json](workflows/0700-mautic-woocommerce-sync.json)
  Description: This flow checks if a WooCommerce customer exists in Mautic via a Mautic search and automatically creates or updates contacts in Mautic.

- [0701-circleci-api-trigger.json](workflows/0701-circleci-api-trigger.json)
  Description: This flow allows executing an action on the CircleCI CI/CD platform via its API by manually activating the trigger.

- [0702-daily-weather-alert.json](workflows/0702-daily-weather-alert.json)
  Description: This automated flow sends a daily SMS message with the current temperature of the user specified in OpenWeatherMap.

- [0703-new-product-twitter-telegram.json](workflows/0703-new-product-twitter-telegram.json)
  Description: This automated flow announces the creation of new products in WooCommerce on Twitter and Telegram.

- [0704-messagebird-sms-trigger.json](workflows/0704-messagebird-sms-trigger.json)
  Description: This automated flow allows sending an SMS using MessageBird via manual activation.

- [0705-google-sheets-mattermost-notification.json](workflows/0705-google-sheets-mattermost-notification.json)
  Description: This automated flow checks for new data from a Google Sheets spreadsheet every 45 minutes and sends a formatted message to the chatbot indicating the addition.

- [0706-mautic-email-validation-alert.json](workflows/0706-mautic-email-validation-alert.json)
  Description: This flow checks if a Mautic contact has an invalid or low-quality email address and, if so, sends an alert to Slack.

- [0707-Crear-Issue-Jira.json](workflows/0707-Crear-Issue-Jira.json)
  Description: This automated flow allows quickly creating a new issue in Jira Software by activating a manual trigger.

- [0708-workflow-timer-unique.json](workflows/0708-workflow-timer-unique.json)
  Description: This flow reviews the connections of a workflow in n8n to detect if there are new input items that have not been processed before, based on the timestamp.

- [0709-openweathermap-weather.json](workflows/0709-openweathermap-weather.json)
  Description: This automated flow allows the user to execute a manual process that queries the current weather data for the specified city (in this case, Berlin) via the OpenWeatherMap service.

- [0710-hoja-calc-binaria-lector.json](workflows/0710-hoja-calc-binaria-lector.json)
  Description: This flow reads a binary spreadsheet file and stores it in memory.

- [0711-phishing-analysis-n8n.json](workflows/0711-phishing-analysis-n8n.json)
  Description: This automated flow analyzes indicators of compromise in emails, extracts URLs, and scans them with VirusTotal and URLScan.io to detect potential phishing threats.


- [0713-bright-data-gemini-chat-enhancement.json](workflows/0713-bright-data-gemini-chat-enhancement.json)
  Description: This flow allows Gemini AI to incorporate real-time search results from Google, Bing, or Yandex to improve chatbot responses.

- [0714-telegram-bot-ai-integration.json](workflows/0714-telegram-bot-ai-integration.json)
  Description: This automated flow processes text, audio, and image messages from a Telegram bot using webhooks and the OpenAI API for analysis.

- [0715-ai-calendar-mcp.json](workflows/0715-ai-calendar-mcp.json)
  Description: This n8n workflow uses an AI agent with OpenAI to manage conversational interactions related to Google Calendar. It allows creating, searching, updating, and deleting events, as well as modifying text between uppercase and lowercase via command-responsive tools.

- [0716-blotato-social-publishing.json](workflows/0716-blotato-social-publishing.json)
  Description: This automated flow publishes videos and images on multiple social networks like Instagram, Facebook, LinkedIn, TikTok, and more using the Blotato platform. The automation extracts content from Airtable, generates viral YouTube titles with OpenAI, and manages publication status.

- [0717-rag-chatbot-docs.json](workflows/0717-rag-chatbot-docs.json)
  Description: This automated flow allows an AI chatbot to maintain a contextualized conversation using documents stored in Google Drive and Qdrant. It extracts relevant metadata such as main topics, pain points, and key information to improve semantic search and assistant responses.

- [0718-crypto-news-sentiment-bot.json](workflows/0718-crypto-news-sentiment-bot.json)
  Description: This automated flow analyzes user queries to extract a keyword, searches for related news in multiple cryptocurrency RSS feeds, and uses GPT-4o to synthesize information and evaluate market sentiment.

- [0719-n8n_rss_photo_filter.json](workflows/0719-n8n_rss_photo_filter.json)
  Description: This flow gets new RSS feeds from The Verge that contain images.

- [0720-spotify-cancion-especifica-trigger.json](workflows/0720-spotify-cancion-especifica-trigger.json)
  Description: This manual flow initiates an action in Spotify using a specific song URI to search or play.

- [0721-error-trigger-mailgun.json](workflows/0721-error-trigger-mailgun.json)
  Description: This flow uses an error trigger to send email notifications when an error occurs in workflow execution.

- [0722-compression-to-dropbox.json](workflows/0722-compression-to-dropbox.json)
  Description: This automated flow downloads two images from HTTP URLs, compresses them into a ZIP file, and then uploads the result to Dropbox.

- [0723-gmail-expenses-mindee.json](workflows/0723-gmail-expenses-mindee.json)
  Description: This flow checks emails in Gmail containing keywords like 'expenses' or 'receipt', extracts invoice data using the Mindee API, and automatically adds the details to a Google sheet.

- [0724-rocket-message-sender.json](workflows/0724-rocket-message-sender.json)
  Description: This automated flow is manually triggered and sends a predefined message to the general RocketChat room.

- [0725-file-list-processing.json](workflows/0725-file-list-processing.json)
  Description: This automated flow is manually triggered, reads content from the file '/home/n8n/filelist.txt', splits it into lines using the newline character, stores each item in an array called 'arrData', and then uses the $runIndex variable to execute commands that print filenames based on this array.

- [0726-typeform-airtable-slack.json](workflows/0726-typeform-airtable-slack.json)
  Description: This automated flow collects responses from a Typeform form, extracts the user's name and email, adds them to Airtable, and sends a Slack notification.

- [0727-iss-tracking-timescaledb.json](workflows/0727-iss-tracking-timescaledb.json)
  Description: This automated workflow periodically queries the current position of the ISS satellite and stores it in a TimescaleDB table for temporal analysis.

- [0728-crear-usuario-intercom.json](workflows/0728-crear-usuario-intercom.json)
  Description: This automated flow allows creating a new user in Intercom by manual click.

- [0729-gmail-invoice-alert.json](workflows/0729-gmail-invoice-alert.json)
  Description: This flow checks for new invoices in Gmail using Mindee and sends Slack or email notifications if the total amount exceeds 1000.

- [0730-diaria-temperatura-push.json](workflows/0730-diaria-temperatura-push.json)
  Description: This scheduled flow executes a daily check at 9 AM to get the current temperature of Berlin and sends a Pushover notification with this information.

- [0731-security-scorecard-context-management.json](workflows/0731-security-scorecard-context-management.json)
  Description: This automated flow starts manually, generates a security scorecard for 'n8n.io', gets a single instance of the report, and downloads it from the provided URL.

- [0732-reddit-automated-posting.json](workflows/0732-reddit-automated-posting.json)
  Description: This automated flow posts an initial message on Reddit, then gets data from that post, and finally adds a comment with processed information.

- [0733-automatic-sms-trigger.json](workflows/0733-automatic-sms-trigger.json)
  Description: This automated flow allows sending a predefined SMS by clicking the 'execute' button.

- [0734-pushcut-sms-trigger.json](workflows/0734-pushcut-sms-trigger.json)
  Description: This automated flow sends an SMS when the 'Leaving Home' action is triggered via Pushcut.

- [0735-manual-trigger-translation.json](workflows/0735-manual-trigger-translation.json)
  Description: This manual flow allows executing a fixed translation of an English text to German using Google Translate.

- [0736-discourse-automated.json](workflows/0736-discourse-automated.json)
  Description: This automated flow allows creating, updating, and retrieving messages in Discourse using n8n.

- [0737-getresponse-trigger-airtable.json](workflows/0737-getresponse-trigger-airtable.json)
  Description: This automated flow is triggered by a subscriber in GetResponse for the list 'qtPk7'. When this event occurs, n8n collects the contact data and adds an entry in Airtable to the specified table.

- [0738-n8n-flujo-set-stackby.json](workflows/0738-n8n-flujo-set-stackby.json)
  Description: This flow uses a manual trigger to set static values in a 'set' node, then passes this data to another Stackby node that displays it in a table. The second Stackby uses the ID and name configuration from the first node, maintaining consistency with those fields.

- [0739-peekalink-verificacion.json](workflows/0739-peekalink-verificacion.json)
  Description: This flow verifies if a service is available by querying a specific URL and using logical conditions.

- [0740-tapfiliate-crear-cuenta.json](workflows/0740-tapfiliate-crear-cuenta.json)
  Description: This automated flow creates an affiliate account in Tapfiliate with predefined data and adds a custom tag.

- [0741-strava-activity-flow.json](workflows/0741-strava-activity-flow.json)
  Description: This automated flow allows creating activities in Strava with specific parameters, updating them using the previously obtained ID, and getting information about them.

- [0742-typeform-demio-registration.json](workflows/0742-typeform-demio-registration.json)
  Description: This automated flow activates registration in Demio with data provided by a Typeform form.

- [0743-quickbooks-cliente-factura.json](workflows/0743-quickbooks-cliente-factura.json)
  Description: This automated flow allows creating a customer in QuickBooks and then sending an existing invoice related to that ID.

- [0744-raindrop-automations.json](workflows/0744-raindrop-automations.json)
  Description: This automated flow uses Raindrop to create and update notes sequentially.

- [0745-crear-organizacion-affinity.json](workflows/0745-crear-organizacion-affinity.json)
  Description: This automated flow allows creating an organization in Affinity via a manual trigger.

- [0746-strava-twitter-tweet.json](workflows/0746-strava-twitter-tweet.json)
  Description: This automated flow monitors new cycling activities in Strava and posts a tweet on Twitter with details about the distance covered and the name of the exercise.

- [0747-twitter-monitor-n8n-mentions.json](workflows/0747-twitter-monitor-n8n-mentions.json)
  Description: This automated flow searches for the latest tweets mentioning a company on Twitter and shares them in a Slack channel if they are more recent than the previous execution.

- [0748-webinar-creation-update.json](workflows/0748-webinar-creation-update.json)
  Description: This automated flow creates a web session for the webinar 'Getting started with n8n', then updates its description, and finally executes the webinar action.

- [0749-emelia-campaign-contact.json](workflows/0749-emelia-campaign-contact.json)
  Description: This automated flow creates a marketing campaign in Emelia and adds a contact to that campaign.

- [0751-weather-alert-schedule.json](workflows/0751-weather-alert-schedule.json)
  Description: This workflow checks the current weather in Berlin every time it is manually started or at a scheduled time (06:15), comparing the temperature with a threshold and sending an alert via signl4 if it is below 25°C.

- [0752-line-chatbot-context.json](workflows/0752-line-chatbot-context.json)
  Description: This automated flow uses Webhook and the postHog Integration node to maintain a contextualized conversation.

- [0753-mailerlite-suscriptor.json](workflows/0753-mailerlite-suscriptor.json)
  Description: This workflow uses MailerLite nodes to create, update, and get subscriber details based on email.

- [0754-agile-crm-contact-creation.json](workflows/0754-agile-crm-contact-creation.json)
  Description: This automated flow allows creating a new contact in Agile CRM by activating the manual 'execute' button.

- [0755-airtable-lemlist-sync.json](workflows/0755-airtable-lemlist-sync.json)
  Description: This flow imports records from Airtable and converts them into leads in Lemlist, using specific credentials for both connections.

- [0756-lemplist-mattermost-email-reply.json](workflows/0756-lemplist-mattermost-email-reply.json)
  Description: This automated flow sends notifications of replies received in a specific Lemplist campaign to a designated Mattermost channel.

- [0757-weather-query-response.json](workflows/0757-weather-query-response.json)
  Description: This automated flow queries a web service to get weather data for a specified city, formats it, and returns it as a response.

- [0758-asana-task-creator.json](workflows/0758-asana-task-creator.json)
  Description: This automated flow queries the Asana API via OAuth2 and processes the result to generate a message showing the permalink of a created task.

- [0759-typeform-api-invoice.json](workflows/0759-typeform-api-invoice.json)
  Description: This flow uses a Typeform trigger to receive responses and uses them as JSON parameters in the APITemplate.io PDF generator.

- [0760-asana-task-creator.json](workflows/0760-asana-task-creator.json)
  Description: This flow allows creating a new task in Asana manually by clicking 'execute'.

- [0761-iss-kafka-positions.json](workflows/0761-iss-kafka-positions.json)
  Description: This automated flow queries the current position of the ISS satellite every minute via the WhereTheIss API and sends the data in real-time to the Kafka topic 'iss-position'.

- [0762-line-chatbot-automations.json](workflows/0762-line-chatbot-automations.json)
  Description: This flow configures automatic processes for LINE Chatbots using n8n Autopilot nodes and passing parameters between them.

- [0763-autopilot-to-airtable-contact.json](workflows/0763-autopilot-to-airtable-contact.json)
  Description: This automated flow automatically imports new contacts from Autopilot to a specific table in Airtable.

- [0764-wise-eur-transfer-flow.json](workflows/0764-wise-eur-transfer-flow.json)
  Description: This automated flow uses the Wise API to create and execute monetary transfers between accounts.

- [0765-wise-transfer-handler.json](workflows/0765-wise-transfer-handler.json)
  Description: This automated flow allows logging transfer details in Airtable when their status changes using the Wise API.

- [0766-demo-batch.json](workflows/0766-demo-batch.json)
  Description: This flow uses the Function node to generate a list of items and then applies SplitInBatches with a batch size of 1 to process them in individual batches, checking if there are pending items.

- [0767-split-batch-test.json](workflows/0767-split-batch-test.json)
  Description: This flow uses a manual trigger to start an execution that generates 10 numerical items and processes them one by one using SplitInBatches, checking if the current index is equal to 5.

- [0768-beber.json](workflows/0768-beber.json)
  Description: This flow gets random drink preparation instructions from TheCocktailDB API and translates them to French using DeepL.

- [0769-sql-query-execution.json](workflows/0769-sql-query-execution.json)
  Description: This automated flow allows executing a SQL query in a Microsoft SQL database via a manual trigger.

- [0770-google-drive-video-upload.json](workflows/0770-google-drive-video-upload.json)
  Description: This automated flow allows uploading videos to Google Drive and immediately uploading them to Instagram, TikTok, and YouTube with a title or description generated by AI (OpenAI). The process includes downloading the video from Google Drive, extracting its audio for analysis with OpenAI, and finally making the necessary HTTP requests to publish on the three social media platforms.

- [0771-google-trends-resumen.json](workflows/0771-google-trends-resumen.json)
  Description: This automated flow extracts data from Google Trends using Bright Data Web Unlocker and processes it with LLM chains (Google Gemini Flash) to generate a structured summary that is then written to a JSON file or sent by email.

- [0772-generador_3d_figurine.json](workflows/0772-generador_3d_figurine.json)
  Description: This flow uses Midjourney to generate base images and GPT-4o to create orthographic views of 3D characters.

- [0773-slack-birthday-contacts.json](workflows/0773-slack-birthday-contacts.json)
  Description: This automated flow allows a user to get all people from Google Contacts with birthdays on the current day and automatically send birthday reminder messages to a specific Slack channel.

- [0774-coffee-groups-organization.json](workflows/0774-coffee-groups-organization.json)
  Description: This automated flow virtually organizes employees into groups for coffee chats every Monday at 10:00 AM.

- [0775-Email-AI-HLT-System.json](workflows/0775-Email-AI-HLT-System.json)
  Description: This automated flow uses IMAP to receive emails and AI to generate responses, integrating human intervention in the loop for validation.

- [0776-youtube-seo-blog-generator.json](workflows/0776-youtube-seo-blog-generator.json)
  Description: This automated flow allows extracting YouTube video transcripts using Dumpling AI, generating a complete SEO blog post with OpenAI GPT-4o based on that transcript, and sending it as an email along with a generated image.

- [0777-telegram-file-downloader.json](workflows/0777-telegram-file-downloader.json)
  Description: This automated flow downloads and saves new files received via Telegram message to Google Drive.

- [0778-discord-ai-agent.json](workflows/0778-discord-ai-agent.json)
  Description: This automated flow allows a Discord chatbot to maintain contextualized conversations across different channels using advanced memory and integrated tools.

- [0779-rag-movie-recom-qdrant-openai.json](workflows/0779-rag-movie-recom-qdrant-openai.json)
  Description: This automated flow implements an AI chatbot based on RAG to recommend movies using Qdrant as vector storage and OpenAI for embeddings and interaction.

- [0780-milvus-paul-graham-essays.json](workflows/0780-milvus-paul-graham-essays.json)
  Description: This flow allows creating a knowledge base with OpenAI embeddings from recent Paul Graham essays, storing the vectors in a Milvus collection.

- [0781-line-chatbot-automatic-reply.json](workflows/0781-line-chatbot-automatic-reply.json)
  Description: This automated flow allows a LINE bot to automatically respond to messages received via webhooks, confirming their receipt. Additionally, it supports manually scheduled message sending using a specific user ID.

- [0782-telegram-chatbot-sessions.json](workflows/0782-telegram-chatbot-sessions.json)
  Description: This automated flow allows a Telegram chatbot to manage multiple conversations while maintaining memory and history per session using Google Sheets.

- [0783-sql-email-query-generator.json](workflows/0783-sql-email-query-generator.json)
  Description: This flow translates questions about emails into SQL queries and executes them against the database.

- [0784-ai-meeting-tool.json](workflows/0784-ai-meeting-tool.json)
  Description: This automated flow allows an AI assistant to manage meeting transcripts and perform automated actions like creating Google Calendar events for follow-up.

- [0785-typeform-feedback.json](workflows/0785-typeform-feedback.json)
  Description: This flow processes positive responses from a Typeform form and automatically adds them to a Notion table while creating a Trello card and notifying on Slack.

- [0786-telegram-groq-llava.json](workflows/0786-telegram-groq-llava.json)
  Description: This automated flow allows receiving an image via Telegram, converting it to base64, and sending it to the GROQ LLAVA V1.5-7B model to get its description.

- [0787-n8n-ai-demo-multifunction.json](workflows/0787-n8n-ai-demo-multifunction.json)
  Description: This automated flow uses the n8n platform to build a multifunctional AI system that includes PDF processing via embeddings and text splitting, as well as a chatbot with document-based QA using the GPT-4o model. It also integrates functionality for scheduling appointments.

- [0789-telegram-ai-chat.json](workflows/0789-telegram-ai-chat.json)
  Description: This automated flow allows a Telegram chatbot to maintain contextualized conversations, answer questions, and generate images when users request it.

- [0790-amazon-ads-optimization-flow.json](workflows/0790-amazon-ads-optimization-flow.json)
  Description: This automated flow analyzes Amazon Ads reports stored in Google Drive, using AI to generate detailed recommendations on bidding strategies, tactical optimization, and budget scaling.

- [0791-ai-wordpress-summary.json](workflows/0791-ai-wordpress-summary.json)
  Description: This automated flow generates and adds an AI summary to the beginning of WordPress articles using OpenAI, checks if one already exists to avoid duplicates, updates the page, and saves the data in Google Sheets.

- [0792-line-chatbot-memory-search.json](workflows/0792-line-chatbot-memory-search.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using buffer memory, integrating web search capability with SerpAPI and the GPT-4o-mini language model.

- [0794-fireflies-ai-agent-tasks-notification.json](workflows/0794-fireflies-ai-agent-tasks-notification.json)
  Description: This automated flow captures meeting transcripts in Fireflies.ai and uses an OpenAI-based AI agent to generate tasks in Airtable based on key meeting points. Additionally, it sends specific notifications to clients about their pending items via Gmail if relevant and schedules Google Calendar events if follow-up calls are required.

- [0795-realtime-meeting-transcriber.json](workflows/0795-realtime-meeting-transcriber.json)
  Description: This flow automates real-time meeting transcription using Recall.ai and integrates the generated notes with an OpenAI chatbot for insights.

- [0796-n8n-reAct-scraper.json](workflows/0796-n8n-reAct-scraper.json)
  Description: This flow uses a ReAct AI agent with the HTTP_Request_Tool to extract and process HTML content via HTTP requests, applying limitations on page length and simplifying it according to parameters.

- [0797-line-chatbot-memory.json](workflows/0797-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation with user memory using cache storage.

- [0798-ai-chat-with-supabase-documents.json](workflows/0798-ai-chat-with-supabase-documents.json)
  Description: This automated flow allows an AI chatbot to process PDF and text documents stored in Supabase, generate vector embeddings with OpenAI, and create an interactive knowledge base for file queries.

- [0799-supabase-chat-ai.json](workflows/0799-supabase-chat-ai.json)
  Description: This automated flow allows a chatbot to interact conversationally with a PostgreSQL database hosted on Supabase, executing SQL queries based on user requests.

- [0800-search-console-ai-agent.json](workflows/0800-search-console-ai-agent.json)
  Description: This automated flow allows a chatbot to interact with search engine data using Google Search Console API tools, OpenAI, and store conversation history in a PostgreSQL database.

- [0801-ai-agent-weather-wiki.json](workflows/0801-ai-agent-weather-wiki.json)
  Description: This automated flow allows an AI chatbot to answer questions about current weather and general data using Wikipedia tools, storing the conversation in memory to maintain context.

- [0802-google-calendar-ai-agent.json](workflows/0802-google-calendar-ai-agent.json)
  Description: This automated flow allows a Google Calendar assistant to interact with users via chat to create events or retrieve data, using the OpenAI API and maintaining conversational context.

- [0803-n8n-hr-cv-automation.json](workflows/0803-n8n-hr-cv-automation.json)
  Description: This automated flow analyzes candidate resumes by extracting and summarizing key data using AI models.

- [0804-ai-agent-hacker-news.json](workflows/0804-ai-agent-hacker-news.json)
  Description: This automated flow allows an AI chatbot to maintain a contextualized conversation using custom tools. In this specific case, the agent uses a workflow to get and process data about the most popular articles on Hacker News.

- [0805-conversational-ai-search.json](workflows/0805-conversational-ai-search.json)
  Description: This automated flow allows a chatbot to maintain contextualized conversations using window memory and integrating tools for web search.

- [0806-stock-fundamental-ai-analyzer.json](workflows/0806-stock-fundamental-ai-analyzer.json)
  Description: This automated flow analyzes fund data using OpenAI embeddings, LangChain processing, and vector storage in Qdrant to answer questions about fundamental stock analysis.

- [0807-analisis-sentimiento-feedback.json](workflows/0807-analisis-sentimiento-feedback.json)
  Description: This automated flow allows collecting customer feedback in a Google sheet, analyzing it with AI to detect sentiment, and then integrating it along with other form data into the same sheet.

- [0808-airtable-dynamic-prompts-llm.json](workflows/0808-airtable-dynamic-prompts-llm.json)
  Description: This automated flow allows the user to generate and maintain a dynamic field schema in an Airtable table via webhooks, optimizing updates with LLM only when necessary.

- [0809-baserow-pdf-extractor.json](workflows/0809-baserow-pdf-extractor.json)
  Description: This automated flow allows a user to extract data from PDFs using dynamic prompts in a Baserow table.

- [0810-strava-coaching.json](workflows/0810-strava-coaching.json)
  Description: This flow analyzes Strava data to offer personalized sports coaching in triathlon.

- [0811-jina-scraper-book-extractor.json](workflows/0811-jina-scraper-book-extractor.json)
  Description: This flow uses Jina.ai to access and extract book data from web scraping, processes it with OpenAI, and saves the result in Google Sheets.

- [0812-social_media_caption_generator.json](workflows/0812-social_media_caption_generator.json)
  Description: This automated flow creates social media captions based on a brief presentation and target audience data, storing everything directly in an Airtable record.

- [0813-voice-ai-chat.json](workflows/0813-voice-ai-chat.json)
  Description: This automated flow integrates Webhook for real-time voice inputs, contextualized memory management with models like Google Gemini and ElevenLabs.

- [0814-elevenlabs-voice-rag-chatbot.json](workflows/0814-elevenlabs-voice-rag-chatbot.json)
  Description: This automated flow allows an ElevenLabs chatbot to maintain voice conversations with customers using vectorized documents and contextualized memory.

- [0815-ai-company-researcher-sales.json](workflows/0815-ai-company-researcher-sales.json)
  Description: This automated flow uses AI along with web tools like SERPAPI or ScrapingBee to research company properties such as domain, LinkedIn URL, market type (B2B/B2C), cheapest plans, API, and free trials, then updates the data in Google Sheets.

- [0816-youtube-trend-finder-n8n.json](workflows/0816-youtube-trend-finder-n8n.json)
  Description: This automated flow uses AI to analyze data from trending YouTube videos based on a specific niche.

- [0817-erp_lead_automation.json](workflows/0817-erp_lead_automation.json)
  Description: This automated flow uses AI to manage new customer opportunities (leads) from ERPNext, analyzing their notes and generating email notifications to relevant contacts if they are related to products or services.

- [0818-ai-summary-wordpress.json](workflows/0818-ai-summary-wordpress.json)
  Description: This automated flow analyzes and classifies WordPress content to determine if it already includes an AI-generated summary, generating new summaries with GPT-4o-mini when necessary.

- [0819-erpnext-candidate-automation.json](workflows/0819-erpnext-candidate-automation.json)
  Description: This automated flow allows integrating ERPNext webhooks to manage candidate applications via AI analysis (like Google Gemini) and update their statuses based on the result.

- [0820-historias-para-ninos.json](workflows/0820-historias-para-ninos.json)
  Description: This automated flow creates stories in English for children, illustrates them visually, and sends them as text and audio images via Telegram.

- [0821-email-ai-auto-responder.json](workflows/0821-email-ai-auto-responder.json)
  Description: This automated flow analyzes incoming emails using DeepSeek and OpenAI to summarize them and identify the topic. If the classification detects it is a request about the company, a professionally structured response is generated based on information from Qdrant.

- [0822-email-approval-ia.json](workflows/0822-email-approval-ia.json)
  Description: This flow automates the processing of incoming emails, generates summaries and responses using RAG and AI, requires Yes/No approval before sending them.

- [0823-ai-monitoring-slack.json](workflows/0823-ai-monitoring-slack.json)
  Description: This automated flow monitors articles of interest in real-time using multiple RSS feeds, classifies their relevance with AI, and generates formatted summaries for efficient management.

- [0824-rag-financial-report-gen.json](workflows/0824-rag-financial-report-gen.json)
  Description: This flow uses the RAG system to analyze corporate profitability reports based on historical documents stored as embeddings in Pinecone. It processes information using Google Gemini and OpenAI models, synthesizes data with a specialized agent, and integrates everything into a markdown report that is automatically saved in Google Docs.

- [0825-ai-social-media-amplifier.json](workflows/0825-ai-social-media-amplifier.json)
  Description: This automated flow allows sharing featured GitHub discussions that appear on Hacker News, generating and sending formatted posts for Twitter and LinkedIn.

- [0826-ai-woocommerce-support-agent.json](workflows/0826-ai-woocommerce-support-agent.json)
  Description: This automated flow implements an AI assistant with n8n and WooCommerce to manage customer inquiries about their orders, ensuring privacy through email encryption and integrating functions like DHL.

- [0827-workflow-retriever-qa.json](workflows/0827-workflow-retriever-qa.json)
  Description: This automated flow allows querying any data source by retrieving existing workflows.

- [0828-podcast-consciencia-ai.json](workflows/0828-podcast-consciencia-ai.json)
  Description: This flow analyzes podcasts about the philosophy of mind, extracts key information, and performs Wikipedia searches to elaborate improved summaries.

- [0829-news-monitor-trello.json](workflows/0829-news-monitor-trello.json)
  Description: This automated flow monitors multiple RSS feeds (Artificial Intelligence Blog, Testing Catalog, and MarkTechPost), filters articles based on date, transforms results to Markdown format, and posts comments on Trello while sending email notifications.

- [0830-assistant-travel-agency.json](workflows/0830-assistant-travel-agency.json)
  Description: This automated flow allows creating an OpenAI assistant from the content of documents stored in Google Drive and maintaining a contextualized conversation for the travel agency.

- [0831-monitor-usdt-balance.json](workflows/0831-monitor-usdt-balance.json)
  Description: This flow automatically monitors the ERC-20 USDT balance stored in a wallet, notifying Telegram every 5 minutes if it has changed or not.

- [0832-wordpress-ai-content-generator.json](workflows/0832-wordpress-ai-content-generator.json)
  Description: This automated flow creates WordPress articles at different reading levels using language models. It processes rewritten content, validates that they have a title and introduction, generates related images, and saves drafts in Google Drive.

- [0833-n8n-nodos-unicos.json](workflows/0833-n8n-nodos-unicos.json)
  Description: This flow analyzes a unique blueprint file with node definitions for n8n.

- [0834-code-review-ai.json](workflows/0834-code-review-ai.json)
  Description: This automated flow allows the repository's Code Review tool to interact with integrated systems that handle pull requests, generating intelligent comments based on detected differences.

- [0835-analisis-papers-hf.json](workflows/0835-analisis-papers-hf.json)
  Description: This automated flow extracts and analyzes academic articles from the Hugging Face platform using artificial intelligence (OpenAI) and stores the result in a structured format in Notion.

- [0836-email-phishing-analysis.json](workflows/0836-email-phishing-analysis.json)
  Description: This automated flow analyzes and classifies suspicious emails using ChatGPT to determine if they are fraudulent or not. Gmail and Outlook alerts capture incoming messages, which are then processed with AI to assess their nature.

- [0837-analisis-retroalimentacion-mattermost.json](workflows/0837-analisis-retroalimentacion-mattermost.json)
  Description: This flow analyzes the sentiment of a feedback comment using the Google Cloud Natural Language API and, if positive (score > 0), sends a notification to the specified Mattermost channel.

- [0838-typeform-mattermost-sentimiento-negativo.json](workflows/0838-typeform-mattermost-sentimiento-negativo.json)
  Description: This flow analyzes the sentiment of comments in Typeform forms and sends only those with a negative rating to a Mattermost channel.

- [0839-email-phishing-analysis.json](workflows/0839-email-phishing-analysis.json)
  Description: This automated flow analyzes suspicious email messages detected in Gmail and Outlook, using ChatGPT Vision to evaluate their visual appearance and indicate if they might be phishing attempts. The results are formatted and stored in Jira.

- [0841-bright-data-gemini-hotel-summarizer.json](workflows/0841-bright-data-gemini-hotel-summarizer.json)
  Description: This automated flow extracts hotel data from Bing Copilot using the Bright Data API and uses Google Gemini AI to format it into JSON structure and generate concise summaries.

- [0842-telegram-ai-assistant.json](workflows/0842-telegram-ai-assistant.json)
  Description: This automated flow allows Angie to maintain real-time conversational context while interacting with users via Telegram (both text messages and audio files) and access their emails, calendar, and Baserow-based data.

- [0843-spy-intelligence-tool.json](workflows/0843-spy-intelligence-tool.json)
  Description: This automated flow allows a LINE chatbot to perform automated spy intelligence. It periodically (daily) scans information from a URL extracted by AI and compares old content with current content to send email alerts if there are significant differences.


- [0845-openai-image-generator.json](workflows/0845-openai-image-generator.json)
  Description: This workflow allows generating images using the OpenAI API based on inputs provided via forms.

- [0846-workflow-pinecone-openai.json](workflows/0846-workflow-pinecone-openai.json)
  Description: This flow loads documents from Google Drive into a Pinecone vector store using OpenAI embeddings to then allow information retrieval via question-answer chains.

- [0847-wp-ai-categorizer.json](workflows/0847-wp-ai-categorizer.json)
  Description: This flow automates the categorization of posts in WordPress using OpenAI language models.

- [0848-competitor-analysis-n8n.json](workflows/0848-competitor-analysis-n8n.json)
  Description: This automated flow analyzes databases and webinars using scraping and artificial intelligence tools to gather structured information about competitors.

- [0849-passport-photo-validation.json](workflows/0849-passport-photo-validation.json)
  Description: This automated flow verifies the validity of passport photos according to British government guidelines using computer vision models in n8n.

- [0852-strapi-testimonials-automation.json](workflows/0852-strapi-testimonials-automation.json)
  Description: This automated flow seeks to collect and analyze positive testimonials in a Strapi system by integrating with Twitter.

- [0853-fine-tuning-openai-with-drive.json](workflows/0853-fine-tuning-openai-with-drive.json)
  Description: This automated flow allows performing a complete fine-tuning process on OpenAI models using JSONL files hosted on Google Drive.

- [0855-eliminar-fondos-google-drive.json](workflows/0855-eliminar-fondos-google-drive.json)
  Description: This flow automatically removes backgrounds from images in Google Drive using the Photoroom API.

- [0856-youtube-x-automation.json](workflows/0856-youtube-x-automation.json)
  Description: This automated flow seeks to promote the latest videos from a specific YouTube channel on X, verifying that they comply with character limitations and maintaining a record in Google Sheets.

- [0857-calendar-event-automation.json](workflows/0857-calendar-event-automation.json)
  Description: This automated flow creates events in Google Calendar from data inserted into a Google Sheets spreadsheet.

- [0858-tiktok-downloader-json.json](workflows/0858-tiktok-downloader-json.json)
  Description: Automatic to download TikTok videos without the watermark sticker

- [0859-telegram-gmail-alertas.json](workflows/0859-telegram-gmail-alertas.json)
  Description: This flow automates sending filtered Gmail emails to a Telegram chat, notifying only those with subjects containing specific keywords like 'Urgent' or 'Server Down'.

- [0861-line-chatbot-memory.json](workflows/0861-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation with its users by using memory via the service's REST API.

- [0863-weather-slack-integration.json](workflows/0863-weather-slack-integration.json)
  Description: This automated flow allows receiving locations in Slack messages, searching their coordinates using OpenStreetMap, and then getting the local weather forecast via the National Weather Service API to send the formatted information as text in the same Slack channel.

- [0864-n8n_leaderboard_stats.json](workflows/0864-n8n_leaderboard_stats.json)
  Description: This automated flow analyzes n8n user metrics to generate a detailed and Markdown-formatted report, including ranking of most popular workflows and creator statistics.

- [0865-bamboo-hr-ai-chatbot.json](workflows/0865-bamboo-hr-ai-chatbot.json)
  Description: This flow is an AI-powered chatbot for answering questions about corporate policies, benefits, and labor procedures using documents uploaded from BambooHR as an information source. It implements vector search with OpenAI, contextual memory (window buffer memory), and employee lookup tools that allow AI to search for internal contacts or departments to facilitate responses.


- [0867-linea_inventario_agendador.json](workflows/0867-linea_inventario_agendador.json)
  Description: This automated flow allows an n8n chatbot to schedule meetings by checking availability in Google Calendar and generating 30-minute time slots between working hours from Monday to Friday.

- [0868-n8n-deployer.json](workflows/0868-n8n-deployer.json)
  Description: This flow allows importing and configuring a workflow in n8n using JSON files hosted in a specific Google Drive folder.

- [0869-bitrix-chatbot-webhook.json](workflows/0869-bitrix-chatbot-webhook.json)
  Description: This automated flow allows Bitrix24 to process chatbot events via webhooks, validate tokens, and send appropriate responses.

- [0870-chatbot-salud-ia.json](workflows/0870-chatbot-salud-ia.json)
  Description: This automated flow allows a chatbot to maintain a contextualized conversation about health donation plans, using persistent memory and integration with external APIs to search for specific information.

- [0871-line-chatbot-memory.json](workflows/0871-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation with users by processing messages in both text and images, extracting relevant information about account statements and personal data, and then inserting it into Google Sheets.

- [0872-estudio-descomposicion-documents-n8n.json](workflows/0872-estudio-descomposicion-documents-n8n.json)
  Description: This automated flow allows the system to process documents uploaded in a specified directory, split them into text blocks, vectorize their content, and then generate different types of study materials like guides or timelines using AI language models. Finally, it exports these generated files along with the original.

- [0873-opensea-marketplace-agent.json](workflows/0873-opensea-marketplace-agent.json)
  Description: This automated flow allows a chatbot to interact with the OpenSea API to get information about listings, offers, and NFT orders in different collections and identifiers.

- [0874-tax-code-assistant-qdrant-mistral-openai.json](workflows/0874-tax-code-assistant-qdrant-mistral-openai.json)
  Description: This automated flow allows an AI chatbot to answer questions about the Texas state tax code using Mistral.ai embeddings to generate vectors and Qdrant to efficiently store and retrieve documents, optimizing large file management through strategic decompression.

- [0875-assistente_viajes_actualizado.json](workflows/0875-assistente_viajes_actualizado.json)
  Description: This automated flow allows creating an OpenAI assistant from a PDF document stored in Google Drive, maintaining a contextualized conversation via buffer memory and allowing interaction via chat.

- [0876-image-search-workflow.json](workflows/0876-image-search-workflow.json)
  Description: This automated flow allows searching for images based on detected objects using artificial intelligence, CDN, and ElasticSearch to efficiently store and query results.

- [0877-rag-peliculas-recomendacion-qdrant.json](workflows/0877-rag-peliculas-recomendacion-qdrant.json)
  Description: This automated flow allows a chatbot to recommend movies using Qdrant vector storage and embeddings generated with OpenAI for user query analysis.

- [0879-whatsapp-sales-agent.json](workflows/0879-whatsapp-sales-agent.json)
  Description: This automated flow allows a WhatsApp chatbot to act as a sales assistant for Yamaha Powered speakers. The bot responds to text messages by querying a vector database with the catalog, maintains conversational memory per customer, and automatically rejects non-text processing.

- [0880-telegram-schedule-ai.json](workflows/0880-telegram-schedule-ai.json)
  Description: This flow allows a Telegram chatbot to interact with AI using conversational memory and calendar data extracted from a Google sheet, sending responses to both the n8n application and the Telegram user.

- [0881-github-trending-scraping.json](workflows/0881-github-trending-scraping.json)
  Description: This flow allows extracting the 13 most popular repositories from GitHub Trends, storing information like author, title, language, and description for monitoring or analysis.

- [0882-hubspot-chatgpt-integration.json](workflows/0882-hubspot-chatgpt-integration.json)
  Description: This automated flow allows a HubSpot chatbot to integrate conversations with the OpenAI Assistant API to maintain context and generate responses.

- [0883-n8n-ai-categorize-wordpress.json](workflows/0883-n8n-ai-categorize-wordpress.json)
  Description: This automatic template uses AI to assign a single category to multiple WordPress posts based on their title.

- [0884-auto-post-sociales-n8n.json](workflows/0884-auto-post-sociales-n8n.json)
  Description: This automated flow, triggered daily at 10:00 PM via a scheduled trigger, collects information from a Google spreadsheet (URL and video description) and integrates with the Blotato API to publish content on multiple social platforms without manual intervention.

- [0885-zammad-roles-sync.json](workflows/0885-zammad-roles-sync.json)
  Description: This automated flow updates all user roles in Zammad for active users based on a predefined list of default roles.

- [0886-workflow-doc-analyzer.json](workflows/0886-workflow-doc-analyzer.json)
  Description: This automated flow analyzes documents uploaded via form, converts markdown to HTML, and saves the results in a vector database to feed a chatbot.

- [0887-horario-tareas-n8n.json](workflows/0887-horario-tareas-n8n.json)
  Description: This flow automates the activation and deactivation of a workflow in n8n at 08:00 and 20:00 daily.

- [0888-webflow-discord-form.json](workflows/0888-webflow-discord-form.json)
  Description: This automated flow creates a Discord channel for each Webflow web form and sends the submitted responses to that channel.

- [0889-openai-chatbot-memory-api.json](workflows/0889-openai-chatbot-memory-api.json)
  Description: This flow allows an OpenAI chatbot to maintain conversations with persistent memory in PostgreSQL and access external information via APIs.

- [0890-Google_Sheet_AI_Interface.json](workflows/0890-Google_Sheet_AI_Interface.json)
  Description: This automated flow allows a chatbot to interact with a Google sheet using custom functions, optimizing data query and management.

- [0891-rag-github-api-chatbot.json](workflows/0891-rag-github-api-chatbot.json)
  Description: This flow uses the RAG (Retrieval-Augmented Generation) pattern with OpenAI and Pinecone to create a chatbot that answers queries about GitHub API documentation.

- [0892-ollama-n8n-chat.json](workflows/0892-ollama-n8n-chat.json)
  Description: This flow allows interacting with local language models (managed by Ollama) via a chat interface.

- [0893-chat-ai-contexto.json](workflows/0893-chat-ai-contexto.json)
  Description: This automated flow allows maintaining a contextualized conversation with the OpenAI assistant by managing previous messages.

- [0894-telegram-gpt-ai-agent.json](workflows/0894-telegram-gpt-ai-agent.json)
  Description: This automated flow allows a Telegram chatbot to process incoming user messages using the OpenAI GPT model and send an emoji-enriched response.

- [0895-chat-pdf-ai-citas.json](workflows/0895-chat-pdf-ai-citas.json)
  Description: This automated flow allows a chatbot to analyze PDF documents using OpenAI embeddings and retrieve relevant information with exact citations when queried.

- [0896-postgres-chat-ai.json](workflows/0896-postgres-chat-ai.json)
  Description: This flow allows an AI chatbot to interact with a PostgreSQL database using tools to execute SQL queries and maintain context.

- [0897-telegram-schedule-bot.json](workflows/0897-telegram-schedule-bot.json)
  Description: This flow allows a chatbot to interact with the event calendar from a Google spreadsheet using Telegram.

- [0898-gitlab-chatgpt-review.json](workflows/0898-gitlab-chatgpt-review.json)
  Description: This automated flow uses ChatGPT to review code changes detected in a GitLab merge request (MR), analyzing the differences between the original and modified code. It then integrates these reviews with the GitLab API to comment directly on the changes.

- [0899-yelp-summary.json](workflows/0899-yelp-summary.json)
  Description: This automated flow allows extracting and summarizing business reviews on Yelp using Bright Data web services for data collection, followed by structured analysis with Google Gemini.

- [0900-n8n-lemlist-reply-classification.json](workflows/0900-n8n-lemlist-reply-classification.json)
  Description: Classifies Lemplist responses with OpenAI and automates management, sending alerts to Slack or unsubscribing interested parties.

- [0901-linear-bugs-classifier.json](workflows/0901-linear-bugs-classifier.json)
  Description: This automated flow classifies new bugs in Linear using OpenAI GPT-4 to determine the correct team based on a predefined list of responsibilities and updates or notifies if a suitable destination is not found.

- [0902-baserow-markdown-sync.json](workflows/0902-baserow-markdown-sync.json)
  Description: This automated flow allows synchronizing and updating records in Baserow where the video description is in Markdown format. It first checks if there is a single record or multiple, converts each description to HTML while maintaining the original data structure, and logs in via a webhook.

- [0903-bitrix24-chatbot-workflow.json](workflows/0903-bitrix24-chatbot-workflow.json)
  Description: This automated flow allows Bitrix24 to process chatbot-related events (like messages and installations) via webhooks, perform token validations, and respond appropriately.

- [0904-line-chatbot-memory.json](workflows/0904-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using persistent memory.

- [0905-whatsapp-chatbot-rag.json](workflows/0905-whatsapp-chatbot-rag.json)
  Description: This automated flow configures an AI-powered WhatsApp chatbot that uses RAG (Retrieval-Augmented Generation) with OpenAI to maintain contextualized conversations.

- [0906-gmail-reply-drafts-openai-assistant.json](workflows/0906-gmail-reply-drafts-openai-assistant.json)
  Description: This automated flow allows Gmail to reply to messages with the help of OpenAI Assistant, creating draft responses based on email content and removing the triggering labels after composing the message.

- [0908-ai-interviews-n8n.json](workflows/0908-ai-interviews-n8n.json)
  Description: This automated flow with n8n allows conducting conversational interviews with an AI agent that dynamically asks questions and records responses in Redis, using forms to capture information. Responses are saved in Google Sheets.

- [0909-openai-tts-manual.json](workflows/0909-openai-tts-manual.json)
  Description: This flow allows converting text to speech via the OpenAI API with a manual process.

- [0910-url-markdown-batch.json](workflows/0910-url-markdown-batch.json)
  Description: This flow processes URLs in batches of 10, uses the Firecrawl API to convert HTML content to markdown and extract links, managing provider limitations.

- [0911-google-calendar-telegram-eventos.json](workflows/0911-google-calendar-telegram-eventos.json)
  Description: This automated flow sends a Telegram notification when a new event is created in Google Calendar. It extracts key details like event name, description, location, start and end date/time, and sends it to the specified chat.

- [0912-adaptive-rag-strategy.json](workflows/0912-adaptive-rag-strategy.json)
  Description: This flow analyzes and classifies queries into specific categories (Factual, Analytical, Opinion, or Contextual) to apply adaptive retrieval and artificial intelligence strategies that optimize obtaining relevant information.

- [0913-google-maps-leads-generator.json](workflows/0913-google-maps-leads-generator.json)
  Description: This automated flow uses the Google Maps API to search for places based on specific categories and postal codes, extracting relevant data and inserting it into a Google Sheets spreadsheet with anti-duplicate control mechanisms and exponential error handling.

- [0914-website-chatbot-n8n.json](workflows/0914-website-chatbot-n8n.json)
  Description: This automated flow allows an n8n chatbot to maintain conversations with customers, check calendar availability via Microsoft Outlook API, and send structured responses. The AI agent uses the GPT-4o model to process queries and make decisions about appointments or message sending.

- [0915-google_analytics_report_workflow.json](workflows/0915-google_analytics_report_workflow.json)
  Description: This flow analyzes Google Analytics data for the last 7 days and compares it with the same period of the previous year, then uses AI to format it into a detailed HTML report sent by email. Additionally, it transforms this data into plain text for Telegram and optionally shares it.

- [0916-twitter-profile-banner-generator.json](workflows/0916-twitter-profile-banner-generator.json)
  Description: This automated flow allows creating a dynamic Twitter banner by combining the avatar images of the most recent followers with a background image, using the OAuth1.0 API.

- [0917-email-drafting-fastmail-openai.json](workflows/0917-email-drafting-fastmail-openai.json)
  Description: This automated flow analyzes unread emails from an IMAP mailbox via the Fastmail API and generates responses using models like GPT-4, saving the drafts in a specific folder.

- [0918-humantic-profile-management.json](workflows/0918-humantic-profile-management.json)
  Description: This automated flow allows creating, updating, and getting a Humantic AI profile using a LinkedIn URL as the initial input.

- [0919-slack-ai-bot.json](workflows/0919-slack-ai-bot.json)
  Description: This automated flow processes Slack messages via an AI agent based on Google Gemini, maintaining contextualized conversations with window memory.

- [0920-squarespace-orders-to-sheets.json](workflows/0920-squarespace-orders-to-sheets.json)
  Description: This automated flow collects all orders from a Squarespace store and automatically updates a Google Sheets file.

- [0921-n8n-flujo-langchain.json](workflows/0921-n8n-flujo-langchain.json)
  Description: This flow allows executing two types of interactions: one to get responses with custom LLM chains and another that uses a chat agent integrated with WikipediaQueryRun as a tool.

- [0922-trustpilot-customer-insights.json](workflows/0922-trustpilot-customer-insights.json)
  Description: This automated flow extracts customer review information from TrustPilot using Qdrant to store vectors and LLMs to generate insights on general sentiment and identify recurring themes.

- [0923-customer-support-ticketing.json](workflows/0923-customer-support-ticketing.json)
  Description: This automated flow monitors a specific Slack channel (n8n-tickets) for messages with the ticket emoji. When it detects a new one, it queries Linear to see if a corresponding ticket already exists and, if not found, uses ChatGPT to generate a descriptive title, a summary description, suggestions for resolving the issue, and determine its priority based on the user's message.

- [0924-cv-multimodal-ai.json](workflows/0924-cv-multimodal-ai.json)
  Description: This workflow uses multimodal vision with AI to analyze PDF resumes and assess if candidates are suitable for an interview.

- [0925-cv-screening-openai.json](workflows/0925-cv-screening-openai.json)
  Description: This automated flow analyzes resumes in PDF format using the OpenAI API, creating structured evaluations with a percentage score and detailed summaries.

- [0926-docker_n8n_api_workflow.json](workflows/0926-docker_n8n_api_workflow.json)
  Description: This automated flow manages the creation and administration of Docker containers via an API with basic authentication.

- [0927-digital-ocean-upload-form.json](workflows/0927-digital-ocean-upload-form.json)
  Description: This flow allows uploading files to Digital Ocean Spaces via a form and displaying the link after the upload.

- [0928-n8n_workflow_stats.json](workflows/0928-n8n_workflow_stats.json)
  Description: This automated flow allows users to get detailed statistics about n8n workflows, including information per node, global, tags, webhooks, and more. It uses advanced JS functions like JMESPath for efficient processing.

- [0929-analisis_comentarios_youtube.json](workflows/0929-analisis_comentarios_youtube.json)
  Description: This flow analyzes YouTube video comments using the Google API and GPT-4o-mini to generate a detailed report with insights on audience trends, highlighted topics, and practical recommendations.

- [0930-linkedin-data-processing.json](workflows/0930-linkedin-data-processing.json)
  Description: This automated flow uses Bright Data's MCP to extract Markdown information from LinkedIn profiles or companies, processes this data with Google Gemini (PaLM model) which converts it to JSON and incorporates deep context to generate detailed stories, and finally writes the output to local files.

- [0931-calendar-gemini-slack-summarization.json](workflows/0931-calendar-gemini-slack-summarization.json)
  Description: This automated flow extracts events from Google Calendar to generate daily summaries using the Gemini AI model and shares them in a Slack channel.

- [0932-podcast-summary-flow.json](workflows/0932-podcast-summary-flow.json)
  Description: This automated flow allows users to receive a daily summary of top podcasts by specific genre via transcription and artificial intelligence.

- [0933-telegram_baserow_ai_assistant.json](workflows/0933-telegram_baserow_ai_assistant.json)
  Description: This automated flow allows a chatbot to interact with Telegram by receiving messages (voice, text, or image), managing them with tools like OpenAI to transcribe voice and analyze images, maintaining contextual memory using Baserow, and then responding appropriately in each modality.

- [0934-ai-logo-sheet-extractor.json](workflows/0934-ai-logo-sheet-extractor.json)
  Description: This automated flow allows extracting information from images showing logo tables, identifying tools and their attributes to save them in Airtable.

- [0935-uber_eats_expense_tracker.json](workflows/0935-uber_eats_expense_tracker.json)
  Description: This automated flow searches Gmail emails with the specific subject '透過 Uber Eats 系统送出的订单', extracts information like price, store, date, and time from the email content using regular expressions, and then sends this formatted information to Slack via blocks. It also provides a direct link to integrate with Moze expense tracker.

- [0936-ai-grant-tracker.json](workflows/0936-ai-grant-tracker.json)
  Description: This automated flow allows filtering and analyzing grant opportunities related to AI on grants.gov. It uses nodes to eliminate duplicates via a tracking system, requests detailed information about each grant through the grants.gov API, and incorporates OpenAI generative models to determine eligibility and facilitate the process.

- [0937-detect-hallucinations-ollama.json](workflows/0937-detect-hallucinations-ollama.json)
  Description: This flow analyzes texts to identify incorrect statements using a specialized Ollama model called bespoke-minicheck. It processes the text by splitting it into sentences while maintaining structural elements like dates and lists, then extracts 'facts' for verification via LLM chains.

- [0938-telegram-moderador.json](workflows/0938-telegram-moderador.json)
  Description: This automated flow detects profane language in Telegram messages and responds with a warning message when the score exceeds 0.7.

- [0939-gmail-gemini-email-management.json](workflows/0939-gmail-gemini-email-management.json)
  Description: This automated flow uses Google Gemini AI along with Gmail OAuth2 to classify emails using a machine learning model. Emails are evaluated based on numerical confidences (0-1) where values above 0.5 indicate the email is unacceptable, marketing, or spam, and are automatically deleted via the Gmail API. A Telegram notification is sent when an email is deleted, not otherwise, or if errors occur.

- [0940-n8n_discord_ai_categorizer.json](workflows/0940-n8n_discord_ai_categorizer.json)
  Description: This automated flow categorizes user requests using OpenAI GPT-4, generating a JSON structure to send them via Webhook to different departments in Discord according to their classification.

- [0941-techradar-ai-agent.json](workflows/0941-techradar-ai-agent.json)
  Description: This automated flow manages corporate technology for three companies, keeping records updated in a SQL database and Pinecone vector storage. A cron job runs monthly to synchronize data from Google Sheets, deleting old records.

- [0942-pdf2blog-automatizado.json](workflows/0942-pdf2blog-automatizado.json)
  Description: This automated flow allows converting PDF files into blogs by extracting text, processing with an OpenAI API, and publishing to Ghost if the results are valid.

- [0943-Telegram-Buffered-Messages.json](workflows/0943-Telegram-Buffered-Messages.json)
  Description: This automated flow allows a Telegram chatbot to combine messages received at short intervals using a Supabase database and maintain contextualized memory to generate cohesive responses.

- [0944-obsidian-email-sender.json](workflows/0944-obsidian-email-sender.json)
  Description: This automated flow allows sending emails from Obsidian using webhooks, correctly processing attachments via base64 encoding and adding sender information.

- [0945-convertapi-merge.json](workflows/0945-convertapi-merge.json)
  Description: This automated flow downloads two PDF documents from CDN using ConvertPDF API authentication and then merges them into a single file for saving.

- [0946-dynamically_switch_llms_customer_support.json](workflows/0946-dynamically_switch_llms_customer_support.json)
  Description: This n8n flow dynamically selects and uses different language models (like OpenAI) based on an index to generate versatile responses and iterate until one meets specified criteria, such as polite tone.

- [0947-trustpilot_reviews_google_sheets.json](workflows/0947-trustpilot_reviews_google_sheets.json)
  Description: This n8n flow automates the extraction of Trustpilot reviews to Google Sheets via paginated scraping and data transformation.

- [0948-glassdoor-resume-empresa.json](workflows/0948-glassdoor-resume-empresa.json)
  Description: This flow automates the extraction of company data from Glassdoor using Bright Data Web Scraper, splits it for processing with Gemini, and generates a summary.

- [0949-dsp_telegram_tutor.json](workflows/0949-dsp_telegram_tutor.json)
  Description: This automated flow allows a Telegram chatbot to maintain a contextualized conversation on signal processing topics, using tools like Wikipedia and a calculator to solve problems.

- [0950-dsp-ai-tutor.json](workflows/0950-dsp-ai-tutor.json)
  Description: This n8n flow acts as a tutoring assistant for signal processing students, using OpenAI and Google Gemini models to guide them interactively through theoretical explanations, numerical solutions, or memory references.

- [0951-book-scraping-automation.json](workflows/0951-book-scraping-automation.json)
  Description: This automated flow extracts book data from URLs using Dumpling AI, cleans the HTML, and saves the information to a CSV.

- [0952-facturas-ocr-google-drive.json](workflows/0952-facturas-ocr-google-drive.json)
  Description: This automated flow allows automatically recognizing invoices stored in a Google Drive folder (PDF, PNG, or JPG formats) using the OakPDF API. The workflow is activated when there are new files and extracts key data such as issuer name, address, total paid, and specific details to save them structured in Google Sheets.

- [0953-notion-supabase-vector.json](workflows/0953-notion-supabase-vector.json)
  Description: This flow automates storing Notion pages as vectorized documents in a Supabase project using vector columns and OpenAI-generated embeddings.

- [0954-bamboo-hr-ai-chatbot.json](workflows/0954-bamboo-hr-ai-chatbot.json)
  Description: This automated flow allows an HR chatbot to access and interpret information about corporate policies and benefits by integrating with vector storage in Supabase. It also facilitates searches for specific employees or departments for relevant contacts.

- [0956-html-generator.json](workflows/0956-html-generator.json)
  Description: This flow uses OpenAI Structured Output along with n8n to dynamically generate HTML pages based on user requests, using a predefined JSON schema and Tailwind CSS as a framework.

- [0957-noco-kanban-ai-monitoring.json](workflows/0957-noco-kanban-ai-monitoring.json)
  Description: This automated flow analyzes incidents via AI to assign categories and parameters, which are inserted into a NocoDB table. It then periodically checks the status of tasks without excessive notifications.

- [0958-image-caption-overlay.json](workflows/0958-image-caption-overlay.json)
  Description: This automated flow downloads an image using HTTP Request, resizes it for AI optimization, and adds a punny caption generated by Gemini 1.5 Pro.

- [0959-squarespace-backup.json](workflows/0959-squarespace-backup.json)
  Description: This automated flow allows saving Squarespace customizations (injection code) into HTML files within a GitHub repository, maintaining context by domain and performing backups hourly.

- [0960-gitea-backup-workflow.json](workflows/0960-gitea-backup-workflow.json)
  Description: This automated flow verifies and saves n8n workflows to a Git repository hosted on Gitea through change comparison and updates.

- [0961-lead-presentaciones-auto.json](workflows/0961-lead-presentaciones-auto.json)
  Description: This automated flow creates personalized presentations based on lead data by monitoring new files in Google Drive and processing them through Google Sheets and Slides operations to integrate the information.

- [0962-email-ai-assistant.json](workflows/0962-email-ai-assistant.json)
  Description: This automated flow analyzes incoming emails using AI to summarize and generate responses, allowing human review when necessary.

- [0963-copiar-documentos-escaneados-json.json](workflows/0963-copiar-documentos-escaneados-json.json)
  Description: This automated flow copies scanned documents from a server via HTTP to a Nextcloud account.

- [0965-factoid_subscription_service.json](workflows/0965-factoid_subscription_service.json)
  Description: This automated flow uses n8n forms to manage subscriptions to daily, weekly, or surprising educational emails with generative AI models and Airtable storage.

- [0966-email-summary-agent.json](workflows/0966-email-summary-agent.json)
  Description: This automated flow collects emails from the last day and summarizes them with AI to highlight key details, issues, and action instructions, sending a summarized HTML report.

- [0967-comparador-sql.json](workflows/0967-comparador-sql.json)
  Description: This flow compares two SQL datasets based on customer number and year, using an option to handle multiple matches.

- [0968-HR_CV_Evaluation_AI.json](workflows/0968-HR_CV_Evaluation_AI.json)
  Description: This automated flow allows automatically evaluating candidate applications via AI analysis to determine their qualification and suitability for the vacancy, then updating Airtable according to the result.

- [0969-ats-ai-assessment.json](workflows/0969-ats-ai-assessment.json)
  Description: This automated flow processes candidate applications extracted from forms, analyzes their personal data and qualifications using Google Gemini models, assigns experiences by roles using an LLM extractor, evaluates their alignment with specific role descriptions in Notion ATS, generates structured evaluations, and updates records in both Notion and Google Sheets.

- [0970-buffer-chat-twilio-redis.json](workflows/0970-buffer-chat-twilio-redis.json)
  Description: This flow uses Redis to store user messages and Twilio to receive SMS inputs, allowing the AI agent to process multiple linked messages as if they were one after verifying no new pending messages.

- [0972-slack-qualys-shortcut.json](workflows/0972-slack-qualys-shortcut.json)
  Description: This automated flow allows a Slack bot to integrate report creation and scan initiatives with the Qualys system, processing user interactions via webhooks.

- [0973-ai-faq-generator.json](workflows/0973-ai-faq-generator.json)
  Description: This flow uses n8n and language models like ChatGPT to automatically generate complete FAQ content based on provided data.

- [0974-pipedrive-enrichment.json](workflows/0974-pipedrive-enrichment.json)
  Description: This workflow automatically enriches Pipedrive organizational data with information extracted by GPT-4o and sends a Slack notification.

- [0975-airtable-image-analysis.json](workflows/0975-airtable-image-analysis.json)
  Description: This flow automates the analysis of images captured in Airtable to identify product attributes and integrates web information, optimizing inventory management.

- [0976-research-report-gen.json](workflows/0976-research-report-gen.json)
  Description: This automated flow allows generating research reports using OpenAI, Wikipedia, Google Search and sending them via email or Telegram.

- [0977-postgresql-chat-automaton.json](workflows/0977-postgresql-chat-automaton.json)
  Description: This automated flow allows a chatbot to interact with a PostgreSQL database, generating responses based on SQL queries that analyze the requested data.

- [0978-ai-cv-screening.json](workflows/0978-ai-cv-screening.json)
  Description: This automated flow collects form information and analyzes uploaded PDF CVs to qualify candidates. It integrates AI evaluation, sends HR notifications, and confirms submission by email.

- [0979-pipeline-etl-twitter-sentiment.json](workflows/0979-pipeline-etl-twitter-sentiment.json)
  Description: This daily automation searches for tweets with the #OnThisDay hashtag via ETL, analyzes their sentiment using Google NLP, and stores the results in Postgres and MongoDB tables.

- [0980-lead-generation.json](workflows/0980-lead-generation.json)
  Description: This automated flow allows extracting and saving thousands of leads with complete data to Airtable.

- [0981-html-generator.json](workflows/0981-html-generator.json)
  Description: This automated flow allows dynamically generating complete HTML pages based on user requests using the structure defined by OpenAI. The process sends the user's text to the GPT-4o-mini API with a specific JSON schema, then converts that JSON response into complete HTML.

- [0982-comparativa-ia-pdf.json](workflows/0982-comparativa-ia-pdf.json)
  Description: This flow automates data extraction directly from PDF files using AI models like Claude or Gemini for efficient comparison.

- [0983-telegram-resume-processing.json](workflows/0983-telegram-resume-processing.json)
  Description: This automated flow allows extracting information from a resume in PDF format via Telegram chatbot and generates a copy in PDF format with Gotenberg.

- [0984-ai-logo-extractor.json](workflows/0984-ai-logo-extractor.json)
  Description: This automated flow allows extracting information from an image with multiple logos using AI, and saving it in structured Airtable tables to categorize tools.

- [0985-youtube-ai-agent-comment-analysis.json](workflows/0985-youtube-ai-agent-comment-analysis.json)
  Description: This automated flow allows an AI conversational agent to interact and analyze YouTube data, including video transcription, comment collection, channel detail retrieval, thumbnail evaluation, and PostgreSQL memory management implementation.

- [0986-extract-lp.json](workflows/0986-extract-lp.json)
  Description: This flow allows automatically extracting the license plate number from images uploaded via form.

- [0987-line-chatbot-llm-extraction.json](workflows/0987-line-chatbot-llm-extraction.json)
  Description: This automated flow uses a self-hosted LLM model (Mistral Nemo) to extract personal information from messages received on LINE, analyzing and structuring the response according to a predefined JSON schema.

- [0988-finance-email-parser.json](workflows/0988-finance-email-parser.json)
  Description: This automated flow extracts financial transaction data from emails using Gmail as a source, Google Gemini AI for content analysis and interpretation, and finally structures the information into a specific format sent to a Google spreadsheet. The workflow uses custom labels to identify different transaction types (invoices, multiple payments, etc.) and applies intelligent processing based on the email sender.

- [0989-vertex-ai-pdf-image-extractor.json](workflows/0989-vertex-ai-pdf-image-extractor.json)
  Description: This automated flow allows extracting text from PDF files and images using Vertex AI (Gemini) and converting them to CSV for storage.

- [0990-google-trends-automatizacion.json](workflows/0990-google-trends-automatizacion.json)
  Description: This automated flow analyzes Google Trends results, filters by minimum traffic and maximum results, then extracts information from related articles via scraping with Jina.ai. If conditions are met (e.g., adequate traffic and new terms), it saves the information in a Google sheet for tracking.

- [0991-umami-analytics-ai.json](workflows/0991-umami-analytics-ai.json)
  Description: This analytical flow processes web traffic data from Umami using multiple API calls and JavaScript transformations to extract key metrics like visits and impressions. It then sends these results along with requests to an OpenRouter AI model to generate detailed analysis, which is finally stored in Baserow.

- [0992-monitor-urls-periodico.json](workflows/0992-monitor-urls-periodico.json)
  Description: This n8n flow periodically checks three specific URLs via HTTP requests, useful for monitoring web resources or services.

- [0993-airtable-telli-ia.json](workflows/0993-airtable-telli-ia.json)
  Description: This automated flow connects Airtable with telli, allowing contacts to be automatically added from the base and AI voice calls to be scheduled.

- [0994-spotify_telegram_integration.json](workflows/0994-spotify_telegram_integration.json)
  Description: This automated flow allows a user to send messages to Telegram about songs or artists, which are analyzed by OpenAI to get detailed information, and then that music is searched for and controlled on Spotify.

- [0995-agent-access-control.json](workflows/0995-agent-access-control.json)
  Description: This flow verifies user credentials in Airtable to establish permissions and access control to different agents and tools.

- [0996-speech_assistant_telegram.json](workflows/0996-speech_assistant_telegram.json)
  Description: This flow uses the Google Gemini and OpenAI API along with n8n to process messages in Telegram, whether textual or voice. It analyzes content, provides feedback on clarity, structure, and content, and allows collaborative speech refinement.

- [0997-netsuite-suiteql-query.json](workflows/0997-netsuite-suiteql-query.json)
  Description: This flow allows executing SuiteQL queries in NetSuite and receiving the results via a webhook.

- [0998-google-credentials-setup.json](workflows/0998-google-credentials-setup.json)
  Description: This automated flow allows creating multiple Google OAuth2 credentials in the n8n tool, using manually provided information.

- [0999-github-prompts-dynamic.json](workflows/0999-github-prompts-dynamic.json)
  Description: This flow automates loading dynamic prompts from a GitHub repository and auto-populating them with n8n expressions for use in language models.

- [1000-ip-authentication-report.json](workflows/1000-ip-authentication-report.json)
  Description: This flow queries and filters successful authentication events for different login types and then sends a report in CSV format via email.

- [1001-flux-image-generator.json](workflows/1001-flux-image-generator.json)
  Description: This automated flow allows generating images with predefined styles (like AI Dystopia, Hyper-Surreal Escape, etc.) via the huggingface API. After a user completes a form providing a prompt and selects a style, the system calls the corresponding model, uploads the generated image to S3, and displays the result on a webpage.

- [1002-flux-dev-image-generation.json](workflows/1002-flux-dev-image-generation.json)
  Description: This automated flow generates an image using the Fal.ai API with predefined parameters and downloads it for automatic storage in Google Drive.

- [1003-ia-output-parser.json](workflows/1003-ia-output-parser.json)
  Description: This flow forces AIs to use a specific output format via structured or self-fixing parsers, ensuring organized and validated responses.

- [1004-imagen-optimizada-gdrive.json](workflows/1004-imagen-optimizada-gdrive.json)
  Description: This automated flow optimizes images uploaded to a Google Drive folder and resends them to the same service.

- [1005-telegram-crypto-price-agent.json](workflows/1005-telegram-crypto-price-agent.json)
  Description: This automated flow allows a Telegram chatbot to maintain conversations about cryptocurrency prices using contextualized memory and tools to query the CoinMarketCap API.

- [1006-rag-stock-analysis.json](workflows/1006-rag-stock-analysis.json)
  Description: This flow analyzes profitability reports using RAG to generate a detailed markdown report on trends and differences.

- [1007-comprador-personalizado-IA-RAG.json](workflows/1007-comprador-personalizado-IA-RAG.json)
  Description: This flow uses OpenAI and RAG to create a personalized assistant that answers queries about products or general business information.

- [1008-workflow-pdf-wordpress-ai.json](workflows/1008-workflow-pdf-wordpress-ai.json)
  Description: This automated flow transforms PDF documents into WordPress blog posts formatted using AI to generate content and titles, creating images with pollinations.ai, and incorporating human review via Gmail.

- [1009-huggingface-notion-ai-database.json](workflows/1009-huggingface-notion-ai-database.json)
  Description: This automated flow executes a daily query to the Hugging Face API weekly to get data on publications related to artificial intelligence and stores it in a structured format as a database in Notion.

- [1010-workflow-contact-form-automation.json](workflows/1010-workflow-contact-form-automation.json)
  Description: This automated flow classifies WordPress form (CF7) responses and generates personalized email drafts to efficiently respond to customers.

- [1011-producthunt-monitor-ai-agents.json](workflows/1011-producthunt-monitor-ai-agents.json)
  Description: This automated flow searches for the latest product launches related to 'AI Agents' on ProductHunt, verifies if there are valid results, and sends an update to a Slack channel daily.

- [1012-crm-coupon-assignment.json](workflows/1012-crm-coupon-assignment.json)
  Description: This automated flow manages the assignment and validation of unique coupons via QR code for lead generation, maintaining a bidirectional relationship with Google Sheets.

- [1013-openai-image-generation.json](workflows/1013-openai-image-generation.json)
  Description: This automated flow allows generating multiple images using OpenAI's GPT-4 image model via its API.

- [1014-INSEE_AgileCRM_Enrichment.json](workflows/1014-INSEE_AgileCRM_Enrichment.json)
  Description: This automated flow enriches company data in Agile CRM using the open INSEE API.

- [1015-modelo_openai_fine_tuning.json](workflows/1015-modelo_openai_fine_tuning.json)
  Description: This automated flow allows the creation and use of custom OpenAI models through fine-tuning based on JSONL files downloaded from Google Drive.

- [1016-bright-data-serp-extractor.json](workflows/1016-bright-data-serp-extractor.json)
  Description: This flow uses the Bright Data API to extract data from Google search result pages (SERP) and processes it with LLM chains like Gemini Flash Exp to generate a structured response.

- [1018-elevenlabs-tts-api.json](workflows/1018-elevenlabs-tts-api.json)
  Description: This automated flow allows generating text audio using the Elevenlabs API via webhooks, first verifying that 'voice_id' and 'text' parameters are correctly provided.

- [1019-obsidian-airtable-agent.json](workflows/1019-obsidian-airtable-agent.json)
  Description: This flow allows getting data from Airtable and generating notes in Obsidian using an OpenAI chat model.

- [1020-item-matching-example.json](workflows/1020-item-matching-example.json)
  Description: This flow uses the itemMatching() function in the code node to modify specific fields of the workflow items.

- [1021-daily-digest.json](workflows/1021-daily-digest.json)
  Description: This automated flow compiles a daily summary with news, emails, and pending tasks in a single HTML view.

- [1022-gmail-ai-auto-responder.json](workflows/1022-gmail-ai-auto-responder.json)
  Description: This automated flow analyzes incoming emails and decides if a response is needed using OpenAI artificial intelligence, creating drafts in Gmail for conversations.

- [1023-get-bible-api-adapter.json](workflows/1023-get-bible-api-adapter.json)
  Description: This flow allows converting a list of structured biblical references into a compatible format for querying via the GetBible API.

- [1024-clicksend-tts.json](workflows/1024-clicksend-tts.json)
  Description: This flow uses n8n to send synthesized voice messages via the ClickSend service using a REST API. It allows creating a form where users can enter text (body), destination number, choose between male or female voice, and select the language.

- [1025-chatbot-extraccion-datos-personales.json](workflows/1025-chatbot-extraccion-datos-personales.json)
  Description: This automated flow analyzes chat messages to extract personal data (name, surname, communication type) and contacts in JSON format.

- [1026-factura-pdf-jsreport.json](workflows/1026-factura-pdf-jsreport.json)
  Description: This flow allows entering invoice information via a form and automatically generates a PDF document using JSReport, which is then attached to an email.

- [1027-facebook-long-lived-token.json](workflows/1027-facebook-long-lived-token.json)
  Description: This automated flow obtains a long-lived Facebook access token from configured parameters and then uses it to obtain page tokens with application scope.

- [1028-lark-message-sender.json](workflows/1028-lark-message-sender.json)
  Description: This automated flow allows obtaining an authentication token for Larksuite and subsequently sending a text message to a specific conversation.

- [1029-seo-onpage-audit.json](workflows/1029-seo-onpage-audit.json)
  Description: This flow analyzes the on-page SEO of a landing page using GPT models to generate detailed reports.

- [1030-telegram-ai-image-generation.json](workflows/1030-telegram-ai-image-generation.json)
  Description: This automated flow converts Telegram message text into OpenAI-generated images and sends them back to the user via the Telegram application.

- [1031-open-meteo-ai-chat.json](workflows/1031-open-meteo-ai-chat.json)
  Description: This automated flow uses Open-Meteo API functions (Tools) with ChatGPT to determine the exact location of a city requested by the user and subsequently use those coordinates to generate a detailed weather forecast.

- [1032-ai-agents-http-tool.json](workflows/1032-ai-agents-http-tool.json)
  Description: This flow allows users to request activities or information via an AI query, using integrated HTTP tools that simplify API calls.

- [1033-icypeas-email-verification.json](workflows/1033-icypeas-email-verification.json)
  Description: This flow verifies a single email in Icypeas via an HTTP request followed by authentication.

- [1034-icypeas-domain-search.json](workflows/1034-icypeas-domain-search.json)
  Description: This automated flow performs domain searches using the Icypeas API.

- [1035-deepseek-chat-r1.json](workflows/1035-deepseek-chat-r1.json)
  Description: This flow allows interacting with DeepSeek models (conversational and reasoner) while maintaining contextualized memory.

- [1036-daily-calendar-summarization-slack.json](workflows/1036-daily-calendar-summarization-slack.json)
  Description: This automated flow allows the user to get all daily Google Calendar events and send an AI-generated summary to their Slack channel.

- [1037-gsc-weekly-report.json](workflows/1037-gsc-weekly-report.json)
  Description: This automated flow executes a weekly SEO report based on Google Search Console data and sends it via email.

- [1038-kb-confluence-search-response.json](workflows/1038-kb-confluence-search-response.json)
  Description: This flow searches Confluence for relevant information based on received queries to improve technical support.

- [1039-amazon-keywords-automation.json](workflows/1039-amazon-keywords-automation.json)
  Description: This automated flow gets keyword suggestions from the Amazon Completion API based on a webhook input, cleans the data, and then stores it in Airtable.

- [1040-auto_resume_disabled_workflows.json](workflows/1040-auto_resume_disabled_workflows.json)
  Description: This automated flow searches for workflows with auto-resume enabled that are disabled, then activates them to maintain the correct state.

- [1041-google-drive-rag-automation.json](workflows/1041-google-drive-rag-automation.json)
  Description: This automated flow allows downloading Google Drive documents, extracting and normalizing their text, generating embeddings with Gemini, inserting them into a Pinecone index for semantic search, and when a chat message is received, retrieving relevant information from the vector store.

- [1042-youtube-ai-summary-discord.json](workflows/1042-youtube-ai-summary-discord.json)
  Description: This automated flow monitors new YouTube videos via an RSS URL, gets their English subtitles, processes and summarizes them with the ChatGPT API, and then posts the summary along with the video link to a Discord channel.

- [1043-linkedin-url-discovery.json](workflows/1043-linkedin-url-discovery.json)
  Description: This flow searches and extracts LinkedIn URLs in a specific Google sheet for each row.

- [1044-line-customer-service-whatsapp-asana.json](workflows/1044-line-customer-service-whatsapp-asana.json)
  Description: This automated flow allows integrating WhatsApp form responses with task creation in Asana for incident tracking.


- [1046-gmail-api-automation.json](workflows/1046-gmail-api-automation.json)
  Description: This automated flow allows sending and receiving emails via the Gmail API, using a single set of OAuth2 credentials for different operations.
- [1047-linkedin-ai-post.json](workflows/1047-linkedin-ai-post.json)
  Description: This flow automates posting on LinkedIn. It pulls the day's content from Notion, reformats it with AI, attaches the corresponding image, and publishes the result on your profile.

- [1048-notion-clockify-client-sync.json](workflows/1048-notion-clockify-client-sync.json)
  Description: This automated flow detects new clients in a Notion database and automatically adds each one to the Clockify time management system.

- [1049-pdf-to-text-converter.json](workflows/1049-pdf-to-text-converter.json)
  Description: Converts PDF files to text using a custom plugin and an HTML input.

- [1050-techcrunch-scraping.json](workflows/1050-techcrunch-scraping.json)
  Description: This automated flow extracts detailed information about the latest TechCrunch articles through sequential HTML processing and HTTP requests.

- [1051-youtube-video-summarizer.json](workflows/1051-youtube-video-summarizer.json)
  Description: This flow uses Searchapi.io along with OpenAI models and advanced text splitting techniques to extract, process, and generate a complete summary of the content of specified YouTube videos.

- [1052-monday-com-column-split.json](workflows/1052-monday-com-column-split.json)
  Description: This flow processes data from specific columns in a Monday.com card and splits them to handle sub-items separately.

- [1053-movie-recommendations-agent.json](workflows/1053-movie-recommendations-agent.json)
  Description: This flow allows a chat assistant to get movie recommendations using the OpenAI API and real-time querying of a MongoDB database.

- [1054-outlook-ai-response.json](workflows/1054-outlook-ai-response.json)
  Description: This automated flow connects a Microsoft Outlook account to filter and process specific incoming emails (in this case 'sales@yourcompany.com'), using an AI agent that responds with a professional, concise, and modern style based on predefined examples.

- [1055-line-chatbot-search.json](workflows/1055-line-chatbot-search.json)
  Description: This automated flow allows a LINE chatbot to search for information on the web when the user makes queries, using tools like SearchAPI.io and LLM models like OpenAI.

- [1056-test_pdf.json](workflows/1056-test_pdf.json)
  Description: This flow allows combining multiple PDFs into a single document and writing it to the file system.

- [1057-analisis-feedback-ia.json](workflows/1057-analisis-feedback-ia.json)
  Description: This flow processes customer comments, analyzes feedback with artificial intelligence to get a summary, improvement suggestions, and ideas for social posts, and then sends the results by email to the team address.
- [1058-notion-pinecone-embeddings.json](workflows/1058-notion-pinecone-embeddings.json)
  Description: This flow monitors new pages in Notion, summarizes the content, generates 768-dimension embeddings via Google Gemini, and inserts them into a Pinecone index.

- [1059-automatic-meetings-telegram.json](workflows/1059-automatic-meetings-telegram.json)
  Description: This automated flow sends a list of your scheduled meetings for the current day to Telegram every morning at six, with dates and times formatted in Persian.

- [1060-slack-gmeet-automator.json](workflows/1060-slack-gmeet-automator.json)
  Description: This automated flow allows generating Google Meet links from Slack requests and sending them to channel participants.

- [1061-telegram-echo-bot.json](workflows/1061-telegram-echo-bot.json)
  Description: This automated flow allows a Telegram chatbot to display the JSON content of any message or event received in real-time.

- [1062-x-post-ai.json](workflows/1062-x-post-ai.json)
  Description: This automated flow automatically posts the latest YouTube videos to X/Twitter with text generated by ChatGPT.

- [1063-github-issues-monitor.json](workflows/1063-github-issues-monitor.json)
  Description: This automated flow queries open issues from a specific GitHub repository every 10 minutes (with parameters like state and labels) and sends only those with fewer than 5 comments via Telegram.

- [1064-okMME97B70fXzK5U_telegram_to_kindle.json](workflows/1064-okMME97B70fXzK5U_telegram_to_kindle.json)
  Description: This automated flow allows receiving attachments via Telegram, verifying their existence, renaming them to send as email attachments to a Kindle address, and notifying both the user on Telegram and via email if the process is successful or fails.

- [1065-assistant-creator.json](workflows/1065-assistant-creator.json)
  Description: This automated flow allows downloading Google Drive documents and creating an OpenAI assistant with those files, followed by a conversation with the assistant.

- [1066-openai-tweet-generator.json](workflows/1066-openai-tweet-generator.json)
  Description: This flow uses OpenAI to generate tweets based on randomly selected hashtags and then automatically saves them to an Airtable base.

- [1067-discord-gemini-response.json](workflows/1067-discord-gemini-response.json)
  Description: This automated flow allows a Discord bot to use Google Gemini to generate conversational responses based on a context window, maintaining conversation history using a memory buffer.

- [1068-openai-tts-audio-generation.json](workflows/1068-openai-tts-audio-generation.json)
  Description: This flow allows generating audio from text using OpenAI's Text-to-Speech (TTS) API. A webhook is configured to receive POST requests that include the text to be converted.

- [1069-telegram-error-handler.json](workflows/1069-telegram-error-handler.json)
  Description: This automated flow sends error notifications to a specific Telegram chat when a failure occurs in any workflow execution.

- [1070-server-monitor-n8n.json](workflows/1070-server-monitor-n8n.json)
  Description: This automated flow checks the availability of web servers every minute via HTTP requests and logs the results in Google spreadsheets.

- [1071-slack-chatbot-slash.json](workflows/1071-slack-chatbot-slash.json)
  Description: This automated flow configures a Slack chatbot using slash commands to interact with users. It responds to different commands like /ask and /another, using OpenAI models.

- [1072-openweathermap-airtable-weather.json](workflows/1072-openweathermap-airtable-weather.json)
  Description: This automated flow gets daily weather data from the OpenWeatherMap API and stores it in an Airtable table.

- [1073-namesilo-domain-checker.json](workflows/1073-namesilo-domain-checker.json)
  Description: This automated flow verifies the availability of multiple domains via the Namesilo API and exports the results in Excel format.

- [1074-netflix-email-forwarding-gmail-mailjet.json](workflows/1074-netflix-email-forwarding-gmail-mailjet.json)
  Description: This automated flow sends Netflix emails received in a Gmail account to multiple defined recipients, using both Gmail and Mailjet services for transmission.

- [1075-x-publication-automation.json](workflows/1075-x-publication-automation.json)
  Description: This automated flow allows publishing on X using the Airtop service, following steps to create a session, open a window, write text, and click 'Publish'.

- [1076-youtube-promotion-x.json](workflows/1076-youtube-promotion-x.json)
  Description: This automated flow checks every 30 minutes if there are new videos on a specific YouTube channel and uses ChatGPT to generate messages on X (formerly Twitter) that promote said videos, staying under the character limit.

- [1077-twilio-http-monitor.json](workflows/1077-twilio-http-monitor.json)
  Description: This automated flow periodically checks the status of a URL via an HTTP request and sends an SMS via Twilio if the response is successful (code 200).

- [1078-matomo-seo-ai-report.json](workflows/1078-matomo-seo-ai-report.json)
  Description: This automated flow analyzes data from recurring visitors (more than 3 visits) in Matomo via integration with LLaMA-3 and saves the results in Baserow for SEO analysis.

- [1079-automatizar-carga-csv-postgres.json](workflows/1079-automatizar-carga-csv-postgres.json)
  Description: This automated flow reads a CSV file from /tmp, converts it to spreadsheet format, and loads the data directly into the t1 table of PostgreSQL.

- [1080-ai-stock-analysis.json](workflows/1080-ai-stock-analysis.json)
  Description: This flow analyzes stock or cryptocurrency charts via images using AI and returns a simplified technical analysis in child-like terms.

- [1081-retry-on-fail-known-error.json](workflows/1081-retry-on-fail-known-error.json)
  Description: This flow implements a retry mechanism for an action but avoids retries in case of specific known errors like 'could not be found'.

- [1082-serp-bear-ai-analysis.json](workflows/1082-serp-bear-ai-analysis.json)
  Description: This automated flow analyzes SERP Bear keyword rank data using artificial intelligence and saves the analysis in Baserow.

- [1083-line-email-ai-resumen.json](workflows/1083-line-email-ai-resumen.json)
  Description: This automated flow uses an AI model to read and summarize incoming emails via IMAP, highlighting important or urgent items like deadlines through intelligent analysis.

- [1084-form-to-airtable.json](workflows/1084-form-to-airtable.json)
  Description: This automated flow automatically captures form data and stores it in an Airtable table without manual intervention. Each form submission creates a new record with custom fields for 'Name', 'Age', 'Email', 'Address', and 'Subscription'.

- [1085-send-sms-clicksend.json](workflows/1085-send-sms-clicksend.json)
  Description: This flow allows sending a text message (SMS) via the ClickSend API when manually activated.

- [1086-perplexity-api-query.json](workflows/1086-perplexity-api-query.json)
  Description: This automated flow queries the Perplexity AI API using the Sonar model with a system prompt and a user request, and then cleanly processes the response.

- [1087-insta-chatbot-gpt.json](workflows/1087-insta-chatbot-gpt.json)
  Description: This flow allows integrating ChatGPT into Instagram via ManyChat to generate automated responses.

- [1088-zip-multiple-files.json](workflows/1088-zip-multiple-files.json)
  Description: This flow compresses multiple files into a dynamic ZIP file with n8n.

- [1089-comunidad-topicos-n8n.json](workflows/1089-comunidad-topicos-n8n.json)
  Description: This automated flow monitors specific topics in the n8n community via a search term and updates a spreadsheet with the results.

- [1090-upload-instagram-tiktok.json](workflows/1090-upload-instagram-tiktok.json)
  Description: This flow allows automatically uploading images to Instagram and TikTok using the same endpoint.

- [1091-spotify-maintenance.json](workflows/1091-spotify-maintenance.json)
  Description: This automated flow checks if songs from recent Spotify plays are already saved in the NocoDB database. If not, it creates new records for each with the song URI and the date it was added (using currentDate). It also searches the existing database for a monthly playlist with a name corresponding to the current date. If it exists, it gets its tracks; if it doesn't exist on Spotify but is in NocoDb, it creates it and synchronizes.

- [1092-url-shortener-management.json](workflows/1092-url-shortener-management.json)
  Description: This automated flow manages short URLs by generating SHA-256 hashes stored in Airtable, allowing creation and verification of unique references to control access or records.

- [1093-n8n-git-automation.json](workflows/1093-n8n-git-automation.json)
  Description: This automated flow allows adding a README.md file and performing the first commit followed by a push on GitHub when manually executed.

- [1094-trello-sync.json](workflows/1094-trello-sync.json)
  Description: This automated flow gets Google Calendar events daily at 8:00 AM, checks if they are recurring tasks (like 'Check email', etc.), and deletes them if necessary. It then creates Trello cards for each event with its details.

- [1095-travis-ci-trigger.json](workflows/1095-travis-ci-trigger.json)
  Description: This workflow activates builds on Travis CI when a 'push' event or an 'opened' action occurs in the 'n8n-io/n8n' repository.

- [1096-mattermost-standup-bot.json](workflows/1096-mattermost-standup-bot.json)
  Description: This automated flow allows the Mattermost standup bot to manage configurations and send scheduled alerts.

- [1097-n8n-workflows-guardar.json](workflows/1097-n8n-workflows-guardar.json)
  Description: This automated flow allows saving n8n workflows to JSON files in Google Drive.

- [1098-eliminar-mensajes-gmail-batches.json](workflows/1098-eliminar-mensajes-gmail-batches.json)
  Description: This automated flow allows deleting old Gmail messages via batch operations.

- [1099-notion-page-archiver.json](workflows/1099-notion-page-archiver.json)
  Description: This automated flow automatically searches for and archives empty pages in a Notion database.

- [1100-gotify-weather-update.json](workflows/1100-gotify-weather-update.json)
  Description: This automated flow is triggered daily at 9:00 AM via a Cron node and gets the current temperature of Berlin using OpenWeatherMap. It then uses Gotify to send a notification with this information as part of the message.

- [1101-strapi-create-update.json](workflows/1101-strapi-create-update.json)
  Description: This automated flow allows creating an entry in Strapi (posts), saving its ID, and then updating it with a specific slug.

- [1102-disqus-forum-details.json](workflows/1102-disqus-forum-details.json)
  Description: This automated flow executes a manual action to get the details of a specific forum on Disqus.

- [1103-plex-qbittorrent-automation.json](workflows/1103-plex-qbittorrent-automation.json)
  Description: This flow automates speed control and download management in QBittorrent based on Plex webhook events, allowing configuration of speed limits or specific actions like pausing/resuming torrents according to the received action.

- [1104-airtable-batch-processing-with-rates.json](workflows/1104-airtable-batch-processing-with-rates.json)
  Description: This flow processes records in batch in Airtable with three modes: insert, update, and upsert. To avoid Airtable API rate limits, it includes pauses after each 429 error.

- [1105-netlify-deploy-alert.json](workflows/1105-netlify-deploy-alert.json)
  Description: This automated flow detects failures in Netlify deployments and sends an alert to a Slack channel.

- [1106-openlibrary-recommendation.json](workflows/1106-openlibrary-recommendation.json)
  Description: This automated flow searches and recommends a random book from Open Library based on the theme 'juvenile_literature' every Friday at 11:00 AM or via manual execution, using HTTP requests to get data and send emails with recommendations.

- [1107-activeMQ-amqp-trigger.json](workflows/1107-activeMQ-amqp-trigger.json)
  Description: This flow uses the AMQP trigger to receive messages from an ActiveMQ queue.

- [1108-notion-project-user-management.json](workflows/1108-notion-project-user-management.json)
  Description: This flow allows managing project and user creation in Notion via functions that process data and integrates with webhooks.

- [1109-transcripcion-drive-sheets.json](workflows/1109-transcripcion-drive-sheets.json)
  Description: This automated flow transcribes voice files uploaded to Google Drive and saves the result in a spreadsheet.

- [1110-nicepng-text-analysis.json](workflows/1110-nicepng-text-analysis.json)
  Description: This flow analyzes a PNG file of motivational quotes with AWS Rekognition to detect text, then extracts the image name and link via an HTTP request and incorporates everything along with the detected texts (converted to lowercase) into Google Sheets via OAuth2.

- [1111-mattermost-bebida.json](workflows/1111-mattermost-bebida.json)
  Description: This flow allows receiving a POST request via webhook, getting random data from an API (like a cocktail recipe), and sending a formatted message to Mattermost with specific details.

- [1112-openai-n8n-examples.json](workflows/1112-openai-n8n-examples.json)
  Description: This n8n flow contains examples of how to use different OpenAI models and APIs to generate summaries (TLDR), translate text, create image prompts, and more.

- [1113-swift_codes_extractor.json](workflows/1113-swift_codes_extractor.json)
  Description: This automated flow extracts SWIFT codes from multiple web pages in different countries, processes the normalized information, and saves it in a MongoDB database.

- [1114-backup-n8n-workflows.json](workflows/1114-backup-n8n-workflows.json)
  Description: This automated n8n flow saves all server configurations into JSON files stored in a GitHub repository.

- [1115-filemaker-pagination.json](workflows/1115-filemaker-pagination.json)
  Description: This flow processes a paginated response from the FileMaker Data API to extract specific contact data.

- [1116-quickbase-registros-n8n.json](workflows/1116-quickbase-registros-n8n.json)
  Description: This flow allows creating, updating, and getting records in Quick Base via configured nodes.

- [1117-telegram-multilang-bot.json](workflows/1117-telegram-multilang-bot.json)
  Description: This automated flow allows a Telegram chatbot to maintain records in a database and send multilingual responses according to the user's language.

- [1118-telegram-weather-bot.json](workflows/1118-telegram-weather-bot.json)
  Description: This automated flow allows a Telegram bot to provide weather data via R-generated charts, following a protocol defined by /start and /getweather commands.

- [1119-smart-factory-alert.json](workflows/1119-smart-factory-alert.json)
  Description: This flow monitors factory sensors to detect temperatures above 50°C and stores both sensor data and incidents in CrateDB.

- [1120-recomendaciones-qdrant-mistral.json](workflows/1120-recomendaciones-qdrant-mistral.json)
  Description: This automated flow recommends recipes using Qdrant for vector search and Mistral AI as a language model.
- [1120-gmail-email-csv.json](workflows/1120-gmail-email-csv.json)
  Description: Downloads a Gmail email containing a JSON file and converts its information into a CSV for spreadsheets.

- [1122-wordpress-auto-generation.json](workflows/1122-wordpress-auto-generation.json)
  Description: This automated flow selects the least used WordPress category from a PostgreSQL database to generate unique and structured articles using GPT models. After creating the complete content in specific HTML format, it generates an optimized title and downloads/attaches a featured image before publishing everything together.

- [1123-shopify-deal-sync.json](workflows/1123-shopify-deal-sync.json)
  Description: This automated flow checks if an updated order in Shopify already exists as a deal in HubSpot and, if not, creates a new deal using order data.

- [1124-zendesk-pipedrive-ticket.json](workflows/1124-zendesk-pipedrive-ticket.json)
  Description: This automated flow processes Zendesk tickets every 5 minutes to search for and update requester information using Pipedrive data.

- [1125-zendesk-pipedrive-sync.json](workflows/1125-zendesk-pipedrive-sync.json)
  Description: This automated flow synchronizes Zendesk ticket comments with notes on Pipedrive people based on the sender's email and uses the last timestamp to filter updates.

- [1126-xml-to-sheets.json](workflows/1126-xml-to-sheets.json)
  Description: This automated flow downloads a sample XML file, parses it to extract elements, and creates a new file in Google Sheets with columns defined from the content.

- [1127-procesamiento_excel.json](workflows/1127-procesamiento_excel.json)
  Description: This flow processes Excel files via various sources and destinations, allows data manipulation, and optionally saves or uploads the modified file.

- [1128-csv-insert-json.json](workflows/1128-csv-insert-json.json)
  Description: This automated flow reads a CSV file from a specific location and converts it to spreadsheet format to then insert it into the MySQL table concerts_2023_csv.

- [1129-telegram-facebook-interest.json](workflows/1129-telegram-facebook-interest.json)
  Description: This automated flow processes Telegram messages starting with '#interest' to search for interests in the Facebook Graph API and then generates a CSV file with the results.

- [1130-auto-email-campaign-followup.json](workflows/1130-auto-email-campaign-followup.json)
  Description: This automated flow manages email campaigns with subsequent follow-up. It gets information from a Google sheet, classifies conversation threads, and sends automated messages according to a predefined schedule.

- [1131-notion-linear-issue-sync.json](workflows/1131-notion-linear-issue-sync.json)
  Description: This automated flow extracts information from To-Do blocks in Notion with a specific format and uses it to automatically create tasks in Linear.

- [1132-todoist-task-management.json](workflows/1132-todoist-task-management.json)
  Description: This automated flow manages tasks in Todoist by moving them between projects according to deadlines and time conditions.

- [1133-linear-tickets-sync.json](workflows/1133-linear-tickets-sync.json)
  Description: This automated flow extracts and processes all issues from a specific team in Linear, paginating results to handle large volumes.

- [1134-youtube-moments-analyzer.json](workflows/1134-youtube-moments-analyzer.json)
  Description: This flow analyzes YouTube videos for 'engaging' moments where intensity exceeds a threshold and are not too close to each other, generating a structured response with the most relevant time coordinates.

- [1135-linear-bug-report.json](workflows/1135-linear-bug-report.json)
  Description: This n8n flow processes bug reports received via webhook in Slack and converts them into tasks within Linear, using OAuth credentials for authentication.

- [1136-linear-ai-classification.json](workflows/1136-linear-ai-classification.json)
  Description: This automated flow classifies bug tickets in Linear using AI (OpenAI) and assigns the responsible team according to their work areas. The ticket is analyzed, AI determines the appropriate team, and this is updated in Linear.

- [1137-pdf-qa-vector-store.json](workflows/1137-pdf-qa-vector-store.json)
  Description: This flow processes chat messages to answer questions about a PDF using the vector stored in Qdrant.

- [1138-email-verificacion-google-sheets.json](workflows/1138-email-verificacion-google-sheets.json)
  Description: This automated flow verifies if the email is not duplicated (based on a removeDuplicates function) and verifies its existence via API. If it exists, it performs an update in Google Sheets.

- [1139-telegram-image-analysis.json](workflows/1139-telegram-image-analysis.json)
  Description: This automated flow detects if a message receives an image and analyzes it with OpenAI to send a processed response via Telegram.

- [1140-gmail-email-test.json](workflows/1140-gmail-email-test.json)
  Description: This automated flow allows sending test emails with an attached image using OAuth2 authentication in Google Mail.

- [1141-hubspot-product-replication.json](workflows/1141-hubspot-product-replication.json)
  Description: This automated flow allows automatically replicating line items from a won deal to a newly created one in HubSpot, integrating Workflows and n8n via webhooks.

- [1142-s3-lista-archivos.json](workflows/1142-s3-lista-archivos.json)
  Description: This automated flow allows downloading all files from a specific Amazon S3 folder and compressing them into a ZIP file for easy download or later processing.

- [1143-seo-serp-analysis.json](workflows/1143-seo-serp-analysis.json)
  Description: This automated flow searches and processes Google search results for SEO analysis.

- [1144-firecrawl-markdown-scraper.json](workflows/1144-firecrawl-markdown-scraper.json)
  Description: This flow automates the extraction of web content in Markdown format and its links using the Firecrawl API.

- [1145-congratulations-automator.json](workflows/1145-congratulations-automator.json)
  Description: This automated flow checks if there are events scheduled today in the spreadsheet, and if so, customizes a message with happy wishes for each contact and sends SMS using Twilio.

- [1146-digitalocean-snapshots-management.json](workflows/1146-digitalocean-snapshots-management.json)
  Description: This automated flow automatically manages DigitalOcean instance snapshots, maintaining a maximum of 4 and deleting the oldest ones.

- [1147-notion-tareas-slack-automatizado.json](workflows/1147-notion-tareas-slack-automatizado.json)
  Description: This automated flow sends reminders of pending tasks stored in a Notion database via direct messages in Slack, filtering by specific users daily between Monday and Friday at 9:00 AM.

- [1148-linkedin-automation.json](workflows/1148-linkedin-automation.json)
  Description: This automated flow seeks to obtain recent articles about LinkedIn via scheduled searches, extract their links, and then generate contributions using AI technology.

- [1149-google-docs-image-replace.json](workflows/1149-google-docs-image-replace.json)
  Description: Google Docs automation with dynamic image replacement.

- [1150-spotify-playlist-classifier.json](workflows/1150-spotify-playlist-classifier.json)
  Description: This automated flow allows classifying and adding Spotify tracks to multiple playlists based on their characteristics and playback history using the Claude 3.5 model.

- [1151-qualys-slack-integration.json](workflows/1151-qualys-slack-integration.json)
  Description: This automated flow allows interacting with the Qualys API from Slack via modals, generating reports and executing vulnerability scans based on user input.

- [1152-qualys-scan-workflow.json](workflows/1152-qualys-scan-workflow.json)
  Description: This automated flow initiates a scan in Qualys via Slack and checks its status every 5 minutes until completion.

- [1153-qualys-report-automation.json](workflows/1153-qualys-report-automation.json)
  Description: This automated flow integrates the Qualys API with Slack to generate periodic reports and send them as attachments in the specified channel.

- [1154-content-generation-automated.json](workflows/1154-content-generation-automated.json)
  Description: This automated flow allows generating structured content from form inputs using OpenAI models and storing the results in Google Drive.

- [1155-sharepoint-token-fetch.json](workflows/1155-sharepoint-token-fetch.json)
  Description: This automated flow obtains authentication tokens to access a SharePoint list and allows executing scheduled operations with them.

- [1156-qualys-thehive-integration.json](workflows/1156-qualys-thehive-integration.json)
  Description: This automated flow searches for finalized reports in Qualys, discards those already processed according to a previous timestamp, and creates cases in TheHive with their respective report attachments.

- [1157-n8n-multi-workflow.json](workflows/1157-n8n-multi-workflow.json)
  Description: This automated flow allows executing multiple secondary jobs in parallel and tracking their status until all are finished.


- [1159-webinar-registration-klicktipp.json](workflows/1159-webinar-registration-klicktipp.json)
  Description: This flow automates the integration of webinar registrations from JotForm with KlickTipp. It validates and transforms data like names, dates, work experiences, and URLs to create subscribers in KlickTipp and apply dynamic tags based on form responses.

- [1160-customer-lead-ai-processing.json](workflows/1160-customer-lead-ai-processing.json)
  Description: This automated flow processes contact requests using an AI agent, analyzing notes to determine if they are valid and generating professional emails when required.

- [1161-gravity-klicktipp-integration.json](workflows/1161-gravity-klicktipp-integration.json)
  Description: This automated flow processes Gravity Forms submissions to subscribe contacts and apply tags in KlickTipp.

- [1162-typeform-klicktipp-quiz.json](workflows/1162-typeform-klicktipp-quiz.json)
  Description: This automated flow processes Typeform form responses to create contacts in KlickTipp and assign dynamic tags based on the responses.

- [1163-strava_ai_coaching_analysis.json](workflows/1163-strava_ai_coaching_analysis.json)
  Description: This automated flow analyzes sports activities from Strava using a conversational AI based on Google Gemini to offer personalized advice as a triathlon coach and sends a formatted summary via email.

- [1164-zendesk-gcal-airtable-customer-flow.json](workflows/1164-zendesk-gcal-airtable-customer-flow.json)
  Description: This automated flow allows a chatbot to integrate multiple systems like Zendesk to create tickets and manage customer data, Gcal (Google Calendar) to schedule appointments, Airtable to share transcripts with the product team, and n8n to execute all operations.

- [1165-telegram-sticker-checker.json](workflows/1165-telegram-sticker-checker.json)
  Description: This workflow analyzes if the message received on Telegram contains a sticker. If so, it responds with information about the sender and the sticker details (ID and set_name). Otherwise, it sends a message indicating that no sticker was found.

- [1166-threads-notion-integration.json](workflows/1166-threads-notion-integration.json)
  Description: This automated flow allows getting posts from the Threads API, filtering them, and saving them to a Notion database after detailed analysis.

- [1167-stripe-quickbooks-integration.json](workflows/1167-stripe-quickbooks-integration.json)
  Description: This blueprint implements an automated flow that integrates n8n with Stripe and QuickBooks Online. When a 'payment_intent.succeeded' webhook notification is received (payment success), it searches if the associated customer already exists in QuickBooks via an HTTP query to the QuickBooks API. If it doesn't exist, it creates a new customer in QuickBooks using data from the payment and Stripe, and then creates a sales receipt with those details. The flow uses n8n to handle the workflow.

- [1168-linkedin-enrichment.json](workflows/1168-linkedin-enrichment.json)
  Description: This automated flow reads LinkedIn URLs from Google Sheets, encodes and filters them to check if they are already enriched. It then calls the RapidAPI (Fresh LinkedIn Profile Data) to get complete profile data and finally updates a CSV file with this detailed information.

- [1169-gmail-file-monitor.json](workflows/1169-gmail-file-monitor.json)
  Description: This automated flow monitors emails in Gmail and classifies attachments by size for later handling, filtering large files (greater than 300MB) or intermediate files (between 10-300MB).

- [1170-html-to-pdf-conversor.json](workflows/1170-html-to-pdf-conversor.json)
  Description: This automated flow converts HTML content received in a webhook request into a PDF file and responds with it.

- [1171-sheets-screenshot-storage.json](workflows/1171-sheets-screenshot-storage.json)
  Description: This automated flow captures a website screenshot every time a new row is added in Google Sheets and saves the image to Google Drive.

- [1172-pdf-generator.json](workflows/1172-pdf-generator.json)
  Description: This automated flow allows generating PDF documents based on predefined HTML templates. It receives structured information like invoice details, automatically calculates amounts, and converts the complete structure into a PDF file using external libraries.

- [1173-retell-webhook-response.json](workflows/1173-retell-webhook-response.json)
  Description: This automated flow uses a webhook to receive incoming call data from Retell and search for the corresponding user in a Google Sheets file, responding with the necessary data.

- [1174-github_n8n_releases.json](workflows/1174-github_n8n_releases.json)
  Description: This automated flow checks daily at 10:00, 14:00, and 18:00 if there are new n8n versions published on GitHub, filtering for same-day releases that include 'n8n@' and a number with a decimal extension like '.0'. If a new version is detected, it sends notifications via Telegram and AWS SES.

- [1175-postgres-data-ingestion.json](workflows/1175-postgres-data-ingestion.json)
  Description: This automated flow executes a function every minute that generates random values and inserts them into a PostgreSQL table.

- [1176-zendesk-ticket-updates.json](workflows/1176-zendesk-ticket-updates.json)
  Description: This automated flow is configured to receive ticket updates in Zendesk via a webhook, although it is not active.

- [1177-registro-betterstack.json](workflows/1177-registro-betterstack.json)
  Description: This flow allows sending log messages to the BetterStack platform via an HTTP POST request.

- [1178-email-body-parser.json](workflows/1178-email-body-parser.json)
  Description: This flow analyzes the body of an email to extract specific fields from the message and store them as individual variables in the cloud.

- [1179-telegram-freshdesk-integration.json](workflows/1179-telegram-freshdesk-integration.json)
  Description: This automated flow processes Telegram messages to create tickets in Freshdesk or items in Monday.com depending on whether they contain the keyword 'refund'.

- [1180-rss-telegram-monitor.json](workflows/1180-rss-telegram-monitor.json)
  Description: This automated flow analyzes Instagram and Weibo RSS feeds to send updates via Telegram.

- [1181-typeform-problems-monitor.json](workflows/1181-typeform-problems-monitor.json)
  Description: This automated flow captures Typeform form submissions and stores them in Google Sheets. If severity is greater than 7, it sends an email and updates the Slack channel with problem details.

- [1182-trigger-crear-ticket.json](workflows/1182-trigger-crear-ticket.json)
  Description: This flow allows manually initiating the creation of a new ticket in Freshdesk.

- [1183-mautic-student-automation.json](workflows/1183-mautic-student-automation.json)
  Description: This automated flow processes student webhook requests, searches for users in Mautic, updates their data and newsletter-related information.

- [1184-google-drive-image-tagging.json](workflows/1184-google-drive-image-tagging.json)
  Description: This n8n flow automatically analyzes the content of images in Google Drive using an AI API and writes the results as tags (Subject/Keywords) in the EXIF metadata.

- [1185-mcp-brave-telegram-search.json](workflows/1185-mcp-brave-telegram-search.json)
  Description: This MCP flow uses the Brave API and Telegram to automatically perform web searches when the user sends a /brave command followed by a query.

- [1186-mautic-get-all-registros.json](workflows/1186-mautic-get-all-registros.json)
  Description: This flow allows manually initiating the execution of a task in the n8n system that connects to Mautic via OAuth2 authentication to get all records.

- [1187-hue-light-control.json](workflows/1187-hue-light-control.json)
  Description: This automated flow allows turning on a specific Philips Hue light and adjusting its brightness to a determined value.

- [1188-n8n-backup-cron.json](workflows/1188-n8n-backup-cron.json)
  Description: This flow schedules a task every 6 hours to execute a workflow and save its result as a binary file in Nextcloud.

- [1189-sheets-automation.json](workflows/1189-sheets-automation.json)
  Description: This automated flow allows reading data from a Google Sheets spreadsheet using search, then modifying the 'Rent' value in the found records and updating them.

- [1190-captura-tiempo-automatica.json](workflows/1190-captura-tiempo-automatica.json)
  Description: This automated flow captures the current local date and time in detailed format.

- [1191-rss-feed-multi-source.json](workflows/1191-rss-feed-multi-source.json)
  Description: This flow reads two RSS feeds from different sources using the rssFeedRead node.

- [1192-json-array-splitter.json](workflows/1192-json-array-splitter.json)
  Description: This workflow takes an initial input containing a JSON list and expands it into multiple flows, each with an individual item from the array for further processing.

- [1193-line-chatbot-memory.json](workflows/1193-line-chatbot-memory.json)
  Description: This flow processes user data to maintain context in conversations.

- [1194-slack-webhook-verify.json](workflows/1194-slack-webhook-verify.json)
  Description: This flow verifies the signature of a Slack web request using HMAC SHA256 to ensure the message actually comes from the official Slack webhook and is not a fake.

- [1195-hubspot-email-validation.json](workflows/1195-hubspot-email-validation.json)
  Description: This flow automatically verifies if a newly created contact in HubSpot has a valid, reliable, or non-suspicious email address.

- [1196-trello-crear-tarjeta-automatico.json](workflows/1196-trello-crear-tarjeta-automatico.json)
  Description: This flow allows automatically creating a card in Trello when manually executed.

- [1197-slack-rss-publicacion.json](workflows/1197-slack-rss-publicacion.json)
  Description: This automated flow posts all articles from the n8n.io/blog RSS feed published the day before to the 'news' Slack channel.

- [1198-notion-duplicates-removal.json](workflows/1198-notion-duplicates-removal.json)
  Description: This flow automatically removes duplicate pages in a Notion database.

- [1199-google-drive-doc-summarizer.json](workflows/1199-google-drive-doc-summarizer.json)
  Description: This automated flow identifies the most recently created Google Drive document, extracts its content, and summarizes it using artificial intelligence before storing it in a spreadsheet.

- [1200-telegram-image-analysis.json](workflows/1200-telegram-image-analysis.json)
  Description: This automated flow analyzes Telegram images using the OpenAI API.


- [1202-gmail-emails-monitor.json](workflows/1202-gmail-emails-monitor.json)
  Description: This flow monitors Gmail email and automatically adds each received message as a new row in a spreadsheet.

- [1203-line-error-alerts.json](workflows/1203-line-error-alerts.json)
  Description: This automated flow allows configuring an n8n workflow to receive immediate LINE notifications when an error occurs in another workflow. It automatically detects errors and sends an alert to the specified user via the 'Send body as JSON' button to the LINE API.

- [1204-telegram-ai-multitranslator.json](workflows/1204-telegram-ai-multitranslator.json)
  Description: This flow allows a Telegram bot to detect and translate voice messages in 55 languages, conversing with users in their native language.

- [1205-dst-automation.json](workflows/1205-dst-automation.json)
  Description: This automated flow verifies daylight saving time changes in different time zones and notifies via Slack and email about upcoming changes.

- [1206-hacker-news-recomendaciones.json](workflows/1206-hacker-news-recomendaciones.json)
  Description: This flow analyzes comments from 'ask_hn' posts related to a specific topic on Hacker News to recommend resources. It uses Google Gemini (PaLM) as a language model, processes the text, and categorizes it by type and difficulty level before sending it via email.

- [1207-lemlist-automation-sales.json](workflows/1207-lemlist-automation-sales.json)
  Description: This automated flow allows Lemlist to use GPT-3 to process lead responses and categorize them (as interested or out of office), in addition to creating deals in HubSpot based on those interactions.

- [1208-pdf-image-extractor.json](workflows/1208-pdf-image-extractor.json)
  Description: This automated flow extracts images from PDFs, analyzes each image with the GPT-4o model, and generates a text document integrating the results.

- [1209-n8n-ai-meteorologia.json](workflows/1209-n8n-ai-meteorologia.json)
  Description: This automated flow allows a chatbot to interact with the Open-Meteo API via tools that convert to functions, facilitating responses about weather forecasts based on user-specified locations.

- [1210-fal-ai-image-generation.json](workflows/1210-fal-ai-image-generation.json)
  Description: This automated flow allows generating images via the Fal.ai API, downloading them, and saving them to a specific Google Drive folder.

- [1211-covid_automated_import.json](workflows/1211-covid_automated_import.json)
  Description: This flow automates the one-time import of specific COVID-19 data (DACH: Germany, Austria, Switzerland) for the year 2023 from an external source to Google Sheets.

- [1212-save-sales-emails-odoo-opportunity.json](workflows/1212-save-sales-emails-odoo-opportunity.json)
  Description: This automated flow captures emails with specific labels in Gmail and uses them to create new sales opportunities in Odoo by summarizing their content via OpenAI.

- [1213-youtube-sync.json](workflows/1213-youtube-sync.json)
  Description: This flow synchronizes YouTube video URLs from specified channels in Google Sheets to another sheet using the YouTube API.

- [1214-pdf-extractor.json](workflows/1214-pdf-extractor.json)
  Description: This flow allows downloading a PDF via an HTTP request and specifically extracting pages 2-3 for processing.

- [1215-telegram-tron-blacklist-checker.json](workflows/1215-telegram-tron-blacklist-checker.json)
  Description: This automated flow allows a Telegram bot to check if a TRON wallet address is on the blacklist by querying the Tronscan API, and send the result to the user.

- [1216-github-multiple-file-push.json](workflows/1216-github-multiple-file-push.json)
  Description: This flow allows uploading multiple files to a GitHub repository via subscriptions, using the token and provided information for authentication and API interaction.

- [1217-luma-ai-webhook-process.json](workflows/1217-luma-ai-webhook-process.json)
  Description: This automated flow receives a web response from Luma AI via a webhook, verifies that it contains a non-empty video, and saves information about it (video URL, thumbnail) in Airtable.

- [1218-pdfmonkey-document-generation.json](workflows/1218-pdfmonkey-document-generation.json)
  Description: This automated flow detects when PDFMonkey generates a document and downloads the PDF file if generation is successful.

- [1219-paul_graham_essays_resumer.json](workflows/1219-paul_graham_essays_resumer.json)
  Description: This automated flow extracts the URLs of recent Paul Graham essays from a list of articles, then gets the full text of each essay and summarizes it using GPT.

- [1220-ai-cv-screening-process.json](workflows/1220-ai-cv-screening-process.json)
  Description: This automated flow allows the application form to capture candidate information for the Software Engineer position, process the uploaded CV, and send a detailed AI analysis to users. It then sends email confirmations to the candidate and notifies HR about new applications. Finally, it saves all this data in a Google Sheets spreadsheet.

- [1221-youtube-chapters-generator.json](workflows/1221-youtube-chapters-generator.json)
  Description: This workflow allows generating structured chapters for YouTube videos based on subtitles. It analyzes temporal content and creates an organized format.

- [1222-wikipedia-summarization-fl.json](workflows/1222-wikipedia-summarization-fl.json)
  Description: This automated flow uses Bright Data to extract information from Wikipedia and Google Gemini AI to format it into readable content and generate a concise summary.

- [1223-line-gratitude-reminder.json](workflows/1223-line-gratitude-reminder.json)
  Description: This automated flow sends a personalized message generated by Azure OpenAI at 9:00 PM to motivate reflection on the positive aspects of the day via LINE.

- [1224-telegram-recipe-daily.json](workflows/1224-telegram-recipe-daily.json)
  Description: This automated flow sends a random vegan recipe via Telegram daily via cron trigger, and also adds new users to chats to manage them appropriately.

- [1225-calvin-hobbes-discord.json](workflows/1225-calvin-hobbes-discord.json)
  Description: This automated flow daily gets Calvin and Hobbes comic strips from GoComics, extracts the image URL, and uses GPT-4o-mini to translate the original English dialogues into Korean. Finally, it posts both texts along with the image to a Discord channel.

- [1226-youtube-discord-ai-summary.json](workflows/1226-youtube-discord-ai-summary.json)
  Description: This automated flow monitors new YouTube videos and generates artificial intelligence summaries that are shared on Discord.

- [1227-tracker-gastos-ia-descripcion.json](workflows/1227-tracker-gastos-ia-descripcion.json)
  Description: This flow allows an AI agent to process messages about expenses, convert them into structured JSON data, and automatically save them in a Google sheet. It includes memory to maintain contextual conversations.

- [1228-slack-ai-chatbot.json](workflows/1228-slack-ai-chatbot.json)
  Description: This flow configures a chatbot in Slack using n8n, where different slash commands (/ask and /another) trigger responses generated by OpenAI models like gpt-4o-mini. The message is then sent to the specified channel.

- [1229-notion-document-embedding.json](workflows/1229-notion-document-embedding.json)
  Description: This flow automates the processing of Notion documents to generate their embeddings and store them in Supabase.

- [1230-squarespace-sync.json](workflows/1230-squarespace-sync.json)
  Description: Automates the extraction and real-time update of Squarespace blog and event content to Google Sheets.

- [1231-feedback-resumen.json](workflows/1231-feedback-resumen.json)
  Description: This automated workflow analyzes Google Form survey responses via Google Sheets and OpenAI GPT-4 to generate a structured summary that includes an overview of event sentiment, along with improvement ideas.

- [1232-email-to-notion-tasks.json](workflows/1232-email-to-notion-tasks.json)
  Description: This automated flow analyzes incoming emails with AI to create organized and detailed tasks in Notion. It integrates Gmail (to receive emails), Airtable (to manage active routes), and Notion API (to generate pages). It also includes error mechanisms, such as sending notifications to specific emails when problems occur.

- [1233-audio-transcription-process.json](workflows/1233-audio-transcription-process.json)
  Description: This automated flow downloads new audio files from Google Drive and sends them for transcription and sentiment interpretation via OpenAI, generating a structured summary that includes title, main content, and analysis.

- [1234-twitter-ai-influencer-schedule.json](workflows/1234-twitter-ai-influencer-schedule.json)
  Description: This automated flow generates and periodically publishes tweets using artificial intelligence to maintain a specific influencer style.

- [1235-automatizacion-subtitulos-json2video.json](workflows/1235-automatizacion-subtitulos-json2video.json)
  Description: This automated flow uses json2video to generate subtitles in videos on a scheduled basis.

- [1236-jira-retrospective-flow.json](workflows/1236-jira-retrospective-flow.json)
  Description: This automated flow is triggered when an epic in Jira is marked as completed. It collects all task details (titles, descriptions, comments) belonging to that epic and uses a language model to generate a structured document with lessons learned and recommendations.

- [1237-bright-data-gemini-scraping-agent.json](workflows/1237-bright-data-gemini-scraping-agent.json)
  Description: This automated flow uses an AI assistant based on Google Gemini to analyze web scraping queries. It then delegates the task to MCP Client tools (Bright Data) that extract data from specified URLs via webhooks, maintaining context with a buffer memory and storing results in files.

- [1238-telegram-agente-multimedia.json](workflows/1238-telegram-agente-multimedia.json)
  Description: This automated flow allows a Telegram bot to generate textual responses using GPT-4o and images via DALL-E, maintaining contextual memory and addressing the user by name.

- [1239-wordpress-multi-social-publisher.json](workflows/1239-wordpress-multi-social-publisher.json)
  Description: This automated flow allows publishing WordPress content on multiple social networks using language models and structured processing.

- [1240-splunk-jira-ticket-automation.json](workflows/1240-splunk-jira-ticket-automation.json)
  Description: This automated flow processes Splunk alerts to create unique Jira tickets when a corresponding ticket does not exist. If it already exists, it adds comments with the alert details.

- [1241-google-drive-sync.json](workflows/1241-google-drive-sync.json)
  Description: This automated flow synchronizes new files from a specific Google Drive folder, shares their details with a recipient via email, and logs the complete metadata in Airtable for tracking.

- [1242-ultimate-scraper-workflow.json](workflows/1242-ultimate-scraper-workflow.json)
  Description: This automated flow allows extracting information from any webpage, whether public or private, using advanced techniques like Selenium browser automation and analysis with OpenAI language models. Ideal for projects requiring data collection behind WAFs.

- [1243-assistant-tool.json](workflows/1243-assistant-tool.json)
  Description: This automated flow functions as a personal assistant, using specific tools to handle email, calendar, contacts, and web search tasks according to user queries.

- [1244-workflow-dashboard-mermaid.json](workflows/1244-workflow-dashboard-mermaid.json)
  Description: This automated flow allows visualizing and displaying n8n workflow graphs using the mermaid.js library to represent connections between nodes in diagrams.

- [1245-github-n8n-workflow_restore.json](workflows/1245-github-n8n-workflow_restore.json)
  Description: This automated flow allows restoring workflows from a GitHub repository to an n8n instance only if they do not already exist in the workspace.

- [1246-twitter-banner-update.json](workflows/1246-twitter-banner-update.json)
  Description: This flow allows downloading an image from Unsplash and updating it as a Twitter banner via HTTP requests.

- [1247-auto-subir-multimedia.json](workflows/1247-auto-subir-multimedia.json)
  Description: This automated flow allows downloading videos from Google Drive and then extracting their audio to generate descriptions used for simultaneous upload to Instagram and TikTok. It also has a mechanism to notify errors via Telegram.




- [1251-trello-list-updates.json](workflows/1251-trello-list-updates.json)
  Description: This flow monitors and receives updates about changes in a specific Trello list.

- [1252-ausencias_procesamiento.json](workflows/1252-ausencias_procesamiento.json)
  Description: This automated flow collects and processes absence data (vacations and illnesses) from recent months from Google Calendar. It uses regular expressions to filter events related to vacations or illnesses, calculates the hours for each event, and generates a detailed report sent by email to payroll-team@mydomain.tld.

- [1253-notion-clickup-sync.json](workflows/1253-notion-clickup-sync.json)
  Description: This flow synchronizes tasks between Notion and ClickUp. When a Notion database page is updated, the corresponding task status in ClickUp is updated, and vice versa.
- [1254-_damus-report.json](workflows/1254-_damus-report.json)
  Description: Generates Damus reports and sends notifications via Gmail and Telegram.
- [1256-n8n_executions_csv.json](workflows/1256-n8n_executions_csv.json)
  Description: Exports a summary of n8n executions to a CSV file.
- [1258-pdf-to-vector-store.json](workflows/1258-pdf-to-vector-store.json)
  Description: Converts a PDF into vector data for later searches.
- [1259-jira-ticket-autoresolver.json](workflows/1259-jira-ticket-autoresolver.json)
  Description: Automatically resolves Jira tickets according to predefined rules.
- [1261-ai-interview-flow.json](workflows/1261-ai-interview-flow.json)
  Description: Automates interviews using AI-generated questions.
- [1262-thehive-slack-integration.json](workflows/1262-thehive-slack-integration.json)
  Description: Sends case notifications from TheHive to a Slack channel.
- [1263-meeting-reminder-bot.json](workflows/1263-meeting-reminder-bot.json)
  Description: Bot that sends meeting reminders via messaging.
- [1264-slack-image-uploader.json](workflows/1264-slack-image-uploader.json)
  Description: Automatically uploads images to a Slack channel.
- [1265-airtable-baserow-form-connector.json](workflows/1265-airtable-baserow-form-connector.json)
  Description: Connects Airtable forms with Baserow databases.
- [1266-smartlead-processing.json](workflows/1266-smartlead-processing.json)
  Description: Processes Smartlead leads and updates the database.
- [1267-email_subscription_workflow.json](workflows/1267-email_subscription_workflow.json)
  Description: Manages email subscriptions automatically.
- [1268-automatizacion_becas_ai.json](workflows/1268-automatizacion_becas_ai.json)
  Description: Automates scholarship application processing using AI.
- [1269-api-schema-extractor.json](workflows/1269-api-schema-extractor.json)
  Description: Extracts and documents an API schema.
- [1270-email-header-analyzer.json](workflows/1270-email-header-analyzer.json)
  Description: Analyzes an email's headers to obtain metadata.
- [1271-email-header-analyzer.json](workflows/1271-email-header-analyzer.json)
  Description: Analyzes an email's headers to obtain metadata.
- [1272-ai_airtable_agent.json](workflows/1272-ai_airtable_agent.json)
  Description: AI agent that manages records in Airtable.
- [1273-service_now_search_bot.json](workflows/1273-service_now_search_bot.json)
  Description: Bot that searches for information in ServiceNow.
- [1274-proxmox-ai-agent.json](workflows/1274-proxmox-ai-agent.json)
  Description: Agent that automates tasks on Proxmox servers with AI.
- [1275-flujo-seleccion-candidatos-ai.json](workflows/1275-flujo-seleccion-candidatos-ai.json)
  Description: Candidate selection flow assisted by AI.
- [1276-airtable-pdf-llm-update.json](workflows/1276-airtable-pdf-llm-update.json)
  Description: Updates Airtable records with data extracted from PDFs using an LLM.
- [1277-baserow-llm-updates.json](workflows/1277-baserow-llm-updates.json)
  Description: Performs updates in Baserow using a language model.
- [1278-chatbot-citas.json](workflows/1278-chatbot-citas.json)
  Description: Chatbot for automatically scheduling appointments.
- [1279-spotify_to_youtube_sync.json](workflows/1279-spotify_to_youtube_sync.json)
  Description: Syncs Spotify playlists with YouTube.
- [1297-generador_totp.json](workflows/1297-generador_totp.json)
  Description: Generates TOTP codes for two-factor authentication.
- [1392-deep_researcher.json](workflows/1392-deep_researcher.json)
  Description: Deep research agent powered by AI.
- [1393-ai_phone_agent_retell.json](workflows/1393-ai_phone_agent_retell.json)
  Description: AI phone agent using Retell.
- [1394-yoga-line-bot.json](workflows/1394-yoga-line-bot.json)
  Description: LINE bot that sends yoga routines.
- [1395-call-processor.json](workflows/1395-call-processor.json)
  Description: Processes call recordings and extracts information.
- [1396-ai-product-data-processor.json](workflows/1396-ai-product-data-processor.json)
  Description: Processes product data with the help of AI.
- [1397-telegram-tareas.json](workflows/1397-telegram-tareas.json)
  Description: Manages tasks via a Telegram bot.
- [1398-mails2notion.json](workflows/1398-mails2notion.json)
  Description: Converts emails into Notion pages.
- [1399-startups-funding-monitor.json](workflows/1399-startups-funding-monitor.json)
  Description: Monitors startup funding rounds.
- [1400-telegram_survey_bot.json](workflows/1400-telegram_survey_bot.json)
  Description: Telegram bot for surveys.
- [1401-logistica-telegram-flow.json](workflows/1401-logistica-telegram-flow.json)
  Description: Automates logistics notifications via Telegram.
- [1402-edi-processor.json](workflows/1402-edi-processor.json)
  Description: Processes EDI files for electronic data interchange.
- [1403-web-security-audit.json](workflows/1403-web-security-audit.json)
  Description: Performs automated web security audits.
- [1405-team_weekly_report_slack.json](workflows/1405-team_weekly_report_slack.json)
  Description: Sends weekly team reports in Slack.
- [1409-automated_social_media_factory.json](workflows/1409-automated_social_media_factory.json)
  Description: Generates social media content automatically.
- [1413-automate_blog_creation.json](workflows/1413-automate_blog_creation.json)
  Description: Automates blog post creation.
- [1414-spot-discrimination-analysis.json](workflows/1414-spot-discrimination-analysis.json)
  Description: Detects discrimination in text using AI.
- [1415-survey_insights_qdrant.json](workflows/1415-survey_insights_qdrant.json)
  Description: Analyzes survey responses and stores vectors in Qdrant.
- [1416-video-social-generator.json](workflows/1416-video-social-generator.json)
  Description: Generates short videos for social media.
- [1417-bitrix-chatbot-rag.json](workflows/1417-bitrix-chatbot-rag.json)
  Description: Bitrix chatbot with RAG search.
- [1418-telegram-bot-integration.json](workflows/1418-telegram-bot-integration.json)
  Description: Integrates a Telegram bot with external services.
- [1419-youtube-rss-notifications.json](workflows/1419-youtube-rss-notifications.json)
  Description: Sends notifications of new YouTube videos via RSS.
- [1420-graphic-design-flow.json](workflows/1420-graphic-design-flow.json)
  Description: Automates basic graphic design tasks.
- [1421-automated-seo-audit-report.json](workflows/1421-automated-seo-audit-report.json)
  Description: Generates SEO audit reports automatically.
- [1422-analyze_reddit_posts_business_opportunities.json](workflows/1422-analyze_reddit_posts_business_opportunities.json)
  Description: Analyzes Reddit posts for business opportunities.
- [1423-bot_handoff.json](workflows/1423-bot_handoff.json)
  Description: Transfers the conversation from a bot to a human agent.


- [2529-firecrawl-tool.json](workflows/2529-firecrawl-tool.json)
  Description: This flow allows any user to send URLs to get responses from the Firecrawl API and keep them as editable fields in the workflow context.

- [2530-analytics-utm-generator.json](workflows/2530-analytics-utm-generator.json)
  Description: This automated flow creates links with custom UTM parameters from specific inputs, generates QR codes for them, and then uses an OpenAI-based analytical agent to evaluate Google Analytics data.

- [2531-etsy-product-scraper.json](workflows/2531-etsy-product-scraper.json)
  Description: This automated flow uses Bright Data Web Unlocker to perform advanced scraping on Etsy and extracts detailed product information using Google Gemini Flash based on the obtained results.

- [2532-pdf-digital-sign-service.json](workflows/2532-pdf-digital-sign-service.json)
  Description: This automated flow allows the generation of digital keys and certificates for signing PDF documents.

- [2533-redaktionsplan_caption_generator.json](workflows/2533-redaktionsplan_caption_generator.json)
  Description: This automated flow creates social media captions, using an Airtable database and an AI chat model to generate creative and informative texts.

- [2534-news-twitter-post.json](workflows/2534-news-twitter-post.json)
  Description: This automated flow searches for artificial intelligence news via a Perplexity AI query, generates a formatted summary for Twitter/X, and posts it directly to the platform.

- [2535-hubspot-chat-ai-integration.json](workflows/2535-hubspot-chat-ai-integration.json)
  Description: This automated flow allows a HubSpot chatbot to integrate the Assistant function with OpenAI and store references in Airtable to maintain contextualized conversations.

- [2536-billbee-address-validation.json](workflows/2536-billbee-address-validation.json)
  Description: This automated flow validates and corrects order shipping addresses using the Endereco API to verify data in Germany.

- [2537-agricultural-crops-vector-db.json](workflows/2537-agricultural-crops-vector-db.json)
  Description: This automated flow jointly loads agricultural crop images and related data (like plant names) from Google Cloud Storage, generates embeddings using Voyage AI's Multimodal model, and stores them in a Qdrant vector collection. It also checks if the collection already exists to avoid duplication and includes an in-memory index on the plant name (crop_name). Loading is done in batches with a configurable size, thus allowing efficient and fast index creation.


- [2539-lands-knn-classification.json](workflows/2539-lands-knn-classification.json)
  Description: This workflow uses KNN with satellite images to classify landscape types via Voyage AI model embeddings and Qdrant queries. When there are ties, it increases the number of neighbors until a clear majority is found.

- [2540-agricultural-anomaly-detection.json](workflows/2540-agricultural-anomaly-detection.json)
  Description: This flow configures the centers of each agricultural cluster and sets thresholds for anomaly detection in crop images.

- [2541-agricultural-anomaly-detector.json](workflows/2541-agricultural-anomaly-detector.json)
  Description: This flow analyzes crop images to detect if they contain unknown specimens, using multimodal embeddings and a Qdrant vector database.

- [2542-venafi_slack_certbot.json](workflows/2542-venafi_slack_certbot.json)
  Description: This automated flow integrates Slack and Venafi to manage certificate requests based on risk analysis via VirusTotal.

- [2543-openrouter-llm-agent.json](workflows/2543-openrouter-llm-agent.json)
  Description: This flow configures an AI agent that uses different language models via OpenRouter and maintains conversational memory for chats.

- [2544-n8n-chatbot-car-offer.json](workflows/2544-n8n-chatbot-car-offer.json)
  Description: This automated flow allows a LINE chatbot to interact with the sell.peddle.com website to get an offer for a used car. It logs into Airtop, loads the site, and simulates interactions like clicks or typing text when prompted by analysis of the current screen content.

- [2545-visual-regression-testing.json](workflows/2545-visual-regression-testing.json)
  Description: This automated flow allows performing visual regression tests on web pages using Apify to capture images and visual language models like Gemini to detect changes between versions.

- [2546-sql-agent-visualizacion.json](workflows/2546-sql-agent-visualizacion.json)
  Description: This automated flow allows an AI Agent to interact with databases via SQL queries and generate visualizations using Chart.js and Quickchart.io based on user needs. The text classifier decides if a graphical representation is required to improve understanding of results.

- [2547-todoist_weekly_review.json](workflows/2547-todoist_weekly_review.json)
  Description: This automated flow performs a weekly review of completed tasks in Todoist, grouping them by date to generate a daily report sent as an email.

- [2548-cv-error-notification.json](workflows/2548-cv-error-notification.json)
  Description: This workflow detects errors in other tasks (either problems during execution or failures at startup) and sends a detailed email via Gmail to notify about the incident.

- [2549-semanal-shodan-thehive.json](workflows/2549-semanal-shodan-thehive.json)
  Description: This automated flow schedules a weekly scan of IP addresses and their specific ports using Shodan. If it finds unexpected services or behaviors, it generates an alert in TheHive for management.

- [2550-3d-character-generation.json](workflows/2550-3d-character-generation.json)
  Description: This automated flow creates 3D rotation videos and figurine models from images, using PiAPI APIs to generate character designs via Midjourney and integrating them with tools like GPT-4o.

- [2551-traductor-srt.json](workflows/2551-traductor-srt.json)
  Description: This automated flow allows processing SRT files by uploading a form containing the file and selecting the target language. The system extracts text from the binary file, splits it into parts, translates each fragment while maintaining subtitle structure, and finally generates a new file with completed translations.

- [2552-google-sheets-mysql-sync.json](workflows/2552-google-sheets-mysql-sync.json)
  Description: This automated flow synchronizes data between Google Sheets and MySQL via comparisons, updates, and specific conditions.

- [2553-parquet-conversion-flujos.json](workflows/2553-parquet-conversion-flujos.json)
  Description: This flow allows converting Parquet, Avro, ORC, and Feather files to JSON using the ParquetReader API. It starts with a webhook submission that receives the file in binary format, processes it, and returns structured data.

- [2554-x-influencers-list.json](workflows/2554-x-influencers-list.json)
  Description: This automated flow allows searching for influencers on X using Airtop, extracting their data in a structured way, deduplicating results, and incorporating them into a Google document via spreadsheet.

- [2555-workflow-docs.json](workflows/2555-workflow-docs.json)
  Description: This automated flow allows n8n to generate and maintain workflow documentation via Docsify, creating Markdown files based on workflow data.

- [2556-glassdoor-discrimination-analysis.json](workflows/2556-glassdoor-discrimination-analysis.json)
  Description: This automated flow uses ScrapingBee to extract reviews and demographic data from Glassdoor, along with OpenAI models to analyze discriminatory patterns via statistical calculations like z-scores and effect sizes.

- [2557-seatable-webhook-validate.json](workflows/2557-seatable-webhook-validate.json)
  Description: This flow verifies Seatable webhooks via HMAC SHA256 authentication, responding with 200 OK if the hash matches and 403 Forbidden otherwise.

- [2558-bee-hiiv-gumroad-subscribers.json](workflows/2558-bee-hiiv-gumroad-subscribers.json)
  Description: This flow automates adding subscribers to a Beehiiv newsletter every time a sale is made on Gumroad.

- [2560-linkedin-profile-collector.json](workflows/2560-linkedin-profile-collector.json)
  Description: This automated flow uses Google Search via SerpAPI to find relevant LinkedIn profiles, cleans and structures the information using OpenAI, and saves the results in Excel or NocoDB.

- [2561-inteligente-busqueda-web.json](workflows/2561-inteligente-busqueda-web.json)
  Description: This flow uses multiple chains of thought and LLM models to generate optimal queries, perform web searches, and implement a semantic re-ranking system that evaluates results and provides relevant structured information.

- [2562-shopify_google_sync.json](workflows/2562-shopify_google_sync.json)
  Description: This flow automatically synchronizes products from a Shopify store to a Google spreadsheet, using GraphQL to extract data like title, description, tags, and price. It implements efficient pagination using a cursor.

- [2563-vector-db-loader.json](workflows/2563-vector-db-loader.json)
  Description: This automated flow allows loading Google Drive documents into a vector database using OpenAI embeddings and PostgreSQL.

- [2564-twitter-hilo-automatizacion.json](workflows/2564-twitter-hilo-automatizacion.json)
  Description: This automated flow uses Twitter tools and an OpenAI language model to generate coherent and interactive threads, maintaining conversational context.

- [2565-ai-screenshot-analysis.json](workflows/2565-ai-screenshot-analysis.json)
  Description: This flow automates screenshot analysis using artificial intelligence. It first collects the website URL to analyze, then generates a screenshot using the URLbox API, and finally processes it with OpenAI to get a concise textual description in a single paragraph.

- [2566-image-generation-api.json](workflows/2566-image-generation-api.json)
  Description: This automated flow allows generating images from text (prompt) via a web URL.

- [2567-postgres-sync.json](workflows/2567-postgres-sync.json)
  Description: This flow automatically synchronizes data from Google Sheets to a PostgreSQL table, inserting new records or updating existing ones based on key fields.

- [2568-service-page-seo-blueprint.json](workflows/2568-service-page-seo-blueprint.json)
  Description: This flow analyzes the SEO performance of service pages, comparing structures and content with competitors in real-time to create optimized strategies.

- [2569-dataforseo-backlink-checker.json](workflows/2569-dataforseo-backlink-checker.json)
  Description: This flow checks the status (live or dead) of a set of URLs, analyzing them via the DataForSEO API and logging the result in a Google Sheets spreadsheet.

- [2570-drive-video-upload.json](workflows/2570-drive-video-upload.json)
  Description: This automated flow allows uploading videos to Google Drive via a Google Apps Script. It starts with a manual trigger that initiates execution, then sends video URL data (and a secret) to the Google Script web app to process the upload, and finally renames the newly uploaded file.

- [2571-OpenSea-Insights-Telegram.json](workflows/2571-OpenSea-Insights-Telegram.json)
  Description: This automated n8n flow analyzes the NFT market in real-time using OpenAI GPT and connects with specialized agents to answer queries via Telegram.

- [2572-youtube-automation-generative.json](workflows/2572-youtube-automation-generative.json)
  Description: This automated flow allows getting YouTube videos and generating titles, descriptions, and SEO information to automate necessary functions.

- [2573-workflow-ai-investigacion.json](workflows/2573-workflow-ai-investigacion.json)
  Description: This flow uses LLMs to generate search queries, process results, and synthesize a complete research report.

- [2574-maia-health-check.json](workflows/2574-maia-health-check.json)
  Description: This automated flow periodically checks URLs listed in a Google Sheets document via the Schedule Trigger node, and then sends the results of these checks via Telegram bot.

- [2575-wordpress-ai-chatbot.json](workflows/2575-wordpress-ai-chatbot.json)
  Description: This automated flow allows creating and maintaining WordPress content embeddings in Supabase, using OpenAI models to answer questions with contextualized information.

- [2576-AI-WordPress-Article-Creator.json](workflows/2576-AI-WordPress-Article-Creator.json)
  Description: This automated flow uses artificial intelligence to generate SEO articles in WordPress based on keywords provided by the user. It includes creation of titles, subtitles, chapters, and Wikipedia verification.

- [2577-ClockifySlackCopilotWorkflow.json](workflows/2577-ClockifySlackCopilotWorkflow.json)
  Description: This flow automates conversational management of time entries in Clockify via Slack, integrating tools to create, update, and delete records without overlap.

- [2578-analisis-contenido-brand.json](workflows/2578-analisis-contenido-brand.json)
  Description: This automated flow allows a user to configure a URL to extract markdown content, clean it leaving only text, generate a concise summary, and analyze its sentiment with Google Gemini models.

- [2579-escaneo-propiedades.json](workflows/2579-escaneo-propiedades.json)
  Description: This automated flow regularly scans the real estate market, identifies new or modified properties, and filters those with high potential profitability (high capital gain) to send alerts to the sales team via email and Slack.

- [2580-multiple-local-llm-testing.json](workflows/2580-multiple-local-llm-testing.json)
  Description: This automated flow allows testing multiple local LLM models in LM Studio via HTTP requests and detailed response analysis.

- [2581-email-todoist-ai-integration.json](workflows/2581-email-todoist-ai-integration.json)
  Description: This flow automates converting emails into Todoist tasks using the GPT-4o-mini model for summaries and action proposals.

- [2582-auto-article-generation.json](workflows/2582-auto-article-generation.json)
  Description: This automated flow uses the Perplexity model to generate initial content and then refines it through iterations using OpenAI generative models, finally publishing it on a platform like Contentful.

- [2583-prospectlens_company_research.json](workflows/2583-prospectlens_company_research.json)
  Description: This automated flow uses the ProspectLens API to get company data and update a Google Sheets spreadsheet while maintaining a record of the processing time.

- [2584-youtube-video-analysis.json](workflows/2584-youtube-video-analysis.json)
  Description: This flow analyzes YouTube videos to generate summaries, transcripts, and detailed scene descriptions. It allows choosing the analysis type via the 'promptType' variable (transcript, summary, scene) and incorporates a Gemini model for processing.

- [2586-shopify-campaign-sync.json](workflows/2586-shopify-campaign-sync.json)
  Description: This n8n flow allows saving .liquid files to the Shopify theme after uploading images using GraphQL, optimizing advertising campaign creation.

- [2587-youtube-sentiment-analyzer.json](workflows/2587-youtube-sentiment-analyzer.json)
  Description: This flow automatically analyzes YouTube video comments from a Google Sheets list using the YouTube API and OpenAI's AI to categorize them as positive, neutral, or negative.

- [2588-image-meta-tagging-automation.json](workflows/2588-image-meta-tagging-automation.json)
  Description: This automated flow analyzes the content of images uploaded to a specific Google Drive folder and directly writes the description as tags in the file's XMP metadata.

- [2589-csv_to_excel_conversion.json](workflows/2589-csv_to_excel_conversion.json)
  Description: This automated flow imports a CSV file from a specific URL and converts it to .xlsx format.

- [2590-cal-booking-distribution.json](workflows/2590-cal-booking-distribution.json)
  Description: This automated flow is triggered when a new appointment is created in Cal.com and automatically adds each attendee to Google Sheets and Beehiiv, in addition to notifying via Telegram.

- [2591-chatbot-jina-scraper.json](workflows/2591-chatbot-jina-scraper.json)
  Description: This automated flow allows a chatbot to integrate real-time web scraping via Jina.ai to intelligently answer queries.

- [2592-multipage-scraper.json](workflows/2592-multipage-scraper.json)
  Description: This automated flow allows extracting and storing the content of multiple web pages from a sitemap.xml file in Google Drive using the Jina.ai API for intelligent searches.

- [2593-seo-blog-generator-flujo-automatico.json](workflows/2593-seo-blog-generator-flujo-automatico.json)
  Description: This automated flow allows a user to send a research query related to men's health topics to be processed by multiple AI nodes, generating structured content like titles, subtitles, and hashtags based on the provided information. It then uses this structure along with research gathered via Perplexity.ai to create a complete blog article.

- [2594-bluesky-post-automation.json](workflows/2594-bluesky-post-automation.json)
  Description: This automated flow allows publishing posts with images on Bluesky, handling session authentication and file sending.

- [2595-line-chatbot-ai.json](workflows/2595-line-chatbot-ai.json)
  Description: This automated flow allows a LINE chatbot to maintain conversations using Groq and Llama3, sending incoming messages as requests to the AI to generate responses.

- [2596-image-to-3d-conversion.json](workflows/2596-image-to-3d-conversion.json)
  Description: This automated flow allows converting an image into a 3D model (.glb) using the Fal.ai API and then saving the result to Google Drive.

- [2597-monitor-ia-articulos-slack.json](workflows/2597-monitor-ia-articulos-slack.json)
  Description: This automated flow monitors relevant articles in real-time using RSS feeds, classifies their content with AI, and generates formatted summaries for Slack.

- [2598-shopware-multi-manufacturer-import.json](workflows/2598-shopware-multi-manufacturer-import.json)
  Description: This automated flow allows importing multiple manufacturers from a Google sheet to Shopware 6 via batch processing. It configures necessary parameters and creates HTTP requests with encrypted data for logos and multilingual information.

- [2599-workflow-nodes-update-check-template.json](workflows/2599-workflow-nodes-update-check-template.json)
  Description: This flow checks for outdated nodes in n8n workflows, adds new nodes with more recent versions, and renames existing ones to maintain consistency.

- [2600-news-pipeline.json](workflows/2600-news-pipeline.json)
  Description: This automated flow extracts press articles, filters them by age (7 days), generates summaries and keywords using ChatGPT, and stores everything in a SQL database.

- [2601-facturacion-automatizada.json](workflows/2601-facturacion-automatizada.json)
  Description: This automated flow downloads attachments from unread emails in Gmail and saves them to Google Drive. It then uses OpenAI to extract key data from invoices (date, description, total price), which are stored in a structured schema and finally incorporated into a spreadsheet.

- [2602-kling-try-on-video-generator.json](workflows/2602-kling-try-on-video-generator.json)
  Description: This automated flow allows generating videos with 360-degree virtual try-ons using the Kling API, first processing images and then generating the final video when available.

- [2603-suspicious-login-detection.json](workflows/2603-suspicious-login-detection.json)
  Description: This n8n flow detects suspicious account logins by integrating data from IP-API, UserParser, and GreyNoise. It analyzes new locations or different devices/browsers to determine if it is a fraudulent attempt.

- [2604-discord-chat-agent.json](workflows/2604-discord-chat-agent.json)
  Description: This automated flow allows a chatbot to interact with Discord while maintaining conversation context via memory.

- [2605-Colombian-Invoices-Processor.json](workflows/2605-Colombian-Invoices-Processor.json)
  Description: This automated flow processes Colombian electronic invoices received by email, verifying key data like taxes and subtotals, and stores them in Google Sheets using the country's tax regulations.

- [2606-youtube-trend-analysis-memory.json](workflows/2606-youtube-trend-analysis-memory.json)
  Description: This automated flow analyzes YouTube video data using tools like search and LangChain engine processing, then stores it in memory for later use. It also integrates an initial verification via chatTrigger that determines if the user provided a niche before proceeding.

- [2608-youtube-transcript-extractor.json](workflows/2608-youtube-transcript-extractor.json)
  Description: This flow allows extracting and cleaning transcribed text from a YouTube video using the RapidAPI.

- [2609-monitor-precios-competicion.json](workflows/2609-monitor-precios-competicion.json)
  Description: This automated flow monitors competitor prices via Google Sheets, queries and processes the response with Airtop to detect significant price or planning changes, updates the record only when there are substantial differences, and sends Slack notifications if changes are detected.

- [2610-icp_linkedin_scoring.json](workflows/2610-icp_linkedin_scoring.json)
  Description: This n8n flow automatically calculates Ideal Customer Profile (ICP) scores for companies based on their LinkedIn pages, using Airtop for analysis and Google Sheets to store and integrate data.

- [2611-github-workflow-restore.json](workflows/2611-github-workflow-restore.json)
  Description: This automated flow allows restoring n8n workflows from a GitHub repository.

- [2612-zammad-roles-excel.json](workflows/2612-zammad-roles-excel.json)
  Description: This automated flow allows downloading an Excel file from a previously configured URL and updating user roles in Zammad based on the data contained within it.

- [2613-airflow-dag-monitor.json](workflows/2613-airflow-dag-monitor.json)
  Description: This automated flow allows initiating an Airflow DAG execution via an API and verifying its status to take necessary actions.

- [2614-custom-ai-agent-memory.json](workflows/2614-custom-ai-agent-memory.json)
  Description: This flow configures a custom AI agent with specific features like personality, conversation topics, and response styles in Chinese. Interaction is done via the integrated chat in n8n.

- [2615-jira-notion-sync.json](workflows/2615-jira-notion-sync.json)
  Description: This automated flow synchronizes the creation, modification, and deletion of Jira issues with entries in a specific Notion database.

- [2616-medium_linkedin_automation.json](workflows/2616-medium_linkedin_automation.json)
  Description: This automated flow searches for random Medium articles using predefined tags, checks if they haven't been used already via an Airtable record, creates LinkedIn posts with their images, and sends an alert for each successful post.

- [2617-woocommerce-ai-product-importer.json](workflows/2617-woocommerce-ai-product-importer.json)
  Description: This workflow automates product import in WooCommerce via Google Sheets. It analyzes product details to generate SEO-optimized meta titles and meta descriptions, creates them immediately in the WordPress catalog, and inserts this information directly into a spreadsheet.

- [2618-gemini-image-data-extractor.json](workflows/2618-gemini-image-data-extractor.json)
  Description: This flow creates an API to extract data from images using Gemini AI, requires sending an image URL and a set of instructions defining what information should be extracted.

- [2619-line-chatbot-memory.json](workflows/2619-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using memory for each user.

- [2620-n8n-workflow-clone.json](workflows/2620-n8n-workflow-clone.json)
  Description: This flow allows cloning workflows between different n8n instances via API, processing batches to optimize performance.

- [2621-vector-paquete.json](workflows/2621-vector-paquete.json)
  Description: This automated flow extracts texts from JSON files on FTP, splits them into fragments, and stores them as embeddings in a Qdrant vector database to facilitate semantic searches.

- [2622-auto-content-wordpress.json](workflows/2622-auto-content-wordpress.json)
  Description: This automated flow allows generating complete HTML content with SEO-optimized titles and specific keywords, in addition to incorporating an image from Pexels each time an article is published on WordPress.

- [2623-wordpress-xmlrpc-posting.json](workflows/2623-wordpress-xmlrpc-posting.json)
  Description: This automated flow uses n8n along with the XML-RPC protocol to publish articles on WordPress.com.

- [2624-OpenSeaAnalyticsAgent.json](workflows/2624-OpenSeaAnalyticsAgent.json)
  Description: This automated flow implements a conversational agent with memory that analyzes NFT data using the OpenSea API.

- [2625-monitor-advisories-paloalto.json](workflows/2625-monitor-advisories-paloalto.json)
  Description: This flow monitors Palo Alto security advisories, filters them by keywords like GlobalProtect or Traps, checks if they were published in the last day, and creates Jira issues or sends emails to relevant customers.

- [2626-stripe-payment-auto.json](workflows/2626-stripe-payment-auto.json)
  Description: This automated flow allows receiving payment notifications via the 'checkout.session.completed' webhook and automatically extracting customer (name, email) and product information via a subsequent HTTP call to the Stripe API.

- [2627-whatsapp-webhook-echo.json](workflows/2627-whatsapp-webhook-echo.json)
  Description: This workflow verifies a webhook with a GET request and responds to POST Requests containing user messages, sending these messages as replies on WhatsApp.

- [2628-error-limitacion.json](workflows/2628-error-limitacion.json)
  Description: This automated flow allows logging errors in a PostgreSQL database but limits notifications to a maximum of one every five minutes.

- [2629-flujo_verificacion_lead.json](workflows/2629-flujo_verificacion_lead.json)
  Description: This automated flow verifies the validity of emails in forms and, if valid, sends them to Gmail, updates a Google Sheets spreadsheet, and notifies via Discord.

- [2630-dumpling-ai-maps-business-leads.json](workflows/2630-dumpling-ai-maps-business-leads.json)
  Description: This automated flow allows extracting information from business places on Google Maps via the Dumpling AI API and saving it in a structured spreadsheet.

- [2631-email-to-tasks.json](workflows/2631-email-to-tasks.json)
  Description: This flow automatically creates tasks in Google Tasks upon receiving a new email with the 'To-Do' label.

- [2632-line-chatbot-memory.json](workflows/2632-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain contextualized conversations using the GPT-4o-mini model and access information via tools like Wikipedia, Google Calendar, and Gmail.

- [2633-icypeas-email-search.json](workflows/2633-icypeas-email-search.json)
  Description: This automated flow allows a user to trigger a specific email search using the Icypeas service. Steps include authentication via API key, API secret, and User ID in a custom node that requires activating the crypto module in self-hosted n8n.

- [2634-opensea-nft-agent.json](workflows/2634-opensea-nft-agent.json)
  Description: This automated flow allows an n8n chatbot to interact with the OpenSea API to retrieve and process specific NFT data.

- [2635-bright_data_gemini_search.json](workflows/2635-bright_data_gemini_search.json)
  Description: This automated flow searches web data using Perplexity, extracts relevant information with LangChain, and uses Gemini AI to generate summaries.

- [2636-monday-boarditem-hierarchy.json](workflows/2636-monday-boarditem-hierarchy.json)
  Description: This automated flow gets all fields of a board item along with its relationships and sub-items to process complete data.

- [2637-line-bitrix-task-integration.json](workflows/2637-line-bitrix-task-integration.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation and update user information in Bitrix24 to manage tasks.

- [2638-telegram-github-agent.json](workflows/2638-telegram-github-agent.json)
  Description: Automates the curation and publication on Telegram of featured GitHub project discussions from Hacker News.

- [2639-oidc-client-auth-flow.json](workflows/2639-oidc-client-auth-flow.json)
  Description: This automated n8n flow implements the OIDC (OpenID Connect) protocol to authenticate users and get information about them. It starts with a webhook that captures incoming requests, then processes authentication cookies. Afterwards, it checks if a token is present or a code is received in the URL to continue getting user data.

- [2640-shopify-orders-to-baserow.json](workflows/2640-shopify-orders-to-baserow.json)
  Description: This automated flow executes a daily GraphQL query to get Shopify orders and inserts them into a Baserow-based table, extracting UTM parameters from the first visit. Only orders where the 'Campaign' field is present are processed.

- [2641-csv-google-sheets-import.json](workflows/2641-csv-google-sheets-import.json)
  Description: This flow allows importing multiple CSV files from a local folder to Google Sheets, removing duplicates and keeping only subscribers.

- [2642-gmail_vector_embeddings_import.json](workflows/2642-gmail_vector_embeddings_import.json)
  Description: This automated flow imports Gmail emails and stores them as vector embeddings in PostgreSQL using PGVector and the Ollama model to facilitate similar searches.

- [2643-api-moa-googleSheets.json](workflows/2643-api-moa-googleSheets.json)
  Description: This automated flow collects sheep quotation data from the Ministry of Agriculture API via an HTTP request, splits it, and then adds it as new rows to a specific Google Sheets file.

- [2644-openai-form-dynamic.json](workflows/2644-openai-form-dynamic.json)
  Description: This automated flow allows a chatbot to dynamically generate forms based on user responses and analysis of a previous open-ended question, thus avoiding asking for redundant information.

- [2645-v1-param-audit.json](workflows/2645-v1-param-audit.json)
  Description: This flow analyzes the parameters of all nodes in active flows to identify those containing expressions affected by changes in n8n v1.

- [2646-telegram-helpdesk-chatbot.json](workflows/2646-telegram-helpdesk-chatbot.json)
  Description: This automated flow allows a Telegram chatbot to maintain a contextualized conversation with users using vector storage in PostgreSQL and chat memory for personalized responses.

- [2647-whatsapp-ai-chatbot.json](workflows/2647-whatsapp-ai-chatbot.json)
  Description: This automated flow allows a WhatsApp chatbot to intelligently analyze and respond to different types of messages: text, voice, images, and PDFs.

- [2648-travel-planner-mongodb.json](workflows/2648-travel-planner-mongodb.json)
  Description: This flow acts as a travel planning assistant that uses MongoDB conversational memory and Atlas vector store to search for points of interest.

- [2649-zoom-ai-meeting-auto.json](workflows/2649-zoom-ai-meeting-auto.json)
  Description: This automated flow processes Zoom meeting transcripts with AI to generate email summaries, create tasks in ClickUp, and schedule follow-up calls.

- [2650-shopify-odoo-customer-sync.json](workflows/2650-shopify-odoo-customer-sync.json)
  Description: This flow automatically synchronizes new Shopify customers with contacts in Odoo, first checking if a matching contact already exists and creating it if not found.

- [2651-ai_tshirt_redesign.json](workflows/2651-ai_tshirt_redesign.json)
  Description: This flow analyzes a t-shirt design image using an AI model, like GPT-4o, and generates an improved prompt to create an artistic visual redesign using generative models.

- [2652-youtube-performance-searcher.json](workflows/2652-youtube-performance-searcher.json)
  Description: This flow searches for the best YouTube videos in the last two weeks and stores them in a PostgreSQL database.

- [2653-line-chatbot-memory.json](workflows/2653-line-chatbot-memory.json)
  Description: This flow allows a LINE chatbot to maintain a contextualized conversation using historical memory stored in Google Sheets.

- [2654-comparador-multiples-modelos.json](workflows/2654-comparador-multiples-modelos.json)
  Description: This flow allows comparing multiple language model responses while maintaining separate memory per model.
- [2655-_Generate_AI-Ready_llms.txt_Files_from_Screaming_Frog.json](workflows/2655-_Generate_AI-Ready_llms.txt_Files_from_Screaming_Frog.json)
  Description: Transforms a CSV exported from Screaming Frog into an optimized `llms.txt` file containing titles, URLs, and indexability information, making it easier for language models to crawl and classify.


- [2656-pipedrive-enrichment-flow.json](workflows/2656-pipedrive-enrichment-flow.json)
  Description: This automated flow scans the website of a newly created organization in Pipedrive to generate a detailed summary using GPT-4o, allowing updated and integrated data directly in the CRM system.

- [2657-calendar-agent.json](workflows/2657-calendar-agent.json)
  Description: This automated flow allows a chatbot to interact with the user's calendar, creating individual or attendee events, getting schedules, and deleting them. The Google Calendar conversational agent uses GPT models to handle requests.

- [2658-agente-contact-ai.json](workflows/2658-agente-contact-ai.json)
  Description: This flow allows the AI agent to interact with Airtable using contact search or update.

- [2659-content-creator-agent.json](workflows/2659-content-creator-agent.json)
  Description: This automated flow uses the Tavily tool to search for information on the internet about a specific topic provided by the user, and then employs an Anthropic Chat Model language model to generate well-structured HTML content for blogs. Connections ensure a web search is performed first before requesting the AI assistant to write the article.

- [2660-email-agent.json](workflows/2660-email-agent.json)
  Description: This automated flow allows a chatbot to interact with email accounts to manage tasks like sending, replying, and labeling emails.

- [2661-youtube-transcripciones-resumen.json](workflows/2661-youtube-transcripciones-resumen.json)
  Description: This automated flow allows a user to send a YouTube URL via Webhook to get its video ID and then extract the video title and description. Subsequently, the video transcript along with gpt-4o-mini is used to generate structured summaries with definitions, features, implementation details, and pros/cons, formatted in markdown.

- [2662-vision-based-scraping.json](workflows/2662-vision-based-scraping.json)
  Description: This flow uses Gemini AI to extract data from web screenshots and integrates the results into Google Sheets.

- [2663-n8n-image-editor-flux-fill.json](workflows/2663-n8n-image-editor-flux-fill.json)
  Description: This flow allows processing images via inpainting with the FLUX Fill tool, integrating user interactions in a visual editor based on Konva.js.

- [2664-deepseek-ia-flujo.json](workflows/2664-deepseek-ia-flujo.json)
  Description: This automated flow allows integrating the DeepSeek Reasoner and Chat V3 AI model while maintaining conversational context via memory.

- [2665-telegram-deepseek-bot.json](workflows/2665-telegram-deepseek-bot.json)
  Description: This automated flow allows a chatbot to interact with Telegram users by integrating the DeepSeek-V3/Chat AI model. It analyzes messages, verifies user data, maintains long-term memory in Google Docs, and responds in a personalized manner.

- [2666-ft-news-resumen.json](workflows/2666-ft-news-resumen.json)
  Description: This automated flow daily collects financial news from FT.com, organizes it by specifically extracting content using CSS Selectors, summarizes it with a Google Gemini model in HTML format, and sends the structured summary to an Outlook inbox.

- [2667-auto-doc-gpt-docsify.json](workflows/2667-auto-doc-gpt-docsify.json)
  Description: This automated flow generates Markdown documentation for n8n workflows using GPT and Docsify, allowing creation of interactive pages with visual schemas (Mermaid) describing each node.

- [2668-perplexity-html-creator.json](workflows/2668-perplexity-html-creator.json)
  Description: This automated flow uses the Perplexity AI research tool to generate HTML content based on a provided topic. The system analyzes the user's topic, calls the Perplexity API with the specified model, and processes the response to extract JSON and convert it to HTML following formatting guidelines.

- [2669-ollama-chat-ai.json](workflows/2669-ollama-chat-ai.json)
  Description: This flow processes chat messages via local language models in Ollama and returns structured JSON responses.

- [2670-n8n_creators_leaderboard_stats.json](workflows/2670-n8n_creators_leaderboard_stats.json)
  Description: This flow automates obtaining and processing statistical data from the n8n creators leaderboard to generate detailed reports in Markdown format on a user's specific contributions.

- [2671-performance-testing-multi-llm.json](workflows/2671-performance-testing-multi-llm.json)
  Description: This automated flow allows multiple tests of local language models (LLM) via the LM Studio server, analyzing metrics like readability score and average word length for each response.

- [2672-telegram-multimedia-ai.json](workflows/2672-telegram-multimedia-ai.json)
  Description: This automated flow allows processing Telegram messages (text, voice, and photos) using language models for classification or analysis.

- [2673-n8n-leaderboard-ai-agente.json](workflows/2673-n8n-leaderboard-ai-agente.json)
  Description: This automated flow collects statistics from n8n creators and flows from GitHub, processes the information with artificial intelligence to generate a detailed report in Markdown format, converts it to HTML if necessary, and shares it via email or Telegram.

- [2674-ai-chatbot-memory.json](workflows/2674-ai-chatbot-memory.json)
  Description: This automated flow allows a chatbot to store and retrieve long-term memory and specific information in Google Docs to maintain contextualized conversations via Telegram.

- [2675-stripe-hubspot-sync.json](workflows/2675-stripe-hubspot-sync.json)
  Description: This flow synchronizes Stripe charges with HubSpot contacts. It searches and sums captured amounts per customer, creating or updating a custom property in HubSpot to show the total spent.

- [2676-workflow-hubspot-lead.json](workflows/2676-workflow-hubspot-lead.json)
  Description: This automated flow manages Lead integration in Lemlist and updates information in HubSpot, notifying relevant teams about sales opportunities. It includes steps to search or create company accounts, update contact profiles, and send Slack notifications.

- [2677-reddit-n8n-monitor.json](workflows/2677-reddit-n8n-monitor.json)
  Description: This flow automates monitoring Reddit posts related to n8n, using OpenAI to classify and summarize relevant ones.

- [2678-gmail-to-drive-pdfs.json](workflows/2678-gmail-to-drive-pdfs.json)
  Description: This automated flow sends specific PDF attachments from an email to Google Drive using OpenAI to filter and upload only those matching a determined term.

- [2679-chatgpt-email-sheets.json](workflows/2679-chatgpt-email-sheets.json)
  Description: This automated flow manages ChatGPT responses to specific emails and logs interactions in Google Sheets.

- [2680-reporte-notion-slack.json](workflows/2680-reporte-notion-slack.json)
  Description: This flow automates the creation of weekly reports summarizing entries from a Notion database containing product ideas. Every Sunday at 8:00 AM, it queries the last 7 days and sends a message to the #nik-wf-testing channel on Slack with the unique count of UX ideas.

- [2681-notion-gmail-sinc.json](workflows/2681-notion-gmail-sinc.json)
  Description: This flow automates synchronizing labeled emails to a Notion database. It searches for specific emails every minute, creates new pages if they don't exist, and removes labels once processed.

- [2682-compare-datasets-frutas.json](workflows/2682-compare-datasets-frutas.json)
  Description: This flow compares two datasets of fruits and colors using the Compare Datasets node to identify differences.

- [2683-podcast_workflow.json](workflows/2683-podcast_workflow.json)
  Description: This automated flow processes a podcast episode by splitting its transcript, summarizing it, and generating related questions and topics, then formats the information into HTML and sends it via Gmail.

- [2684-threat-intelligence-scan.json](workflows/2684-threat-intelligence-scan.json)
  Description: This flow automates cyber threat inspection by performing analyses on VirusTotal and Greynoise. It receives URLs or IPs via a form or Webhook, performs DNS Lookup to get IPs, sends to VirusTotal for scanning and queries Greynoise, combining results to send detailed reports via email and Slack.

- [2685-email_campaign_generator.json](workflows/2685-email_campaign_generator.json)
  Description: This flow automates the creation of personalized email campaigns using purchase data and customer feedback. It uses OpenAI to generate engaging content and decides whether to send a promotional coupon.

- [2686-nextcloud_folder_migration.json](workflows/2686-nextcloud_folder_migration.json)
  Description: This automated flow migrates folders and their subfiles and subfolders to a specified Nextcloud location, ensuring structural integrity and avoiding rate limit exceeding.

- [2687-flujo-verificacion-voz-correo.json](workflows/2687-flujo-verificacion-voz-correo.json)
  Description: This automated flow sends voice messages for verification and then verifies the code via email.

- [2688-data_extraction_bright_google.json](workflows/2688-data_extraction_bright_google.json)
  Description: This flow extracts and analyzes structured data from a webpage using Bright Data Web Unlocker and Google Gemini to perform data mining tasks, including thematic analysis and sentiment extraction.

- [2689-printify-update-product.json](workflows/2689-printify-update-product.json)
  Description: Automates updating product titles and descriptions in Printify via Google Sheets. The workflow uses Printify API to get store and product data, processes each product to generate custom title and description options using OpenAI, and updates them in Google Sheets.

- [2690-blockchain_dex_insights_agent.json](workflows/2690-blockchain_dex_insights_agent.json)
  Description: This automated flow acts as an insights agent for DEX blockchain, using different analysis tools and the DexScreener API to provide real-time information on tokens and trading pairs.

- [2691-dialpad_syncro.json](workflows/2691-dialpad_syncro.json)
  Description: This flow automates data synchronization between Dialpad and Syncro. It receives an inbound call notification, searches for the customer in Syncro, creates a ticket if the customer doesn't exist or updates their status, and logs the information in Google Sheets.

- [2692-http-web-content-processor.json](workflows/2692-http-web-content-processor.json)
  Description: This flow processes an HTTP request to get webpage content, converts it to Markdown, and applies limitations like removing links and images if the method is simplified. It handles errors and formats the output according to provided parameters.

- [2693-búsqueda_correo_icypeas.json](workflows/2693-búsqueda_correo_icypeas.json)
  Description: This flow configures a bulk email search using Icypeas. It reads data from a Google spreadsheet with personal information and authenticates the user to make a POST request to the Icypeas API, generating a necessary SHA1 signature for the process.

- [2694-dominio_icypeas.json](workflows/2694-dominio_icypeas.json)
  Description: This flow automates the execution of a bulk domain analysis using Icypeas. It reads data from a Google spreadsheet, authenticates with the Icypeas account, and sends a POST request to perform mass searches.

- [2695-g2_reviews_monitor.json](workflows/2695-g2_reviews_monitor.json)
  Description: This automated flow extracts and monitors recent G2 reviews for competitors like Zendesk, Intercom, and Dixa using ScrapingBee. It notifies of new reviews on Slack and logs them in Google Sheets.

- [2696-country_capitals_fiction.json](workflows/2696-country_capitals_fiction.json)
  Description: This flow uses ChatGPT to answer questions about capitals of fictional countries. The user can ask for a list of countries or the capital of a specific country.

- [2697-shopify-inventory-alert.json](workflows/2697-shopify-inventory-alert.json)
  Description: Flow to monitor and notify when Shopify products are low on stock or out of stock by sending messages to Discord with product details.

- [2699-telegram-support-flow.json](workflows/2699-telegram-support-flow.json)
  Description: This automated flow manages Telegram messages via a bot, creating custom topics for each user and forwarding messages to the support group or Broadcast channel. It uses Redis to store data and ensure message integrity.

- [2700-cloudflare_kv_management.json](workflows/2700-cloudflare_kv_management.json)
  Description: This flow manages Cloudflare KV Storage operations like listing, creating, deleting, and renaming namespaces, as well as performing specific actions with key-value pairs.

- [2701-songkick-event-email.json](workflows/2701-songkick-event-email.json)
  Description: This automated flow extracts and processes music event information from Songkick, PagerDuty-style, sending an email with formatted details to the user monthly.

- [2702-meraki-network-monitor.json](workflows/2702-meraki-network-monitor.json)
  Description: This automated flow monitors and analyzes latency and packet loss data in Meraki networks to detect issues, notifying only those exceeding thresholds via Redis.

- [2703-google_maps_scraper.json](workflows/2703-google_maps_scraper.json)
  Description: This flow extracts and processes Google Maps data using SerpAPI, removes duplicates, formats them, and updates status in Google Sheets.

- [2704-switchy-url-shortener.json](workflows/2704-switchy-url-shortener.json)
  Description: This flow processes URLs to generate and shorten them using Switchy.io. It analyzes metadata, verifies security with Norton and Bitdefender, and handles different OpenGraph image modes.

- [2705-automated-tasks-creator.json](workflows/2705-automated-tasks-creator.json)
  Description: This automated flow creates tasks in Airtable based on templates and updates records with calculated dates.

- [2706-airtable-csv-uploader.json](workflows/2706-airtable-csv-uploader.json)
  Description: This automated flow processes and uploads data from a CSV file to Airtable. It detects if the campaign is not empty, marks the processing status, downloads the file, creates records in Airtable, and updates the status to 'Uploaded' or 'Failed'.

- [2707-dropbox-backup-cleanup.json](workflows/2707-dropbox-backup-cleanup.json)
  Description: This automated flow schedules periodic tasks for Workflow Backup and cleanup in Dropbox. Daily, it copies current Workflows to an 'OLD' folder and deletes backups older than 30 days.

- [2708-piloterr-fundraising-scraping.json](workflows/2708-piloterr-fundraising-scraping.json)
  Description: This automated flow extracts recent funding information from Crunchbase for Series A, B, and Seed, enriches it with additional data from LinkedIn and Semrush, and exports it to Google Sheets.

- [2709-email-to-telegram.json](workflows/2709-email-to-telegram.json)
  Description: This flow automates reading emails from an IMAP account and converting them into HTML pages hosted on GitHub Gist, sending notifications to Telegram with an access link. After 3 hours, it deletes the Gist file.

- [2710-youtube-sum-resumen.json](workflows/2710-youtube-sum-resumen.json)
  Description: This flow extracts text from a YouTube video using searchapi.io and summarizes it with LangChain and OpenAI to generate detailed summaries with example questions.

- [2711-google-sheet-ai-agent.json](workflows/2711-google-sheet-ai-agent.json)
  Description: This flow uses an artificial intelligence agent to interact with a Google Sheets spreadsheet, allowing listing columns, getting specific values, and retrieving customer information based on defined operations.

- [2712-automated-email-flow.json](workflows/2712-automated-email-flow.json)
  Description: This flow automates managing pending messages to send emails. It retrieves data from a Google Sheets spreadsheet, filters entries based on 'Waiting to be sent' status and current date, configures necessary data, sends emails via Gmail, and updates the status in the spreadsheet.

- [2713-chat-agent-postgres.json](workflows/2713-chat-agent-postgres.json)
  Description: This flow uses a language agent to process chat messages, employing simple memory and a PostgreSQL database to support system-generated SQL queries.

- [2714-ai-agent-slack-transfer.json](workflows/2714-ai-agent-slack-transfer.json)
  Description: Flow that implements an AI chat agent capable of transferring conversations to Slack if the user does not provide an email address.

- [2715-discord-to-sheets-sync.json](workflows/2715-discord-to-sheets-sync.json)
  Description: This flow automates synchronizing active Discord members with Google Sheets. It extracts information from Discord, filters by roles, and maintains a record in a spreadsheet.

- [2716-form-to-email-notificacion.json](workflows/2716-form-to-email-notificacion.json)
  Description: This flow collects data from a form where users enter their role and email. It then checks if the email is not personal using Clearbit to enrich information. If it meets certain criteria, it sends an email.

- [2717-linkedin-email-finder.json](workflows/2717-linkedin-email-finder.json)
  Description: This flow automates updating contact information in Google Sheets using the Prospeo.io API to find emails via LinkedIn URLs.

- [2718-intercom-enrich-user-flow.json](workflows/2718-intercom-enrich-user-flow.json)
  Description: This flow automates enriching newly created user data in Intercom via API. It receives Intercom notifications, verifies the 'contact.user.created' event, extracts information, and queries ExactBuyer to update details like email, phone, location, and social profiles.

- [2719-discourse-slack-notifications.json](workflows/2719-discourse-slack-notifications.json)
  Description: This flow automates Slack notifications for new highly-rated users in Discourse, filtering personal emails and verifying business data via Clearbit.

- [2720-leadfeeder-to-googlesheets.json](workflows/2720-leadfeeder-to-googlesheets.json)
  Description: This automated flow extracts and enriches Lead data from Leadfeeder, filters by company and engagement, and exports it to Google Sheets.

- [2721-email-verification-flow.json](workflows/2721-email-verification-flow.json)
  Description: This flow verifies email validity, gets company and person information from Clearbit, and adds a lead to Hubspot if the email is valid.

- [2722-asignacion-deal-hubspot.json](workflows/2722-asignacion-deal-hubspot.json)
  Description: This automated flow schedules daily tasks to get HubSpot deals and assign them to different sellers based on regions and company size.

- [2723-lead-generation-flow.json](workflows/2723-lead-generation-flow.json)
  Description: This automated flow collects Leads via a web form, verifies email validity using Hunter, evaluates customer profile with MadKudu, and if interesting (score >60), sends an outreach email via Gmail and logs the interaction in HubSpot.

- [2724-social-activity-email.json](workflows/2724-social-activity-email.json)
  Description: This automated flow collects recent Twitter tweets and LinkedIn posts from companies and sends an email with social activity to configured email addresses.

- [2725-flujo-automatico-diario.json](workflows/2725-flujo-automatico-diario.json)
  Description: This automated flow schedules daily tasks to extract and process calendar, LinkedIn, and Twitter information, enrich data with Clearbit, and send an email with a personalized summary.

- [2726-crm-enrichment-flow.json](workflows/2726-crm-enrichment-flow.json)
  Description: This flow automates the process of enriching and managing contact and company data via Clearbit and Hubspot. It detects if a company exists in CRM; otherwise, it creates or updates it with detailed information. It also validates and filters emails to avoid personal addresses.

- [2727-crm-enrich-flow.json](workflows/2727-crm-enrich-flow.json)
  Description: This automated n8n flow uses Clearbit and Hubspot to enrich company and contact data. It detects if a company exists in the CRM, creates or updates records accordingly, and manages Leads in ConvertKit. It filters non-personal emails and intelligently manages contacts.

- [2728-automatizacion-leads-pipedrive.json](workflows/2728-automatizacion-leads-pipedrive.json)
  Description: This flow automates Pipedrive lead management via Clearbit and Slack. It searches for unarchived leads with B2B tags and more than 10 employees, enriches them with Clearbit business data, marks as enriched, and notifies Slack.

- [2729-form-to-pipedrive.json](workflows/2729-form-to-pipedrive.json)
  Description: This flow uses forms to collect emails, verifies their validity with Hunter.io, gets information from Clearbit, and creates or updates records in Pipedrive.

- [2730-slack-command-flow.json](workflows/2730-slack-command-flow.json)
  Description: This flow handles Slack commands, validates tokens, creates threads, and executes workflows according to configuration. It responds to users with help or unknown commands.

- [2731-woocommerce-chatbot.json](workflows/2731-woocommerce-chatbot.json)
  Description: This automated flow allows a chatbot to retrieve and display WooCommerce order information based on the user's email address. It uses encryption tools to protect sensitive data and services like DHL for shipment tracking.

- [2732-vector-chatbot-pinecone.json](workflows/2732-vector-chatbot-pinecone.json)
  Description: This flow configures a vector retrieval system to answer questions based on content downloaded from Google Drive. It uses Pinecone as a vector database and OpenAI for embeddings and chat response.

- [2733-gitlab-code-review.json](workflows/2733-gitlab-code-review.json)
  Description: This flow uses the GitLab API to get changes made in a merge request and uses an LLM model to review those changes. If there are issues, it posts comments in the repository.

- [2734-cv-extractor-telegram.json](workflows/2734-cv-extractor-telegram.json)
  Description: This flow automates extracting and formatting resume information into HTML and PDF for Telegram. It receives a PDF CV file, extracts text, processes it with OpenAI to structure data, and generates an HTML document/converted to PDF.

- [2735-traductor-deepL-GDrive.json](workflows/2735-traductor-deepL-GDrive.json)
  Description: This flow automates PDF document translation using DeepL and Google Drive. It configures a path, selects source and target languages, and files will be automatically translated.

- [2736-wordpress-article-generator.json](workflows/2736-wordpress-article-generator.json)
  Description: Flow that automates WordPress article creation using OpenAI to generate structured content and DALL·E for images, with data validation.

- [2737-stripe-payment-link.json](workflows/2737-stripe-payment-link.json)
  Description: This flow creates a product in Stripe and generates a payment link based on submitted form data. It configures currency and price, then creates the product, and finally redirects the user.

- [2738-gmail-label-assigner.json](workflows/2738-gmail-label-assigner.json)
  Description: This flow automates assigning labels to Gmail messages using AI. It analyzes emails and determines which labels to apply based on their content.

- [2739-email-ai-reply.json](workflows/2739-email-ai-reply.json)
  Description: This automated flow processes emails with specific labels by transferring their content to the OpenAI Assistant to generate a draft reply. The workflow includes from email extraction to final sending and subsequent removal of trigger labels.

- [2740-automate_ga_reporting.json](workflows/2740-automate_ga_reporting.json)
  Description: This automated flow extracts and processes Google Analytics data to generate detailed reports on page statistics, search results, and views by country, comparing weekly data. Results are formatted in HTML and sent via email.

- [2741-zalando-price-monitor.json](workflows/2741-zalando-price-monitor.json)
  Description: This flow monitors prices on Zalando, extracts product information, compares with saved prices, and notifies if there are reductions.

- [2742-email_to_podcast.json](workflows/2742-email_to_podcast.json)
  Description: This flow automates converting emails into podcasts. It uses Gmail to detect messages with the 'CATEGORY_PROMOTIONS' label, processes them, generates a summary, and converts text to audio sent to Telegram.

- [2743-youtube-rss-generator.json](workflows/2743-youtube-rss-generator.json)
  Description: This flow generates custom RSS URLs for YouTube channels and specific videos in different formats (ATOM, JSON, MRSS, PLAINTEXT, SFEED, and XML) using external sources.

- [2744-ai-storyteller-telegram.json](workflows/2744-ai-storyteller-telegram.json)
  Description: This flow automates creating and sending children's stories to a Telegram channel, generating text, audio, and images with artificial intelligence.

- [2745-kids-story-generator.json](workflows/2745-kids-story-generator.json)
  Description: Automated flow to create and share children's stories in Arabic with OpenAI and Telegram.

- [2746-dropcontact-batch.json](workflows/2746-dropcontact-batch.json)
  Description: This flow automates bulk contact deletion in Dropcontact via PostgreSQL queries and handles up to 1500 requests per hour.

- [2747-correo_n8n_version.json](workflows/2747-correo_n8n_version.json)
  Description: This flow schedules a daily email with the most stable n8n version obtained from GitHub.

- [2748-wordpress_blog_poster.json](workflows/2748-wordpress_blog_poster.json)
  Description: This flow automates content publishing on WordPress and Airtable. It searches for entries marked 'To Post', converts markdown to HTML, uploads an image, creates a WordPress entry with it, and updates Airtable to mark it as 'Posted'.

- [2749-spotify-downloads-manager.json](workflows/2749-spotify-downloads-manager.json)
  Description: This automated flow manages a Spotify playlist called 'Downloads'. It searches for the most recent songs the user has favorited and adds them to the playlist, keeping only a defined number of songs. If the playlist doesn't exist, it creates it. If it already exists, it deletes the oldest songs if the limit is exceeded.

- [2750-email_classifier.json](workflows/2750-email_classifier.json)
  Description: This flow monitors email responses in Lemlist and uses OpenAI to categorize them, subsequently sending personalized notifications to Slack. If the response is classified as 'Unsubscribe', the lead is unsubscribed; if 'Interested', it's marked as interested.

- [2751-crm-verification-form.json](workflows/2751-crm-verification-form.json)
  Description: Flow that uses Tally Forms to capture form data, verifies email with CaptainVerify, manages credits, and creates Leads in SuiteCRM and contacts in Brevo. Notifies on NextCloudDiscussions if there's malformation or low credit.

- [2752-notion-webflow-sync.json](workflows/2752-notion-webflow-sync.json)
  Description: This flow synchronizes blog entries from Notion to Webflow by comparing slugs and updating or creating posts accordingly.

- [2753-n8n-updates-checker.json](workflows/2753-n8n-updates-checker.json)
  Description: This flow retrieves node type and available version information, then checks if any nodes require updating by comparing their current version with the latest registered version. If a node is inactive or its version is obsolete, it identifies it and generates formatted output with the flow name, its ID, and the list of outdated nodes.

- [2754-backup-github.json](workflows/2754-backup-github.json)
  Description: This flow automates credential backup to GitHub. It uses a command to export credentials, formats them, and then compares with existing versions or creates new ones if none exist.

- [2755-social-media-crawler.json](workflows/2755-social-media-crawler.json)
  Description: This flow extracts social media information from websites using text and URL retrieval tools. It navigates pages, gets social links, and organizes them in JSON format.

- [2756-automatizacion-facturas-pdf.json](workflows/2756-automatizacion-facturas-pdf.json)
  Description: This flow automates data extraction from PDF invoices sent by email. It uses LlamaParse to analyze documents and then extracts structured information with OpenAI, finally inserting data into a Google Sheets spreadsheet.

- [2757-automatiza-rfp.json](workflows/2757-automatiza-rfp.json)
  Description: Automated flow to generate RFP responses using Webhooks, Google Docs, and OpenAI. Receives an RFP document, extracts questions, processes them with AI, and inserts answers into a Google Docs document.

- [2758-evento-banner-generator.json](workflows/2758-evento-banner-generator.json)
  Description: This flow automates creating promotional event banners using n8n. It allows capturing information via a form, generating an AI image, and creating custom banners in BannerBear for sharing on Discord.

- [2760-empresa_research.json](workflows/2760-empresa_research.json)
  Description: This flow automates company research using OpenAI and Google Sheets. It collects structured information from websites and databases, and updates a spreadsheet with the results.

- [2761-slack-calendar-event.json](workflows/2761-slack-calendar-event.json)
  Description: This automated flow monitors a Slack channel for messages tagged with a calendar emoji (📅) and manages Google Calendar event creation and updates. It uses artificial intelligence to extract event details, creates a new one if necessary, or adds attendees to an existing event based on user reactions.

- [2762-sitios-monitor.json](workflows/2762-sitios-monitor.json)
  Description: This flow automates website monitoring using a timer that checks each site's status and sends email or Slack alerts if there are status changes.

- [2763-google-meet-scheduler.json](workflows/2763-google-meet-scheduler.json)
  Description: This flow automates meeting management via Google Calendar and Drive. It retrieves meeting records, processes transcripts with OpenAI, creates calendar events, and assigns attendees.

- [2764-inventory-enricher.json](workflows/2764-inventory-enricher.json)
  Description: This automated flow uses Airtable to capture inventory photos, OpenAI to analyze images, and artificial intelligence agents to enrich data. First, it gets applicable rows from Airtable with unprocessed photos. Then, it uses the OpenAI model to identify object attributes in the image. An AI agent uses custom tools (reverse image search and web scraping) to find additional information. Finally, it overwrites data in Airtable with enriched results.

- [2765-image-object-extraction.json](workflows/2765-image-object-extraction.json)
  Description: This flow uses the Cloudflare API to detect objects in an image and then extracts and stores those objects as separate images in Elasticsearch to allow object-based searches.

- [2766-hellofresh-recomendador.json](workflows/2766-hellofresh-recomendador.json)
  Description: This flow automates recommending weekly HelloFresh recipes using a vector search engine and a database. It extracts information from weekly menus, processes recipe data, generates embeddings with Mistral Cloud, and uses Qdrant to recommend options based on preferences.

- [2767-file-organizer-mistral.json](workflows/2767-file-organizer-mistral.json)
  Description: This workflow uses a local trigger to monitor a directory, uses commands to get a list of files and folders, then employs the Mistral AI model to organize files by moving them to appropriate subfolders based on AI suggestions.

- [2768-file_sync_qdrant.json](workflows/2768-file_sync_qdrant.json)
  Description: This workflow monitors a local directory and synchronizes file changes with Qdrant to create a knowledge base using Mistral AI.

- [2769-bank_statement_reconciliation.json](workflows/2769-bank_statement_reconciliation.json)
  Description: This workflow monitors bank statement CSV files, processes them with an AI model to detect discrepancies in rent payments and specific notifications.

- [2770-automated-notes-generator.json](workflows/2770-automated-notes-generator.json)
  Description: This automated workflow monitors a directory for new files, processes their content, and uses AI agents to generate structured documents in Markdown format such as study guides, timelines, and informational documentation.

- [2771-tax-code-ai-assistant.json](workflows/2771-tax-code-ai-assistant.json)
  Description: This workflow automates the creation of a legal chatbot assistant specialized in Texan tax codes. It downloads, processes, and stores PDF documents in Qdrant using Mistral.ai embeddings to enable advanced searches.

- [2772-pc_repair_booking.json](workflows/2772-pc_repair_booking.json)
  Description: This automated workflow manages appointment scheduling and follow-ups for a PC and laptop repair service. It uses Twilio to receive SMS messages, Airtable to handle sessions and conversations, and OpenAI with language agents to interact with customers, in addition to Cal.com for scheduling appointments.

- [2773-image-embedding_workflow.json](workflows/2773-image-embedding_workflow.json)
  Description: This workflow downloads an image from Google Drive, extracts color information, and generates semantic keywords using OpenAI to create an embedding document, which is stored in an in-memory vector store.

- [2774-chat-flow-buffer.json](workflows/2774-chat-flow-buffer.json)
  Description: This workflow uses Redis and Twilio to handle chat messages, pausing execution for 5 seconds and checking if the last message matches the one entered. If it matches, it sends a unique response based on all buffered messages using OpenAI.

- [2775-competitor-research-automator.json](workflows/2775-competitor-research-automator.json)
  Description: This workflow automates competitive research using Exa.ai to find competitors and then collects detailed information about each competitor using AI agents that extract data from sites like Crunchbase, LinkedIn, and other relevant sites. The data is structured and inserted into Notion.

- [2776-pdf-pinecone-reserva.json](workflows/2776-pdf-pinecone-reserva.json)
  Description: Workflow that includes downloading a PDF, its embedding and storage in Pinecone, plus an appointment booking capability via Google Calendar using language agents like GPT-4o and Anthropic.

- [2777-encuesta-analisis.json](workflows/2777-encuesta-analisis.json)
  Description: This workflow automates survey collection and analysis using OpenAI and Qdrant to extract insights through clustering and embeddings.

- [2778-trustpilot-insights.json](workflows/2778-trustpilot-insights.json)
  Description: This workflow extracts, processes, and analyzes Trustpilot reviews for a specific company. It uses Qdrant as a vector database to store structured data, applies K-means clustering to identify patterns, generates insights using an LLM model, and exports the results to Google Sheets.

- [2779-hn_comments_analyzer.json](workflows/2779-hn_comments_analyzer.json)
  Description: This automated workflow extracts and analyzes comments from a Hacker News article, organizes them into clusters using clustering algorithms (K-means), and generates insights with a large language model. The data is stored in Qdrant for further analysis.

- [2780-gitlab-backup-n8n.json](workflows/2780-gitlab-backup-n8n.json)
  Description: This automated workflow configures periodic and manual backups of n8n workflows in GitLab. It uses scheduled and manual triggers to save the updated configuration in separate files within a GitLab repository.

- [2781-spotify-mqtt-controller.json](workflows/2781-spotify-mqtt-controller.json)
  Description: This workflow handles MQTT commands from a remote button to control Spotify, including volume and playback, as well as playing favorite playlists.

- [2782-sync-workflows.json](workflows/2782-sync-workflows.json)
  Description: This workflow automates the synchronization of workflows between n8n and GitLab. It retrieves n8n workflows, checks their status in GitLab, and updates or creates new JSON files based on detected differences.

- [2783-paddle-invoice-processor.json](workflows/2783-paddle-invoice-processor.json)
  Description: This automated workflow detects and processes Paddle invoices from Gmail, extracts the PDF link, downloads it, and stores it in Google Drive, organizing it into specific folders.

- [2784-supabase-vector-store.json](workflows/2784-supabase-vector-store.json)
  Description: This workflow sets up a vector database in Supabase to store and retrieve documents with OpenAI embeddings, allowing for semantic searches and answering questions based on content.

- [2785-it-slack-ai-agent.json](workflows/2785-it-slack-ai-agent.json)
  Description: This workflow uses n8n to handle Slack messages, responding to users with OpenAI-generated answers and querying Confluence. It includes webhook verification, contextual memory, and deletion of initial messages.

- [2786-telegram_bot_workflow.json](workflows/2786-telegram_bot_workflow.json)
  Description: This workflow uses Telegram to handle different types of messages and commands, such as text, photos, files, voice, and buttons. It detects the message type and acts accordingly, displaying a context menu or handling payments.

- [2787-contabo-backups.json](workflows/2787-contabo-backups.json)
  Description: This automated workflow schedules daily snapshots of instances in Contabo, checking and deleting if a snapshot already exists before creating a new one.

- [2788-daily-order-summary.json](workflows/2788-daily-order-summary.json)
  Description: This workflow automates the creation of a daily order summary and its email delivery. Each time a new order is received via a webhook, the data is stored in Airtable. At 7 PM, a report is generated with all orders of the day, and a formatted HTML is attached.

- [2789-notion-task-reminder.json](workflows/2789-notion-task-reminder.json)
  Description: This workflow automates the creation of a weekly email with reminders and push notifications for pending tasks in Notion. It retrieves tasks from a Notion database, filters and sorts them by deadline, generates an HTML with the details of each task, and sends an email or a Pushover notification if there are overdue tasks.

- [2790-notion-kb-agent.json](workflows/2790-notion-kb-agent.json)
  Description: This workflow uses OpenAI and Notion to act as a knowledge base assistant that searches for information in a Notion database based on user questions.

- [2791-notion-workflow-generator.json](workflows/2791-notion-workflow-generator.json)
  Description: This workflow generates a custom n8n workflow for Notion databases from a URL provided by the user. It uses language agents and validation to ensure the correct JSON structure.

- [2792-flujo-imagen-ai.json](workflows/2792-flujo-imagen-ai.json)
  Description: Workflow that generates AI images based on user-selected prompts and styles, using the Hugging Face API. The user can choose from different visual styles like cyberpunk or neon to create advanced visual compositions.

- [2793-image-caption-generator.json](workflows/2793-image-caption-generator.json)
  Description: This workflow automates the generation of image captions using the Gemini model and applies them visually.

- [2794-visual-regression-test-flow.json](workflows/2794-visual-regression-test-flow.json)
  Description: Automated workflow for performing visual regression tests on websites using Google Gemini and Apify. It generates base images, compares them with recent captures, and reports detected changes via Linear.

- [2795-banco-estado-pdf-to-markdown.json](workflows/2795-banco-estado-pdf-to-markdown.json)
  Description: This workflow automates the conversion of a bank statement PDF in image format to structured markdown text using Google Gemini and advanced OCR.

- [2796-slack-csr-approval.json](workflows/2796-slack-csr-approval.json)
  Description: This automated workflow manages digital certificate requests via Slack. It analyzes threats using VirusTotal and generates an automatic confirmation or a report for manual approval.

- [2797-adobe-pdf-processing.json](workflows/2797-adobe-pdf-processing.json)
  Description: This automated workflow implements an integration with the Adobe API to process PDF files, performing tasks such as uploading a file, sending a processing query, and downloading the result. It uses custom credentials for authentication and manages different process states.

- [2798-podcast-summarizer.json](workflows/2798-podcast-summarizer.json)
  Description: This workflow automates the creation of a daily summary of specific podcasts by genre. It uses the Taddy API to get lists of the most popular podcasts, downloads selected episodes, transcribes their content with Whisper, and then generates a summary using OpenAI. The result is sent via email.

- [2799-faq-generator-n8n.json](workflows/2799-faq-generator-n8n.json)
  Description: This workflow automates FAQ creation for n8n integrations using OpenAI and Google Sheets. It extracts data from a spreadsheet, generates question-answer pairs, completes some answers with AI, and saves the results to Google Drive.

- [2800-monitor-github.json](workflows/2800-monitor-github.json)
  Description: This workflow monitors multiple GitHub repositories without polling, registering and handling webhooks to receive notifications for events like pushes and pull requests.

- [2801-email-reply-draft.json](workflows/2801-email-reply-draft.json)
  Description: This automated workflow uses OpenAI to generate email replies and saves them to the Fastmail drafts folder.

- [2802-webhook-relay.json](workflows/2802-webhook-relay.json)
  Description: This automated workflow uses webhook.site to receive and store requests, then processes and forwards them to a local address via n8n. An authentication token and a key are used to synchronize state between executions.

- [2803-workflow_calendar_task.json](workflows/2803-workflow_calendar_task.json)
  Description: Workflow that manages tasks and appointments in Google Calendar and Notion using specialized agents for calendar and tasks, employing OpenAI and Chat Models for artificial intelligence.

- [2804-fastmail-masked-email-flow.json](workflows/2804-fastmail-masked-email-flow.json)
  Description: This workflow manages Fastmail's anonymous email addresses via its API. It allows getting a list of anonymized emails, creating new ones with an initial state, updating their status (enabled/disabled), and deleting them. The generated HTML interface displays a list with options to filter by status, add new ones, and perform actions.

- [2805-sincronizacion-stripe-s3.json](workflows/2805-sincronizacion-stripe-s3.json)
  Description: This workflow automates the synchronization of PDF invoices from Stripe to an AWS S3 bucket, organizing files into subfolders by year and month. It configures monthly intervals to download only invoices issued from the first day of the month.

- [2806-telegram-bot-memory.json](workflows/2806-telegram-bot-memory.json)
  Description: This automated workflow manages Telegram conversations using OpenAI and Supabase to maintain context. It creates a new discussion thread in OpenAI if it's the first time a user talks to the bot, saves user information in Supabase, and sends personalized responses.

- [2807-automatiza-categorizacion-outlook.json](workflows/2807-automatiza-categorizacion-outlook.json)
  Description: This workflow automates email categorization in Outlook using an AI agent. It extracts the email body, processes it to remove HTML, and then sends it to an Ollama language model to assign categories. If it fails, it logs the error. Depending on the resulting category, it moves emails to different folders like 'Junk', 'Receipt', 'SaaS', 'Community', 'Business', or 'Action'.

- [2808-telegram-ai-agent.json](workflows/2808-telegram-ai-agent.json)
  Description: This workflow uses Telegram to receive messages, processes voice or text, transcribes voice to text, and uses OpenAI as an AI agent to respond based on email, calendar, and contacts.

- [2809-seo-ai-keywords-generator.json](workflows/2809-seo-ai-keywords-generator.json)
  Description: Workflow that generates SEO keywords using an AI agent based on the ideal customer profile (ICP).

- [2810-incident-service-now.json](workflows/2810-incident-service-now.json)
  Description: This workflow receives a Slack request via a slash command, extracts the incident ID, and queries ServiceNow for details. If the incident exists, it sends the information to Slack; otherwise, it notifies the user.

- [2811-gmail-auto-label.json](workflows/2811-gmail-auto-label.json)
  Description: Automates email categorization in Gmail using OpenAI to label messages based on existing ones or create new labels if necessary.

- [2812-youtube-metagen.json](workflows/2812-youtube-metagen.json)
  Description: This workflow automates metadata generation for YouTube videos, including SEO-optimized titles, descriptions, and tags, using an input form that processes video links and transcriptions.

- [2813-transform-text.json](workflows/2813-transform-text.json)
  Description: This workflow transforms text to lowercase, uppercase, and replaces specific words using echo commands.

- [2814-subscriber-unsubscribes-customerio.json](workflows/2814-subscriber-unsubscribes-customerio.json)
  Description: This workflow activates a node when a subscriber unsubscribes in Customer.io, allowing actions to be performed based on that event.

- [2815-luma-video-generator.json](workflows/2815-luma-video-generator.json)
  Description: This workflow creates custom videos using the Luma AI Dream Machine API. It generates a video based on a globally defined prompt with different options for aspect ratio, duration, and random motion. It records video data in Airtable.

- [2816-rss-telegram-updates.json](workflows/2816-rss-telegram-updates.json)
  Description: This workflow automates publishing updates from an RSS feed to Telegram. It reads RSS entries, checks if they are new using the date, and sends them to the channel if they are recent.

- [2817-eleven-labs-transcript.json](workflows/2817-eleven-labs-transcript.json)
  Description: This workflow automates audio transcription creation using Eleven Labs. It starts with a 'Test workflow' click, reads the media file from disk (/files/tmp/tst1.mp4), and processes it to get a transcript by sending a POST request to the Eleven Labs API.

- [2818-squarespace-fulfillment.json](workflows/2818-squarespace-fulfillment.json)
  Description: This workflow automates order management in Squarespace Commerce. It searches for pending orders and marks them as fulfilled, using the API Key for authentication.

- [2819-procesar_Ordenes_Gmail.json](workflows/2819-procesar_Ordenes_Gmail.json)
  Description: Automated workflow that processes purchase orders received by email, extracts relevant information, and stores it in a Google Sheets spreadsheet.

- [2820-auto-assign-jira.json](workflows/2820-auto-assign-jira.json)
  Description: This workflow automates the assignment of stalled JIRA tasks using a matching system with past resolved issues using AI and vector databases. It looks for unassigned tasks for more than 5 days, finds the most similar ones in the knowledge base, and assigns them to team members with the least current workload.

- [2821-automatizacion-facturas-outlook.json](workflows/2821-automatizacion-facturas-outlook.json)
  Description: This workflow automates invoice management from an Outlook account, classifying messages to detect and download attachments that are invoices issued to the company. It uses Google Gemini to verify if attachments are relevant invoices and extract key information, then records this data in an Excel spreadsheet.

- [2822-automated-sales-email-generator.json](workflows/2822-automated-sales-email-generator.json)
  Description: This workflow automates the creation of personalized sales emails using Google Gemini and Gmail. It retrieves customer emails, builds custom profiles with communication and buying style analysis, generates tailored pitches, and creates drafts for human review.

- [2823-anthropic-batch-processing.json](workflows/2823-anthropic-batch-processing.json)
  Description: This automated workflow sends multiple prompts simultaneously to the Anthropic Claude Batch API, checks their status, and processes the results using memory nodes to maintain context.

- [2824-csrd-audit-flow.json](workflows/2824-csrd-audit-flow.json)
  Description: Automated workflow for auditing CSRD reports in xHTML format. Analyzes and generates a report summarizing key findings and recommendations.

- [2825-gestion_citas_vapi.json](workflows/2825-gestion_citas_vapi.json)
  Description: This automated workflow manages appointment booking and management using Vapi, Google Calendar, and Airtable. It allows checking availability, creating, updating, and deleting events, as well as recording phone call information.

- [2826-client-usage-tracker.json](workflows/2826-client-usage-tracker.json)
  Description: This workflow tracks client token usage and costs when using a CV data extraction service with OpenAI, storing the data in a Google Sheets spreadsheet.

- [2827-redis_lock_workflow.json](workflows/2827-redis_lock_workflow.json)
  Description: This workflow uses Redis to block the execution of a workflow until a TTL key expires, thus preventing concurrent execution.

- [2828-organizador-tags.json](workflows/2828-organizador-tags.json)
  Description: This automated workflow organizes workflows into specific folders based on tags. First, it logs into n8n, extracts tags from personal projects, allows selecting them via a form, and then moves the workflows to corresponding folders or creates new ones if necessary.

- [2829-digest-novedades-plantillas.json](workflows/2829-digest-novedades-plantillas.json)
  Description: This automated workflow generates a daily summary of the latest n8n templates filtered by categories selected by subscribers stored in an Excel spreadsheet. It uses OpenAI to summarize descriptions and Outlook to send the email.

- [2830-outlook-calendar-agent.json](workflows/2830-outlook-calendar-agent.json)
  Description: This workflow uses an AI agent to handle Outlook calendar-related queries. The user can ask questions about calendar events, and the agent, equipped with Outlook tools, will respond appropriately.

- [2831-rss_to_gsheet_cleaner.json](workflows/2831-rss_to_gsheet_cleaner.json)
  Description: This workflow automates the updating and handling of RSS entries in Google Sheets. First, it uses a timer to read links from a spreadsheet, then extracts the corresponding news and processes them. Filters remove old entries (older than 3 days), and new ones are saved with a delay to avoid blocks. Old entries are deleted after a certain time.

- [2832-gmail-to-drive-organizer.json](workflows/2832-gmail-to-drive-organizer.json)
  Description: This workflow automates downloading Gmail attachments, organizing them into specific folders in Google Drive based on the recipient's email and date, creating necessary folders if they don't exist.

- [2833-icp_scoring_workflow.json](workflows/2833-icp_scoring_workflow.json)
  Description: This workflow automates ICP scoring by collecting and processing data from LinkedIn profiles. First, it uses Google Sheets to obtain personal information, then extracts LinkedIn profile details and calculates an ICP score based on AI interests, technical level, and seniority.

- [2834-automated-instagram-posts.json](workflows/2834-automated-instagram-posts.json)
  Description: This automated workflow publishes content on Instagram using Google Drive to detect file uploads, OpenAI to generate captions, and Facebook Graph API for publication.

- [2835-acuity-chatbot-search.json](workflows/2835-acuity-chatbot-search.json)
  Description: Workflow that uses a chatbot to search for information in the AcuityScheduling support API and format the results.

- [2836-sms-course-assistant.json](workflows/2836-sms-course-assistant.json)
  Description: This workflow automates an SMS assistant for Northvale Institute of Technology that uses OpenAI and Airtable to answer questions about courses. It receives messages via Twilio, queries the course database, and sends responses via SMS.

- [2837-linkedin-posts-generator.json](workflows/2837-linkedin-posts-generator.json)
  Description: This workflow automates the generation of promotional LinkedIn posts for each blog post extracted from Ghost. It uses an AI agent to create engaging content and records it in a Google spreadsheet.

- [2838-retell-call-storage.json](workflows/2838-retell-call-storage.json)
  Description: This workflow processes and stores call data analyzed by Retell AI in different tools like Airtable, Google Sheets, and Notion. It receives a webhook when a call ends, filters only 'call_analyzed' events, extracts relevant information such as call ID, duration, cost, and transcription, and saves it in Airtable, Google Sheets, and Notion.

- [2839-automaton-ics-calendario.json](workflows/2839-automaton-ics-calendario.json)
  Description: This workflow automates the extraction of dates and events from an Excel file using Cloudflare to convert it to a readable format, then uses the Gemini model to extract structured information and creates an ICS calendar to share via email.

- [2840-google-drive-deduplicate.json](workflows/2840-google-drive-deduplicate.json)
  Description: This workflow automates file deduplication in Google Drive. It identifies duplicates based on the md5 checksum and manages their deletion or renaming according to Keep (first/last) and Action (trash/flag) settings.

- [2841-export_google_keep_to_sheet.json](workflows/2841-export_google_keep_to_sheet.json)
  Description: This workflow automates the export of notes from Google Keep to align with a processing and storage system in Google Sheets. It searches for JSON files in a specific Google Drive folder, filters those that are not archived and contain keywords like 'dépensé' or 'depense', downloads the selected files, extracts their content, and uses OpenAI to process the information before inserting it into a spreadsheet.

- [2842-automated-purchase-order-processing.json](workflows/2842-automated-purchase-order-processing.json)
  Description: This workflow automates the import and processing of purchase orders from Outlook. It converts XLSX files to a format readable by LLMs, extracts details using AI, and performs validations.

- [2843-gdrive-audit.json](workflows/2843-gdrive-audit.json)
  Description: This workflow automates Google Drive permission audits, identifying files shared publicly or with external users and generating a daily report sent by email.

- [2844-actualizar_Tasas.json](workflows/2844-actualizar_Tasas.json)
  Description: This workflow automates the daily update of exchange rates from USD to multiple currencies using an API. It records data in Google Sheets and maintains an archived history.

- [2845-linkedin-enrichment-icebreaker.json](workflows/2845-linkedin-enrichment-icebreaker.json)
  Description: This automated n8n workflow allows extracting and enriching LinkedIn profile data using Bright Data, generating personalized icebreakers with Anthropic's Claude model, and updating a Google Sheets spreadsheet with the resulting information.

- [2846-news-email-digest.json](workflows/2846-news-email-digest.json)
  Description: Workflow that collects, processes, and selects RSS articles from Calcalist and Mako to send a formatted daily summary by email with the most relevant ones for executives.

- [2847-paulgraham-essays-milvus.json](workflows/2847-paulgraham-essays-milvus.json)
  Description: This workflow extracts Paul Graham essay titles, gets their content, processes them, and stores them in Milvus to later answer questions about them.

- [2848-linkedin-jobs-to-sheets.json](workflows/2848-linkedin-jobs-to-sheets.json)
  Description: This workflow automates the extraction of job listings from LinkedIn using Bright Data, cleans them, and sends them to a Google Sheets spreadsheet. It includes a form to define filters like location, keyword, and country, waits for the request to be processed, then sends the cleaned data to the spreadsheet.

- [2849-producthunt-to-sheets.json](workflows/2849-producthunt-to-sheets.json)
  Description: This workflow collects and processes information from Product Hunt daily to update a Google Sheets spreadsheet with basic data of published products.

- [2850-nutrientes_dieta.json](workflows/2850-nutrientes_dieta.json)
  Description: This workflow processes Telegram messages to extract nutrients and macros from the daily diet. If it's a voice message, it transcribes it; then structures the data and stores it in Google Sheets.

- [2851-job_scraping_openai.json](workflows/2851-job_scraping_openai.json)
  Description: This workflow automates the search for job listings on Indeed using Bright Data and OpenAI to assess if each position is suitable. It starts with a form that collects location, keyword, and country, then sends a request to Bright Data, waits for the snapshot to be processed, extracts the data, and finally uses OpenAI to determine if you are a good candidate.

- [2852-glassdoor-jobs-scraper.json](workflows/2852-glassdoor-jobs-scraper.json)
  Description: This workflow uses Bright Data to extract job listings from Glassdoor based on location, keyword, and country, waits for them to be ready, saves them to Google Sheets, and then generates personalized pitches using an LLM.

- [2853-trustpilot-analysis.json](workflows/2853-trustpilot-analysis.json)
  Description: This workflow automates the extraction and analysis of negative competitor reviews on Trustpilot using Bright Data. The user enters a Trustpilot URL and selects a period, then the workflow sends a request to Bright Data, waits until the data is ready, filters negative reviews (1 or 2 stars), groups comments, and uses OpenAI to generate persuasive text based on those complaints. Finally, it sends a summary by email.

- [2854-finanzas-sync.json](workflows/2854-finanzas-sync.json)
  Description: This automated workflow generates monthly financial reports comparing budget data with actual results for a specific business unit. It includes detailed analysis of sales, costs, margins, and an employee report, using artificial intelligence for interpretation.

- [2855-cripto-market-summary.json](workflows/2855-cripto-market-summary.json)
  Description: This automated workflow obtains market price data from Binance for BTC, ETH, and SOLUSDC via its API, analyzes fluctuations, and sends a detailed summary to the Telegram channel.

- [2856-amazon_reviews_analysis.json](workflows/2856-amazon_reviews_analysis.json)
  Description: This workflow uses Bright Data to extract and analyze product reviews on Amazon. It sets up a form to enter product URLs, sends an HTTP request to start the analysis, waits for the information to be processed, and then stores the data in Google Sheets. Afterward, it uses OpenAI to summarize the reviews, generates creative images based on the results, and sends these creatives by email.

- [2857-filesystem-mcp-server.json](workflows/2857-filesystem-mcp-server.json)
  Description: Workflow that implements an MCP server to handle file operations like listing directories, reading, and creating files on a file system through controlled commands.

- [2858-postgre-mcp-server.json](workflows/2858-postgre-mcp-server.json)
  Description: Workflow that implements an MCP interface to interact with PostgreSQL allowing secure CRUD operations using custom tools.

- [2859-sqlite-mcp-server.json](workflows/2859-sqlite-mcp-server.json)
  Description: Workflow that implements an SQLite MCP server to perform basic operations on a local database such as reading, inserting, and updating records, using custom nodes to handle secure operations.

- [2860-gdrive-mcp-server.json](workflows/2860-gdrive-mcp-server.json)
  Description: This workflow sets up an MCP server that interacts with Google Drive to search and read files, converting binary formats to text. It uses OpenAI to analyze images and transcribe audio.

- [2861-github-mcp-server.json](workflows/2861-github-mcp-server.json)
  Description: This workflow sets up a custom MCP server in n8n to interact with GitHub, allowing viewing and commenting on issues. It uses custom nodes to get the latest issues, issue comments, and add new comments.

- [2862-mcp-qdrant-reviews.json](workflows/2862-mcp-qdrant-reviews.json)
  Description: This workflow configures and manages a vector database with Qdrant to perform operations such as inserting, searching, comparing, and recommending company reviews. It uses MCP Server Trigger to handle different custom tools and extends the Qdrant server functionality with advanced capabilities.

- [2863-youtube-mcp-server.json](workflows/2863-youtube-mcp-server.json)
  Description: This workflow configures an MCP server that uses external tools to perform YouTube searches, download transcriptions, and monitor usage metrics with APIFY.com.

- [2864-mcp-paycaptain-employees.json](workflows/2864-mcp-paycaptain-employees.json)
  Description: This workflow configures an MCP server that interacts with the PayCaptain API to allow employee search and update operations, protecting sensitive data and logging activities in Google Sheets.

- [2865-image_alt_text_generator.json](workflows/2865-image_alt_text_generator.json)
  Description: This workflow extracts images and their alt text from a webpage, generates alt text if necessary, and updates a spreadsheet with the results.

- [2866-legis-sostenibilidad.json](workflows/2866-legis-sostenibilidad.json)
  Description: This automated workflow extracts information on legislative procedures related to sustainability from the European Parliament's website, classifying each document using an OpenAI language agent and storing them in a Google Sheets spreadsheet.

- [2867-telegram-voz-tareas.json](workflows/2867-telegram-voz-tareas.json)
  Description: This workflow uses Telegram to receive voice messages, download and transcribe audio with OpenAI, and manage tasks in Google Tasks via MCP Server.

- [2868-sustentabilidad-news.json](workflows/2868-sustentabilidad-news.json)
  Description: This automated workflow extracts and classifies EU news, identifying if they are related to sustainability, and sends a summary by email.

- [2869-automail_manager.json](workflows/2869-automail_manager.json)
  Description: This workflow automates email management using OpenRouter and Telegram. It retrieves unread messages from Gmail, categorizes them with the help of a Chat Model, and sends notifications via Telegram.

- [2870-paypal-payment-email.json](workflows/2870-paypal-payment-email.json)
  Description: This workflow collects data from a PayPal webhook, filters completed payment events, extracts order details, captures buyer and product information, generates an email with formatted data, and attaches a JSON file.

- [2871-image-processing.json](workflows/2871-image-processing.json)
  Description: This automated workflow downloads images from URLs, analyzes them to create a product photography prompt, and generates a new image with OpenAI before storing it in Google Drive and updating a table.

- [2872-flujo_conversaciones.json](workflows/2872-flujo_conversaciones.json)
  Description: This workflow automates customer conversation management using HubSpot and LangChain. It allows searching for customer IDs, summarizing conversations, routing feedback to specific departments, and sending emails using Gmail.

- [2873-google-drive-folder-creator.json](workflows/2873-google-drive-folder-creator.json)
  Description: This workflow creates a hierarchical structure in Google Drive from a given path and returns the ID of the last folder created.

- [2875-email-process-hubspot.json](workflows/2875-email-process-hubspot.json)
  Description: This automated workflow processes a received email, extracts relevant information with AI, checks if a contact exists in HubSpot, and creates a new entry or updates the existing record.

- [2876-workflow_mcp_manager.json](workflows/2876-workflow_mcp_manager.json)
  Description: This workflow dynamically manages a list of available workflows using Redis and n8n, allowing operations like adding, deleting, and listing workflows. It uses a language agent to execute tasks based on these workflows.

- [2877-import-hubspot.json](workflows/2877-import-hubspot.json)
  Description: This workflow imports data from a CSV file to HubSpot. First, it validates the file fields against a list of existing properties in HubSpot. If there are discrepancies, it displays a form to map corresponding fields. Then it processes the data and exports it to Google Sheets.

- [2878-n8n-backup-workflows.json](workflows/2878-n8n-backup-workflows.json)
  Description: This workflow automates the daily backup of n8n workflows to Google Drive. It searches and processes all workflows, and if an existing file is not found, it creates a new one; if it already exists, it updates it with the new information.

- [2879-stock-analysis-bot.json](workflows/2879-stock-analysis-bot.json)
  Description: This automated workflow performs a detailed stock analysis combining technical analysis and news sentiment. It uses various APIs to obtain technical data (charts, indicators) and sentiment analytics, then processes them with GPT-4 to generate a structured report in HTML format in Hebrew, which is sent by email.

- [2880-calendario_openai_report.json](workflows/2880-calendario_openai_report.json)
  Description: This workflow automates the research of attendees and companies using OpenAI API, collects Google Calendar information, and sends a detailed report by email.

- [2881-hotel-reservation-confirmation.json](workflows/2881-hotel-reservation-confirmation.json)
  Description: This workflow handles a hotel reservation via a Retell webhook, confirms the reservation, and sends a response to the user.

- [2882-contact_discovery.json](workflows/2882-contact_discovery.json)
  Description: This workflow automates the discovery of decision-makers in companies using Google Sheets and Apollo.io. It extracts company information, finds key contacts, performs human verification via Slack, and enriches data with APIs to then update a verified contact database.

- [2883-chatbot-interactivo.json](workflows/2883-chatbot-interactivo.json)
  Description: This workflow manages chatbot interaction, storing messages in Redis and using OpenAI to extract information. It waits a variable amount of time based on word count before processing messages.

- [2884-instagram-post-automation.json](workflows/2884-instagram-post-automation.json)
  Description: Automates the creation of Instagram posts using Google Sheets and AI tools. Includes everything from content concept generation to final publication.

- [2885-reddit-business-opportunities.json](workflows/2885-reddit-business-opportunities.json)
  Description: This workflow automates the extraction and analysis of Reddit posts relevant to business opportunities, applying filters and generating summaries with an LLM.

- [2886-jira-ticket-automatizacion.json](workflows/2886-jira-ticket-automatizacion.json)
  Description: This automated workflow uses JIRA and OpenAI to triage, prioritize, and resolve support incidents. It searches for open tickets, processes them with AI to label and rewrite, then searches for similar resolutions in history to suggest comments based on them.

- [2887-ai-language-tools.json](workflows/2887-ai-language-tools.json)
  Description: This workflow includes a variety of nodes related to language agents and AI tools, such as language transformers, chaining chains, information extractors, sentiment analyzers, vector tools, and memory. It also contains connections to external services like Google Sheets, Dropbox, Gmail, Twitter, and more.

- [2888-automatizacion-ticket.json](workflows/2888-automatizacion-ticket.json)
  Description: This workflow automates ticket generation and triage. For this, it uses Gmail to extract support messages, OpenAI to triage and label each ticket, and Linear.app to create an issue based on AI results.

- [2889-linkedin-monitor.json](workflows/2889-linkedin-monitor.json)
  Description: This workflow automates LinkedIn profile monitoring and updates a Google Sheets spreadsheet with customer information. It gets lists of HubSpot owners, searches profiles on LinkedIn, compares data, and sends email notifications if there are changes.

- [2890-email_bot_transcripciones.json](workflows/2890-email_bot_transcripciones.json)
  Description: This automated workflow processes new emails, uses OpenAI to determine if they need a response, and transcribes Telegram audios to generate formatted replies in Gmail.

- [2891-flujo_whatsapp_klicktipp.json](workflows/2891-flujo_whatsapp_klicktipp.json)
  Description: This workflow automates the delivery of personalized WhatsApp messages from KlickTipp and processes user responses to control campaigns. It detects if the message starts with 'STOP' to redirect to support or subscribe the contact.

- [2892-resto-order-processor.json](workflows/2892-resto-order-processor.json)
  Description: Automated workflow for processing restaurant orders. Extracts order information using a chat agent and AI tools, separates items, quantity, and table number, confirms the order, and records it in a Google Sheets spreadsheet.

- [2893-imagen-style-transfer.json](workflows/2893-imagen-style-transfer.json)
  Description: This workflow generates images based on a source image style using Google Imagen 3.0 and Gemini 2.0 to describe the style. Users provide a source image URL and a target image prompt via a form, then input is validated and the source image is downloaded. The image is analyzed with Gemini 2.0 to get a detailed description of the visual style, which is combined with the user's prompt to generate new images with Imagen 3.0. Generated images are uploaded to Cloudinary and emailed to the user if specified.

- [2894-onboarding-clientes.json](workflows/2894-onboarding-clientes.json)
  Description: This workflow automates new client onboarding by sending a welcome email and scheduling a call with an assigned account advisor.

- [2896-secure-webhook-validator.json](workflows/2896-secure-webhook-validator.json)
  Description: This workflow implements a secure webhook with authentication and required field validation. It verifies the authorization token and mandatory fields in the request, responding with appropriate HTTP codes (401 if authentication fails or 400 if fields are missing) and returning a successful JSON response.

- [2897-team-weekly-report.json](workflows/2897-team-weekly-report.json)
  Description: This automated workflow collects messages from a Microsoft Teams channel, groups and summarizes the activity of each team member using OpenAI to generate personalized reports, and publishes a weekly summary in the channel.

- [2898-whatsapp-flow-encrypt.json](workflows/2898-whatsapp-flow-encrypt.json)
  Description: Workflow that handles hybrid data decoding and encryption using RSA and AES-GCM to process secure interactions with users via Whatsapp Flow.

- [2899-prevent-concurrent-workflows.json](workflows/2899-prevent-concurrent-workflows.json)
  Description: This workflow uses Redis to prevent concurrent execution of workflows. It stores states in Redis and checks if a process is already ongoing before continuing.

- [2900-inventario-materiales.json](workflows/2900-inventario-materiales.json)
  Description: This automated workflow manages material requests, from reception to approval and inventory update, including low stock notifications. It integrates Google Sheets and Supabase to maintain accurate inventory tracking.

- [2901-error_alert_summarizer.json](workflows/2901-error_alert_summarizer.json)
  Description: This automated workflow detects errors in n8n executions and generates email alerts with diagnostics and resolution.

- [2902-financial-tracker-bot.json](workflows/2902-financial-tracker-bot.json)
  Description: This workflow automates financial tracking by receiving invoices via Telegram, extracting data with Google Gemini, structuring it in Notion, and generating visual reports.

- [2903-extraer_y_decodificar_noticias_google.json](workflows/2903-extraer_y_decodificar_noticias_google.json)
  Description: This workflow extracts and decodes Google News URLs from its RSS feed, cleaning the links to obtain clear and accessible articles.

- [2904-ai-ready-vector-datasets.json](workflows/2904-ai-ready-vector-datasets.json)
  Description: This workflow creates LLM-ready vector datasets using Bright Data, Gemini, and Pinecone. It performs information extraction, structured formatting, and persistence in a vector database.

- [2905-analyze-email-headers.json](workflows/2905-analyze-email-headers.json)
  Description: This workflow analyzes email headers to detect IP addresses and fraud. It extracts IPs from 'received' headers and checks their reputation using the IP Quality Score API, also verifying SPF, DKIM, and DMARC authentication.

- [2906-workflow-obsidian-markdown.json](workflows/2906-workflow-obsidian-markdown.json)
  Description: This workflow automates the creation of Markdown notes in your Obsidian Vault via Google Drive. It receives workflow results, processes information to generate structured content with YAML frontmatter, and stores the files in Google Drive.

- [2907-automated_churn_management.json](workflows/2907-automated_churn_management.json)
  Description: Automates daily churn risk detection and management, generating personalized offers for customers at high risk of churn.

- [2908-llm_chaining.json](workflows/2908-llm_chaining.json)
  Description: This workflow uses LLM chains to perform sequential and parallel tasks with different AI models, including fetching data from a webpage, analyzing with specific prompts, and combining results.

- [2909-workflow_management.json](workflows/2909-workflow_management.json)
  Description: This automated workflow manages and synchronizes n8n Workflows with Airtable and Dropbox. It retrieves Workflow details, prepares data, handles cron jobs, and updates or adds new records in Airtable.

- [2910-import_odoo_product_images.json](workflows/2910-import_odoo_product_images.json)
  Description: This workflow imports product images from Google Drive to Odoo, filtering and updating them based on model and SKU. It maintains a system for moving processed files and notifying the total downloaded.

- [2911-manejador_comentarios_ig.json](workflows/2911-manejador_comentarios_ig.json)
  Description: This automated workflow autonomously manages Instagram comments. It receives webhook notifications, validates the origin, extracts data, and uses an AI agent to respond appropriately.

- [2912-youtube-ai-summarizer.json](workflows/2912-youtube-ai-summarizer.json)
  Description: This workflow automates the summarization and analysis of YouTube playlists or videos using AI. It detects URLs, processes transcriptions, generates structured summaries, and stores embeddings for contextualized responses.

- [2914-openai-file-citation.json](workflows/2914-openai-file-citation.json)
  Description: This workflow extracts and formats citations from files stored in OpenAI from a conversation thread, ensuring references are correctly displayed with filenames.

- [2915-mcp-google-calendar.json](workflows/2915-mcp-google-calendar.json)
  Description: This workflow configures an MCP server integrated with Google Calendar to perform calendar operations like creating, updating, and deleting events using specific tools.

- [2916-telegram-rag-pdf.json](workflows/2916-telegram-rag-pdf.json)
  Description: This automated workflow processes a PDF document sent via Telegram, uploads it to Pinecone to perform question and answer searches with artificial intelligence.

- [2917-youtube-to-airtable.json](workflows/2917-youtube-to-airtable.json)
  Description: This workflow automates the extraction of YouTube video transcriptions and generates detailed summaries that are saved in Airtable.

- [2919-gestor_consultas_medicas.json](workflows/2919-gestor_consultas_medicas.json)
  Description: This workflow manages medical appointment rescheduling tasks and sends reminders via WhatsApp and Telegram using Google Calendar and Tasks, integrating tools like OpenAI to process text and messages.

- [2920-flujo-extraccion-apuestas.json](workflows/2920-flujo-extraccion-apuestas.json)
  Description: This automated workflow schedules the extraction of sports betting data using TheOddsAPI and Airtable. It performs daily captures at the beginning and end of the day for future events and results, respectively, and updates records in Airtable with detailed information.

- [2921-ai-agent-charts-generator.json](workflows/2921-ai-agent-charts-generator.json)
  Description: This workflow allows an AI agent to generate custom charts in conversations using OpenAI Structured Output to define Chart.js and Quickchart.io chart configurations.

- [2922-n8n_creator_leaderboard_report.json](workflows/2922-n8n_creator_leaderboard_report.json)
  Description: This automated workflow generates detailed reports on creators and workflows in n8n. It uses tools like OpenAI GPT-4 and Google Gemini to analyze and synthesize data, and then sends the results to Google Drive or Telegram.

- [2923-dashboard-metricas.json](workflows/2923-dashboard-metricas.json)
  Description: This workflow automates the update of a dashboard that collects and displays statistics and metrics from various sources like Docker, npm, GitHub, and Product Hunt. It uses Cron to schedule periodic executions, extracts data via HTTP requests, processes and formats the results, and updates WIDGETS on a dashboard host with authentication.

- [2924-hacker_news_video_creator.json](workflows/2924-hacker_news_video_creator.json)
  Description: This workflow automates video creation from Hacker News articles. It collects articles, analyzes them for relevance, generates images with Leonardo AI and RunwayML, and creates a video with Creatomate.

- [2926-google-sheets-to-postgres.json](workflows/2926-google-sheets-to-postgres.json)
  Description: This workflow automates data import from Google Sheets to PostgreSQL. It dynamically analyzes data to detect types and generate SQL schemas, creates tables if they don't exist, and performs insertions with appropriate formatting.

- [2927-convert-squarespace-to-shopify.json](workflows/2927-convert-squarespace-to-shopify.json)
  Description: This automated workflow converts Squarespace profiles to Shopify customers using Google Sheets. It extracts data from a Squarespace spreadsheet, processes and updates information in Shopify.

- [2928-sitemap-index-automatizado.json](workflows/2928-sitemap-index-automatizado.json)
  Description: This workflow automates URL indexing in Google Search Console using sitemap.xml. It extracts URLs from sitemap files, checks their status, and updates those that have been modified or are not indexed.

- [2929-support-sales-flow.json](workflows/2929-support-sales-flow.json)
  Description: This workflow implements a customer support and sales system that uses artificial intelligence to manage orders, update stock, and maintain conversations with users. The chatbot can check stock, place orders, and update availability in Google Sheets.

- [2930-exam-question-generator.json](workflows/2930-exam-question-generator.json)
  Description: Workflow for generating both open-ended and closed-ended exam questions from content in Google Docs using Qdrant vectors and different language models.

- [2931-linkedin-leads-enrichment.json](workflows/2931-linkedin-leads-enrichment.json)
  Description: Automated workflow for extracting and enriching LinkedIn lead data using Apollo.io and RapidAPI, with database management in Google Sheets. Includes profile retrieval, email, validation, post summarization, and status updates.

- [2932-bluesky-threads.json](workflows/2932-bluesky-threads.json)
  Description: This workflow creates threads on Bluesky using authentication and HTTP requests to publish initial posts and nested replies with a wait and loop scheme.

- [2933-monitoreo_precios.json](workflows/2933-monitoreo_precios.json)
  Description: This workflow automates price monitoring on different websites. It extracts prices of specific products using CSS selection, updates saved data, and sends notifications if there is a price decrease.

- [2936-api_schema_extractor.json](workflows/2936-api_schema_extractor.json)
  Description: Extracts API schemas by identifying and processing online technical documentation to generate a custom schema.

- [2937-tiktok-youtube-generator.json](workflows/2937-tiktok-youtube-generator.json)
  Description: This automated workflow generates multimedia content for TikTok and YouTube Shorts/Reels automatically using APIs like PiAPI for images and videos, ElevenLabs for voices, Google Drive for storage, and OpenAI for text. It includes idea capturing, image generation, video conversion, audio addition, element mixing, and final notification.

- [2938-auth0-login-flow.json](workflows/2938-auth0-login-flow.json)
  Description: This workflow implements an OAuth2 authentication system with Auth0, which initiates a user session by redirecting to a login page, obtains the authorization code, and then requests the access token to verify the user's identity.

- [2940-dmarc-processing-flow.json](workflows/2940-dmarc-processing-flow.json)
  Description: This automated workflow processes DMARC reports received by email, extracts and formats relevant data, and inserts it into a MySQL database. If DKIM or SPF checks fail, it sends notifications to Slack and email.

- [2941-blog-automation.json](workflows/2941-blog-automation.json)
  Description: This workflow automates blog post creation and publication using Google Sheets as a data source. It configures parameters, retrieves information from spreadsheets, processes custom prompts with OpenAI, generates content, validates dates and statuses, and updates the status in real-time.

- [2942-categorizador-ai-outlook.json](workflows/2942-categorizador-ai-outlook.json)
  Description: This workflow automatically categorizes Outlook emails using AI to classify them into different folders based on their content.

- [2943-auto-label-gmail.json](workflows/2943-auto-label-gmail.json)
  Description: This workflow automates the assignment of labels to new messages in Gmail using artificial intelligence. It collects emails, processes them with a language model to determine appropriate labels, and then applies them.

- [2945-automate-blog-ai.json](workflows/2945-automate-blog-ai.json)
  Description: This workflow automates the creation of blog articles in a brand's voice using AI. It analyzes existing content to extract style and tone characteristics, then generates new articles consistent with them.

- [2946-automate-content-generator-wordpress.json](workflows/2946-automate-content-generator-wordpress.json)
  Description: This automated workflow generates content for WordPress using DeepSeek R1, including SEO-friendly articles and titles, creates images with DALL-E, uploads them, and updates a Google Sheets spreadsheet.

- [2947-automate-support-issues.json](workflows/2947-automate-support-issues.json)
  Description: This automated workflow manages support issue resolution using AI to classify and resolve incidents in Jira. It analyzes comments, uses knowledge agents, and notifies via Slack if necessary.

- [2948-pinterest-analysis-ai.json](workflows/2948-pinterest-analysis-ai.json)
  Description: This automated workflow extracts and analyzes Pinterest data using its API, stores the information in Airtable, then uses OpenAI to generate content recommendations and sends a summary to Gmail.

- [2949-automate-sales-meeting-prep.json](workflows/2949-automate-sales-meeting-prep.json)
  Description: This automated workflow schedules meetings and sends notifications with relevant information via WhatsApp using artificial intelligence to summarize emails and LinkedIn profiles.

- [2950-automate-siem-enrichment-mitre.json](workflows/2950-automate-siem-enrichment-mitre.json)
  Description: This workflow automates SIEM alert enrichment using the MITRE ATT&CK framework, using Qdrant as a vector store and Zendesk to update incidents with contextualized information.

- [2951-automate-rfp-openai.json](workflows/2951-automate-rfp-openai.json)
  Description: Automates the RFP process by integrating with OpenAI to extract questions, generate answers, and notify via Slack and email.

- [2952-crawler-ai-scraper.json](workflows/2952-crawler-ai-scraper.json)
  Description: Workflow that uses AI agents to autonomously extract social media links from websites.

- [2953-influxdb-docker-deploy.json](workflows/2953-influxdb-docker-deploy.json)
  Description: This automated workflow deploys and manages an InfluxDB container in Docker for an application related to WHMCS/WISECP, supporting operations such as deployment, start, stop, suspend, mount, and disk control.

- [2954-financial-documents-assistant.json](workflows/2954-financial-documents-assistant.json)
  Description: This workflow monitors a local directory for financial documents and synchronizes changes with Qdrant using Mistral.ai to create a question-and-answer assistant.

- [2955-auto-content-generator.json](workflows/2955-auto-content-generator.json)
  Description: This workflow automates multimedia content creation based on data from Google Sheets. It generates images and cinematic videos with promotional texts, adds ambient sounds, and publishes the result on YouTube.

- [2956-nextcloud-docker-flow.json](workflows/2956-nextcloud-docker-flow.json)
  Description: This workflow configures and manages Docker environments for NextCloud using n8n, including actions like starting, stopping, suspending, unsuspending, mounting/unmounting disks, updating packages, and more. It also manages DNS connections and verifies domain validity.

- [2957-oaut-service-config.json](workflows/2957-oaut-service-config.json)
  Description: This workflow uses a language model to identify OAuth2 configurations from a service name. The process includes generating authorization and token URIs with a confidence score.

- [2958-formulario-datos.json](workflows/2958-formulario-datos.json)
  Description: This automated workflow records form data in Google Sheets and Airtable, extracts the submission date and time, and sends personalized emails.

- [2959-centroid_calculator.json](workflows/2959-centroid_calculator.json)
  Description: This workflow calculates the centroid of a set of vectors. It receives a GET request with an array of vectors, validates that they are consistent, and calculates their centroid.

- [2960-video_analyzer_youtube.json](workflows/2960-video_analyzer_youtube.json)
  Description: This workflow uses different language models to analyze a YouTube video via its transcription, structuring the analysis in JSON format and sending the results by email.

- [2961-anomaly-crops-detection.json](workflows/2961-anomaly-crops-detection.json)
  Description: This workflow uses image embeddings and clustering to detect anomalies in crops. It receives an image URL, converts it into a vector with Voyage.ai model, queries against vectors stored in Qdrant, and determines if it is similar to any known crop or detects anomalies.

- [2962-telegram-links-sync.json](workflows/2962-telegram-links-sync.json)
  Description: This workflow automates the synchronization of links between a Telegram channel and two services: Readeck and Hoarder. First, it uses a Telegram API to retrieve messages from the specified channel. Then, it filters and processes unsaved links in each service, making POST requests to store those that have not yet been added.

- [2963-spotify-sync-playlist.json](workflows/2963-spotify-sync-playlist.json)
  Description: This workflow synchronizes songs marked as favorites on Spotify with a specific playlist. It automatically adds new songs that are in your liked songs but not in the playlist and removes those that have been removed from your liked songs.

- [2964-image_generator_9_16.json](workflows/2964-image_generator_9_16.json)
  Description: This workflow generates 9:16 aspect ratio images from content and brand guidelines using OpenAI and Leonardo.ai to create optimized visual assets.

- [2965-instagram-content-generator.json](workflows/2965-instagram-content-generator.json)
  Description: This workflow automates Instagram content creation using current trends and AI image generation. It downloads popular Instagram content via an API, analyzes images with GPT-4, creates attractive captions, and generates new images with Flux AI. It publishes content to your business Instagram account and monitors post status.

- [2966-generar-palabras-clave-seo.json](workflows/2966-generar-palabras-clave-seo.json)
  Description: This workflow generates initial SEO keyphrases using AI based on the ideal customer profile.

- [2967-sql-agent-scheme.json](workflows/2967-sql-agent-scheme.json)
  Description: Workflow that uses an AI agent to generate SQL queries based on a database schema, saving the structure locally and using OpenAI to formulate SQL statements.

- [2968-image-embedder.json](workflows/2968-image-embedder.json)
  Description: This workflow automates image embedding creation through textual summarization. It downloads an image from Google Drive, extracts color information, and generates keywords using OpenAI, then combines this data to create a document that is stored in a vector store.

- [2969-chatbot_line.json](workflows/2969-chatbot_line.json)
  Description: This workflow configures a LINE chatbot that displays a loading animation upon receiving a message and uses an AI agent with CBT (Cognitive Behavioral Therapy, assumed) to respond to users. If the message is not text, it sends a warning.

- [2970-autoclip-video-generator.json](workflows/2970-autoclip-video-generator.json)
  Description: This automated workflow generates video clips by randomly selecting from videos and music in Google Drive, juxtaposes quotes, and then uploads them to YouTube.

- [2971-youtube-automatic-metadata-uploader.json](workflows/2971-youtube-automatic-metadata-uploader.json)
  Description: Workflow to upload videos to YouTube with automatically optimized metadata using transcriptions and AI.

- [2972-youtube-ai-agent.json](workflows/2972-youtube-ai-agent.json)
  Description: This workflow automates the extraction of details and transcriptions from YouTube videos, which are processed by an AI agent to allow for contextualized conversation and detailed content analysis.

- [2973-pinterest-analysis-ai-suggestions.json](workflows/2973-pinterest-analysis-ai-suggestions.json)
  Description: This automated workflow extracts and analyzes Pinterest Organic data using the API, stores the results in Airtable, and generates content recommendations with artificial intelligence for marketing.

- [2974-mcp_calendar_operations.json](workflows/2974-mcp_calendar_operations.json)
  Description: This workflow handles Google Calendar operations such as getting events, checking availability, updating, and deleting events.

- [2975-conversion-rate-optimizer.json](workflows/2975-conversion-rate-optimizer.json)
  Description: This workflow automates conversion rate optimization by analyzing a landing page through scraping and using an AI agent to perform a critical analysis and propose specific improvements.

- [2976-ai-research-jina.json](workflows/2976-ai-research-jina.json)
  Description: This automated workflow uses Jina AI's DeepSearch API to perform in-depth searches and analyses, formatting and cleaning the AI model-generated responses.

- [2978-linkedin-empresa-score.json](workflows/2978-linkedin-empresa-score.json)
  Description: This workflow automates searching for companies on LinkedIn using the Ghost Genius API, processes their data, evaluates their fitness with an AI model, and records them in a Google Sheets spreadsheet. First, it obtains detailed information for each company, filters those with more than 200 followers and a website, then checks if they already exist in the CRM. If they are new, it scores them with AI and finally adds them to the CRM with their score and relevant details.

- [2979-multi_methods_airtable.json](workflows/2979-multi_methods_airtable.json)
  Description: This workflow handles different HTTP methods to interact with an Airtable API, performing operations like creating, getting all, getting a record by ID, updating, and deleting records.

- [2980-reddit-pr-report.json](workflows/2980-reddit-pr-report.json)
  Description: This workflow automates the identification of trending stories by analyzing discussions on Reddit and subsequently analyzing them with an LLM to generate strategic PR reports.

- [2981-instagram_content_generator.json](workflows/2981-instagram_content_generator.json)
  Description: This workflow automates Instagram content creation based on the most popular trends, using AI to generate images and publish them. It scrapes specific trends like #blender3d and isometric, filters content by images, analyzes images with GPT-4 and OpenAI, generates attractive captions, creates new images with Flux AI, and checks if content already exists in a database to avoid duplication. It publishes on Instagram and sends notifications to a Telegram channel.

- [2982-amazon-best-seller-electronic-extractor.json](workflows/2982-amazon-best-seller-electronic-extractor.json)
  Description: This workflow extracts information from Amazon's best sellers in the electronics category using Bright Data and Google Gemini for structured data extraction.

- [2983-hacker-news-jobs-scraper.json](workflows/2983-hacker-news-jobs-scraper.json)
  Description: This workflow extracts and processes job offer information published on Hacker News using its API and Algolia, structures the data with OpenAI, and exports it to Airtable.

- [2984-hn-throwback-analyzer.json](workflows/2984-hn-throwback-analyzer.json)
  Description: This workflow collects and analyzes Hacker News front-page headlines for a specific date in past years, using an LLM to categorize them thematically and send the result to Telegram.

- [2985-hacker_news_video_content.json](workflows/2985-hacker_news_video_content.json)
  Description: This workflow automates the conversion of Hacker News articles into video content using RunwayML and LeonardoAI to generate custom images and videos.

- [2986-appointment-leads-follow-up.json](workflows/2986-appointment-leads-follow-up.json)
  Description: This automated workflow manages appointments and lead follow-ups using Twilio for SMS, Cal.com for appointment scheduling, and OpenAI for customer interactions. It detects commands like STOP to halt messages, updates Airtable with follow-up data, and sends reminders.

- [2987-gestion-solicitudes-AI.json](workflows/2987-gestion-solicitudes-AI.json)
  Description: Workflow that automates job application management using forms and AI tools to extract information, classify documents, and store data in Airtable.

- [2988-line-bot-flow.json](workflows/2988-line-bot-flow.json)
  Description: This workflow processes LINE messages, including text, images, and namecards, to store in Microsoft To Do and Teams, using OpenRouter for extractions and image agents.

- [2989-motion-illustration.json](workflows/2989-motion-illustration.json)
  Description: This workflow generates an animated illustration using Midjourney and Kling API. It first creates an image with Midjourney, then waits and processes the status to generate a video with Kling, finally returning the URL of the unwatermarked video.

- [2990-optimizar-prompt.json](workflows/2990-optimizar-prompt.json)
  Description: Workflow that optimizes prompts using an AI agent to improve clarity and specificity, sending the result via Telegram.

- [2991-auto_create_publish_videos.json](workflows/2991-auto_create_publish_videos.json)
  Description: This automated workflow creates and publishes social videos with AI using Telegram, GPT-4, and Blotato. It includes everything from video creation to distribution on multiple platforms like Instagram, YouTube, TikTok, Facebook, among others.

- [2992-telegram-chatbot-multi-format.json](workflows/2992-telegram-chatbot-multi-format.json)
  Description: This automated workflow manages messages and voice in Telegram, transcribes audio to text with OpenAI, processes inputs, and sends formatted responses.

- [2993-paul_graham_essays_milvus.json](workflows/2993-paul_graham_essays_milvus.json)
  Description: This workflow automates the extraction and storage of Paul Graham articles in Milvus, using OpenAI to generate responses with contextual citations.

- [2994-gemini-video-analysis.json](workflows/2994-gemini-video-analysis.json)
  Description: This workflow analyzes videos using the Gemini AI API. It downloads a video, uploads it to Google's servers, and generates a detailed description using the Gemini-2.0-flash-exp model.

- [2995-lead-automaton-v4.json](workflows/2995-lead-automaton-v4.json)
  Description: This automated workflow monitors entries in Google Sheets and sends notifications to Slack and Gmail upon receiving a new Lead. If the interest is hot and has not been followed up, it schedules a reminder after 3 minutes.

- [2996-perplexity_to_html.json](workflows/2996-perplexity_to_html.json)
  Description: This workflow automates the creation of an HTML page from Perplexity research, structuring and styling with Tailwind CSS.

- [2997-deep_research_agent.json](workflows/2997-deep_research_agent.json)
  Description: This automated workflow generates learnings from SEO search results for deepened research, using n8n, OpenAI, and Apify. It analyzes content, extracts key information, and organizes results in Notion.

- [2998-notion-clockify-sync.json](workflows/2998-notion-clockify-sync.json)
  Description: This workflow synchronizes data between Notion and Clockify, managing clients, projects, and tasks. It updates statuses and IDs bidirectionally.

- [2999-hr-it-chatbot-transcription.json](workflows/2999-hr-it-chatbot-transcription.json)
  Description: This workflow configures a chatbot for HR and IT assistance that processes text and audio messages in Telegram, uses OpenAI embeddings for transcriptions and PostgreSQL vector storage, answering questions based on internal policies.

- [3000-automatizacion_rrhh.json](workflows/3000-automatizacion_rrhh.json)
  Description: This workflow automates job posting and candidate evaluation using artificial intelligence. It includes application forms, CV analysis with ChatGPT, generation of personalized questionnaires, and tracking in Airtable.

- [3002-n8n-check-models.json](workflows/3002-n8n-check-models.json)
  Description: This workflow verifies and records which models are being used in each n8n workflow, collecting detailed information about relevant nodes and workflows.

- [3003-extract-summarize-indeed.json](workflows/3003-extract-summarize-indeed.json)
  Description: This workflow extracts and summarizes company information from Indeed using Bright Data and Google Gemini. It includes web scraping, LLM analysis, and webhook notifications.

- [3004-voice-chatbot-rag-qdrant.json](workflows/3004-voice-chatbot-rag-qdrant.json)
  Description: This workflow implements a voice chatbot that uses RAG (Retrieval-Augmented Generation) with ElevenLabs and OpenAI to answer questions using a vector database in Qdrant.

- [3005-chinese-translator-line.json](workflows/3005-chinese-translator-line.json)
  Description: This workflow translates LINE messages using OpenRouter.ai to get Chinese characters, pinyin, and English translation.

- [3006-linkedin-to-airtable.json](workflows/3006-linkedin-to-airtable.json)
  Description: This workflow automates the extraction of LinkedIn likes, filters the most recent and relevant posts, and records them in Airtable to organize them as content ideas.

- [3007-travel-agent-couchbase-vector.json](workflows/3007-travel-agent-couchbase-vector.json)
  Description: This workflow uses Google Gemini 2.0 Flash and OpenAI to create a travel planning agent with vector search capability in Couchbase, allowing searching and storing points of interest.

- [3008-minio-deploy.json](workflows/3008-minio-deploy.json)
  Description: This workflow automates the deployment and management of Docker containers for MinIO on a server with WHMCS/WISECP. It handles operations like creating, starting, stopping, suspending, mounting/unmounting disks, and configuring ACLs, plus Nginx integration for access.

- [3009-enra-zammad-sync.json](workflows/3009-enra-zammad-sync.json)
  Description: This workflow synchronizes Entra contacts with users in Zammad. It retrieves contacts from Microsoft Graph, compares them with existing users, and updates or creates new users in Zammad.

- [3010-coinmarketcap_dex_agent.json](workflows/3010-coinmarketcap_dex_agent.json)
  Description: This automated workflow acts as an intelligent agent tool to interact with the CoinMarketCap DEXScan API, allowing retrieval and real-time analysis of data on decentralized exchanges, trading pairs, volume, liquidity, and trading activity through an integrated multi-agent system.

- [3011-flujo-analisis-crowdstrike-detecciones.json](workflows/3011-flujo-analisis-crowdstrike-detecciones.json)
  Description: This automated workflow analyzes CrowdStrike detections, searches for indicators of compromise (IOCs) in VirusTotal, creates a ticket in Jira, and sends a notification to Slack.

- [3012-web-query-semantic-re-ranking.json](workflows/3012-web-query-semantic-re-ranking.json)
  Description: This workflow automates web queries and semantically re-ranks results using Brave and Google Gemini to improve relevance.

- [3014-factura-extraccion-llamaparse.json](workflows/3014-factura-extraccion-llamaparse.json)
  Description: This automated workflow extracts information from invoices in PDF format using LlamaParse and OpenAI. It detects emails with PDF attachments, processes the documents to obtain structured data, and stores it in a Google Sheets spreadsheet.

- [3015-automated-resume-review-system.json](workflows/3015-automated-resume-review-system.json)
  Description: This automated workflow allows for automated resume analysis and evaluation using OpenAI and Google Sheets. It includes uploading to Drive, information extraction, professional summary, and storage in spreadsheets.

- [3016-it-slack-ai-bot.json](workflows/3016-it-slack-ai-bot.json)
  Description: This automated workflow manages IT queries on Slack via a chatbot integrated with OpenAI and Confluence. It analyzes messages, verifies webhooks, avoids bots, and provides answers based on company knowledge.

- [3017-knn_land_classifier.json](workflows/3017-knn_land_classifier.json)
  Description: This workflow uses a KNN classifier to determine the class of an image based on its vector embedding. First, it obtains the image embedding via the Voyage AI API, then queries Qdrant with this embedding to find the nearest neighbors and applies majority voting to resolve conflicts.

- [3018-webflow-airtable-tables-creator.json](workflows/3018-webflow-airtable-tables-creator.json)
  Description: This workflow creates dynamic tables in Airtable for Webflow form submissions. It automates the creation of boards and records based on forms, using API credentials and handling errors.

- [3019-export_zammad_to_excel.json](workflows/3019-export_zammad_to_excel.json)
  Description: This workflow exports Zammad objects like Users, Roles, Groups, and Organizations to Excel files.

- [3020-convertir_imagenes_webp.json](workflows/3020-convertir_imagenes_webp.json)
  Description: This automated workflow converts JPG and PNG images to WEBP format using the APYHub API. It retrieves image URLs from a Google Sheets spreadsheet, determines the file type, performs the corresponding conversion, and updates the sheet with the new links. Finally, it uploads the converted images to Google Drive.

- [3021-automatizacion-pipedrive-tokens.json](workflows/3021-automatizacion-pipedrive-tokens.json)
  Description: This workflow automates the process of updating access and refresh tokens in Pipedrive. It uses Supabase to store and retrieve credentials, handles errors, and validates access tokens via webhooks.

- [3022-youtube_transcriber.json](workflows/3022-youtube_transcriber.json)
  Description: This workflow transcribes YouTube videos by validating the URL and structuring the text with OpenAI for a clean output in Portuguese.

- [3023-ai-whatsapp-support-bot.json](workflows/3023-ai-whatsapp-support-bot.json)
  Description: This workflow automates a customer support assistant on WhatsApp that uses artificial intelligence to answer questions based on the company's web content. It uses crawling and page analysis tools to obtain accurate information.

- [3024-ssl-expiry-alert.json](workflows/3024-ssl-expiry-alert.json)
  Description: This automated workflow monitors the expiration of SSL certificates for websites and sends alerts via email or Telegram when certificates are about to expire.

- [3025-zoom-meeting-assistant.json](workflows/3025-zoom-meeting-assistant.json)
  Description: This workflow automates Zoom meeting assistance by extracting and analyzing transcriptions to send summaries via email, create tasks in ClickUp, and schedule future appointments.

- [3026-shopify-mautic-sync.json](workflows/3026-shopify-mautic-sync.json)
  Description: This workflow synchronizes and manages marketing states between Shopify and Mautic. It detects changes in customer email subscriptions in Shopify, verifies their existence in Mautic, and automatically updates their segmentation or creates a new entry if necessary.

- [3027-retry-executions-hourly.json](workflows/3027-retry-executions-hourly.json)
  Description: This workflow schedules an automatic hourly execution to search and retry executions with an 'error' status in n8n, using saved credentials.

- [3028-telegram-woocommerce-notifications.json](workflows/3028-telegram-woocommerce-notifications.json)
  Description: This workflow sends Telegram notifications when a WooCommerce order status changes to 'Processing', including details like ID, customer name, total amount, and ordered products.

- [3029-wordpress-to-mautic-form.json](workflows/3029-wordpress-to-mautic-form.json)
  Description: Workflow that receives data from a WordPress form, normalizes and validates fields like email, and creates or updates an entry in Mautic if the address is valid.

- [3030-n8n-rag-living-data.json](workflows/3030-n8n-rag-living-data.json)
  Description: This workflow automates the integration of real-time data from Notion into a vector-based information retrieval system (RAG) using OpenAI and Supabase. It processes documents, splits them into chunks, generates embeddings with OpenAI, and stores the results in Supabase to enable semantic searches.

- [3031-google-drive-summarizer.json](workflows/3031-google-drive-summarizer.json)
  Description: This workflow downloads a file from Google Drive, summarizes it using Mistral AI, and sends the summary by email.

- [3032-gitlab-merge-request-review.json](workflows/3032-gitlab-merge-request-review.json)
  Description: This automated workflow analyzes changes in a GitLab merge request (MR), uses Claude AI to assess risk, and generates a structured report with recommendations, test cases, and corrections.

- [3033-clockify-backup.json](workflows/3033-clockify-backup.json)
  Description: This automated workflow extracts and stores detailed Clockify reports in GitHub. For each configured month, it checks if the file exists and updates it or creates a new one.

- [3034-google-analytics-seo-analysis.json](workflows/3034-google-analytics-seo-analysis.json)
  Description: This automated workflow collects and analyzes Google Analytics data for a webpage, comparing weekly statistics like page views, active users, and engagement rates. Then, it sends this information to an A.I. language model to get SEO recommendations and saves the results in Baserow.

- [3035-cripto-market-agent.json](workflows/3035-cripto-market-agent.json)
  Description: This workflow uses language agents and HTTP tools to query cryptocurrency market data via the CoinMarketCap API, providing information on exchanges, assets, indexes, and market sentiment.

- [3036-procesador-imagenes-ollama.json](workflows/3036-procesador-imagenes-ollama.json)
  Description: This workflow automates detailed image analysis using local Ollama visual models. It downloads an image from Google Drive, processes it with multiple models (like granita3.2-vision and llama3.2-vision), generates exhaustive descriptions in markdown, and saves them to Google Docs.

- [3037-youtube-summarizer-gpt.json](workflows/3037-youtube-summarizer-gpt.json)
  Description: This workflow extracts and processes YouTube video transcriptions to summarize them and maintain a conversation about their content using GPT-4o-mini and interacts via Telegram.

- [3038-personal_assistant_mcp_server.json](workflows/3038-personal_assistant_mcp_server.json)
  Description: This workflow configures a personal assistant that uses Google Gemini to process chat messages, maintains contextual memory, and interacts with MCP Server to perform tasks like scheduling appointments in Google Calendar, managing emails, updating Google Sheets spreadsheets, and searching/updating CRM rows.

- [3039-documento_procesamiento_ai.json](workflows/3039-documento_procesamiento_ai.json)
  Description: This automated workflow processes email attachments using LlamaParse to extract information and store it in Google Sheets and Drive, as well as sending summaries via Telegram.

- [3040-enra_zammad_sync.json](workflows/3040-enra_zammad_sync.json)
  Description: This workflow synchronizes Entra users with Zammad. It retrieves groups and members from Entra, creates universal user objects, compares data to update or deactivate users in Zammad.

- [3041-online-marketing-report.json](workflows/3041-online-marketing-report.json)
  Description: This automated workflow generates a weekly digital marketing report that collects and analyzes data from Google Analytics, Google Ads, and Meta Ads. It uses sub-workflows to obtain current and last year's metrics, processes the information with OpenAI, and sends the report by email.

- [3042-airtable-mcp-server.json](workflows/3042-airtable-mcp-server.json)
  Description: This workflow creates an MCP server using Airtable to interact with a database, allowing operations such as getting, searching, updating, and deleting records.

- [3043-three-view-to-video.json](workflows/3043-three-view-to-video.json)
  Description: Converts three-dimensional orthographic projections into dynamic animated video using GPT-4o and Kling to generate images and videos.

- [3044-video_generator_short_form.json](workflows/3044-video_generator_short_form.json)
  Description: This automated workflow generates short AI videos, using OpenAI for texts and prompts, Flux and Kling by PiAPI for images and videos, ElevenLabs for voice, and Creatomate for final video rendering. It then uploads them to all social media platforms.

- [3045-selenium_scraping_automatizado.json](workflows/3045-selenium_scraping_automatizado.json)
  Description: This workflow automates web data extraction using Selenium and OpenAI. It searches for relevant URLs on a given page, extracts information with AI, manages cookies and sessions for optional login, takes screenshots, and detects potential WAF blocks.

- [3048-analyze_youtube_workflow.json](workflows/3048-analyze_youtube_workflow.json)
  Description: This workflow analyzes YouTube videos to summarize them, generate transcriptions, and extract content using Google's Gemini AI API. It allows for different types of analysis such as concise summaries, verbatim transcriptions, subtitles with timestamps, and more.

- [3049-line-chat-gcal-gmail.json](workflows/3049-line-chat-gcal-gmail.json)
  Description: This automated workflow allows a LINE chatbot to integrate with Google Calendar and Gmail to manage events and email, using contextual memory and advanced response capabilities.

- [3050-telegram-ai-document-assistant.json](workflows/3050-telegram-ai-document-assistant.json)
  Description: This workflow creates a chatbot assistant on Telegram that processes PDF documents and uses Google Gemini to generate responses based on content stored in Supabase.

- [3051-airtable-markdown-to-html.json](workflows/3051-airtable-markdown-to-html.json)
  Description: This workflow processes markdown descriptions from an Airtable and converts them to HTML. If there is a single record, it updates that entry; if there are multiple records, it updates all of them with the converted HTML.

- [3052-email-chatbot-telegram-vector.json](workflows/3052-email-chatbot-telegram-vector.json)
  Description: This workflow implements a chatbot that uses Telegram and PostgreSQL with vectors to perform semantic and structured searches in email databases, allowing for advanced and contextualized interaction.

- [3053-Notify_user_quarantined_email.json](workflows/3053-Notify_user_quarantined_email.json)
  Description: This workflow notifies a Slack user when an email is quarantined and creates a Jira card if the email was opened before quarantine.

- [3054-business-canvas-generator.json](workflows/3054-business-canvas-generator.json)
  Description: Workflow that generates a Business Model Canvas from chat inputs, using an LLM for each section and transforming the results into HTML.

- [3055-discord-server-flow.json](workflows/3055-discord-server-flow.json)
  Description: This workflow sets up an integration with Discord that allows performing various actions such as sending messages, getting server and user information, managing roles, and waiting for responses.

- [3056-email-classifier.json](workflows/3056-email-classifier.json)
  Description: This automated workflow classifies and organizes emails in Gmail using AI to label them as Priority, Work-related, or Promotions.

- [3057-email_summary_dailly.json](workflows/3057-email_summary_dailly.json)
  Description: This workflow automates the creation of daily email summaries. Every morning at 7 AM, it retrieves emails received in the last 24 hours, organizes the data, uses OpenAI to synthesize the content, and then sends a structured report in HTML format.

- [3058-set_medoids_cultivos.json](workflows/3058-set_medoids_cultivos.json)
  Description: This workflow configures medoids (centers) of two types for anomaly detection in a crop dataset using Qdrant and the Voyage model. It calculates cluster representatives using distance matrices and text embedding vectors.

- [3059-openai-file-retrieval-rg.json](workflows/3059-openai-file-retrieval-rg.json)
  Description: This workflow uses OpenAI to retrieve and cite content from files stored in a vector store, formatting the output with Markdown or HTML.

- [3060-manipula-pdf-adobe.json](workflows/3060-manipula-pdf-adobe.json)
  Description: This workflow handles PDF file manipulation using the Adobe Services API. It performs authentication, uploads a PDF file, processes specific requests (like extraction), and waits for process completion before downloading the results.

- [3061-wordpress-ai-optimizer.json](workflows/3061-wordpress-ai-optimizer.json)
  Description: This workflow automates the creation and optimization of WordPress posts using AI to generate SEO-friendly titles, articles, and meta tags, as well as handling images and updating spreadsheets.

- [3062-coinmarketcap-analyst.json](workflows/3062-coinmarketcap-analyst.json)
  Description: This automated workflow uses an AI agent to analyze and send real-time cryptocurrency information via Telegram, using three specialized sub-agents: Crypto, Exchange & Community, and DEXScan. The system processes user queries, manages session memory, and uses CoinMarketCap API to provide detailed insights.

- [3063-animated_stories_generator.json](workflows/3063-animated_stories_generator.json)
  Description: This workflow creates animated stories using GPT-4o-mini to generate prompts, Midjourney to create images, and Kling to generate videos, then combines the videos in Creatomate.

- [3064-outlook-email-ai-assistant.json](workflows/3064-outlook-email-ai-assistant.json)
  Description: This workflow uses Microsoft Outlook to read untagged and uncategorized emails, processes their content with OpenAI to categorize them, updates their importance, and assigns categories. It also integrates contacts from Monday.com and Airtable for better contextualization.

- [3065-chat-voice-agent-RAG.json](workflows/3065-chat-voice-agent-RAG.json)
  Description: This workflow integrates a chatbot, voice agent, and telephony with Voiceflow, Google Calendar, and RAG to manage appointments, perform searches, and rely on Qdrant vectors.

- [3066-generar_fondo_grafico.json](workflows/3066-generar_fondo_grafico.json)
  Description: This workflow uses Midjourney, GPT-4o-mini, and Canvas API to generate a graphic wallpaper with emotive copy. First, GPT-4o-mini generates text based on the provided theme and scenario, then Midjourney creates an image according to the description, and finally Canvas designs the final composition with text and visual elements.

- [3067-format-phone-us.json](workflows/3067-format-phone-us.json)
  Description: This workflow processes and formats US phone numbers. It extracts only digits, checks the initial country code, adds the code if missing, and then formats the number in different formats like national and international.

- [3068-confluence-chatbot-ai.json](workflows/3068-confluence-chatbot-ai.json)
  Description: This workflow uses the Confluence API to search and retrieve specific content from pages, converts HTML to Markdown, and uses the GPT-4 AI agent to answer questions based on the provided context. Additionally, it sends responses via Telegram.

- [3069-email-routing-ai.json](workflows/3069-email-routing-ai.json)
  Description: This automated workflow classifies and routes business emails using AI to assign messages to different departments.

- [3070-spotify-archiver.json](workflows/3070-spotify-archiver.json)
  Description: This automated workflow archives monthly favorite Spotify songs in a Google spreadsheet and classifies Tracks into playlists using an AI model.

- [3071-line-file-save-to-google-drive.json](workflows/3071-line-file-save-to-google-drive.json)
  Description: This workflow automates downloading files from LINE, organizes them in Google Drive according to configuration, and records details in a spreadsheet.

- [3072-ollama-llm-router.json](workflows/3072-ollama-llm-router.json)
  Description: This workflow sets up an automatic private and local LLM route using Ollama to dynamically select the most appropriate model based on user input.

- [3073-reservation_medica.json](workflows/3073-reservation_medica.json)
  Description: This workflow uses an AI agent to manage medical appointments, integrating OpenAI and Google Calendar/Sheets. The agent receives messages, checks calendar availability, suggests times, or creates appointments.

- [3074-erp-chatbot-odoo.json](workflows/3074-erp-chatbot-odoo.json)
  Description: This automated workflow allows a chatbot contextualized with Window Memory to retrieve and summarize business opportunities from Odoo, using calculation tools and conversational agents to improve user assistance.

- [3075-video-narration-ai.json](workflows/3075-video-narration-ai.json)
  Description: This workflow automates the creation of a narrative script for videos using multimodal artificial intelligence. It downloads a video, extracts evenly distributed frames, processes them with a large language model (LLM) to generate descriptive texts, and then converts that text into audio.

- [3076-ai-seo-keyword-automation.json](workflows/3076-ai-seo-keyword-automation.json)
  Description: This automated workflow uses artificial intelligence to perform SEO keyword research. It includes topic expansion, competitor analysis, metrics like search volume and CPC, and generates a final optimized strategy.

- [3077-shopify-to-d365-sync.json](workflows/3077-shopify-to-d365-sync.json)
  Description: This workflow synchronizes Shopify orders with Dynamics 365 Business Central by creating orders and invoices. It detects if orders are from POS or web to generate invoices or orders respectively, checks customer existence, and creates new ones if not in BC. It handles multi-store locations and adds taxes and discounts as lines.

- [3078-ai_tech_newsletter.json](workflows/3078-ai_tech_newsletter.json)
  Description: This workflow automates the creation of a personalized tech newsletter using RSS feeds, OpenAI, and Gmail. Each day, it collects news articles from sources like Wired and TechCrunch, processes them, and stores them in a vector store. Weekly, it uses OpenAI to summarize the most relevant articles according to your interests and sends the recap by email.

- [3079-extract-spend-details.json](workflows/3079-extract-spend-details.json)
  Description: This workflow extracts and processes spending details from emails related to payments and invoices using Gmail as a data source. It analyzes emails specifically tagged to detect transactions, invoices, and payments, uses LLMs (Google Gemini and Groq) to structure the information, and finally inserts the data into a Google Sheets spreadsheet.

- [3080-email-ai-management.json](workflows/3080-email-ai-management.json)
  Description: This automated workflow efficiently manages emails using artificial intelligence to summarize, classify, and automatically respond. It uses Qdrant to store document vectors, OpenAI for embeddings and LLMs to generate responses, as well as integrating with Gmail and Outlook.

- [3081-whatsapp-ai-chatbot.json](workflows/3081-whatsapp-ai-chatbot.json)
  Description: This workflow implements a WhatsApp chatbot that uses RAG (Retrieval-Augmented Generation) technology to answer queries using OpenAI and Qdrant. It collects documents from Google Drive, vectorizes them with OpenAI, stores them in Qdrant, and uses the AI agent to answer questions based on them.

- [3082-pge-energy-cost-tracker.json](workflows/3082-pge-energy-cost-tracker.json)
  Description: This workflow automates the daily extraction of PG&E energy costs, including electricity and gas, from their website. It uses a browser to log in, navigate to relevant pages, extract data, and send an email with a formatted report.

- [3083-linkedin-profile-finder.json](workflows/3083-linkedin-profile-finder.json)
  Description: This workflow automates LinkedIn profile searches through a form where the user provides the full name and company. It uses Bright Data to perform Google searches and GPT-4o-mini to analyze results, extract relevant information, and generate a personalized email follow-up.

- [3084-notion-chatbot-generator.json](workflows/3084-notion-chatbot-generator.json)
  Description: This workflow generates a custom chatbot assistant for Notion databases, creating a workflow adapted to the provided schema. It analyzes the database URL, simplifies objects, and uses language agents to modify the workflow JSON according to specific needs.

- [3085-notion-ai-assistant.json](workflows/3085-notion-ai-assistant.json)
  Description: This workflow acts as a knowledge assistant that uses Notion to search for information and OpenAI to answer questions, efficiently organizing data from databases.

- [3086-linkedin-to-airtable.json](workflows/3086-linkedin-to-airtable.json)
  Description: This workflow automates searching for companies on LinkedIn and adds them to an Airtable CRM database. It searches for companies based on criteria like industry, size, and location, then checks if they already exist in the CRM and enters them if they are not duplicates.

- [3087-email-automatizado-con-HITL.json](workflows/3087-email-automatizado-con-HITL.json)
  Description: This automated workflow processes incoming emails via an IMAP mail system, summarizes them with AI, and generates automatic responses. The human user validates the response before sending it.

- [3088-whatsapp_medical_appointments_bot.json](workflows/3088-whatsapp_medical_appointments_bot.json)
  Description: This automated workflow sends medical appointment notifications via WhatsApp to users who have given consent, records messages in a Google Sheets spreadsheet, and allows responding to users through a scalable system.

- [3089-automated-backups-google-drive.json](workflows/3089-automated-backups-google-drive.json)
  Description: This automated workflow schedules daily backups of workflows, saving JSON files to Google Drive with a date and time stamp. It handles file retention by keeping only the most recent seven days' copies, deleting older ones, and sends Telegram notifications upon process completion.

- [3090-app-wordpress-genai.json](workflows/3090-app-wordpress-genai.json)
  Description: This workflow implements an application that uses RAG (Retrieval-Augmented Generation) and GenAI technologies to interact with WordPress content. It extracts text embeddings, manages documents in Supabase, and maintains chat memory using PostgreSQL.

- [3091-obsidian-podcast-flow.json](workflows/3091-obsidian-podcast-flow.json)
  Description: Workflow that converts Obsidian notes into audio for podcasts using OpenAI and stores data in Google Sheets.

- [3092-woocommerce-chatbot-posventa.json](workflows/3092-woocommerce-chatbot-posventa.json)
  Description: This automated workflow implements a post-sales support chatbot integrated with WooCommerce that uses artificial intelligence to handle customer inquiries, retrieve order information, verify identity, and provide assistance using OpenAI and Qdrant. It includes escalation to human operators via Telegram if necessary.

- [3093-bright_data_extractor.json](workflows/3093-bright_data_extractor.json)
  Description: This workflow uses Bright Data Web Scraper to extract structured data in bulk. It initiates a capture, waits for it to be ready, and then downloads the data. It handles errors and notifies via webhook.

- [3094-flujo-get-scaleway-servers.json](workflows/3094-flujo-get-scaleway-servers.json)
  Description: This workflow automates obtaining and filtering server information in Scaleway, including instances and bare metal, allowing searches by tags, name, public IP, or zone.

- [3095-remove-background-google-drive.json](workflows/3095-remove-background-google-drive.json)
  Description: This workflow removes the background from images stored in Google Drive using the Photoroom API, adding a configurable background color and saving the new images to a specific location.

- [3096-ahrefs-keyword-research.json](workflows/3096-ahrefs-keyword-research.json)
  Description: Keyword research workflow that uses Ahrefs to extract and format SEO data, passing through a query cleaning agent and then processing the information with the Gemini model for a structured response.

- [3097-mcp-supabase-agent.json](workflows/3097-mcp-supabase-agent.json)
  Description: This workflow implements a LangChain agent with vector retrieval and OpenAI embedding capabilities, using Supabase to store and manage data like messages, tasks, and status.

- [3098-ai-powered-research-flow.json](workflows/3098-ai-powered-research-flow.json)
  Description: Automated workflow that uses LLMs and APIs to conduct deep search research, generate search queries, analyze results, and create detailed reports.

- [3099-country-capitals-tool.json](workflows/3099-country-capitals-tool.json)
  Description: This workflow configures a chat assistant that can list capitals of fictitious countries or return the capital of a specific country based on a custom tool.

- [3100-openai-examples.json](workflows/3100-openai-examples.json)
  Description: This workflow uses different OpenAI models like ChatGPT to summarize and translate text, Whisper-1 for audio transcription, and DALLE-2 to generate images from textual descriptions.

- [3101-update-printify-products.json](workflows/3101-update-printify-products.json)
  Description: This workflow updates product titles and descriptions on Printify using OpenAI to optimize content and Google Sheets for management.

- [3102-organizar-archivos-con-AI.json](workflows/3102-organizar-archivos-con-AI.json)
  Description: This workflow automates file organization in local directories using AI. It monitors a specific folder, lists files and folders, uses Mistral AI to classify files by suggesting existing or new subdirectories, and then moves files according to AI indications.

- [3103-email-autoresponder-approval.json](workflows/3103-email-autoresponder-approval.json)
  Description: This automated workflow processes incoming emails, summarizes them, and generates responses with RAG using DeepSeek R1 and Qdrant. It allows for email approval before sending the final response.

- [3104-flux-image-edit.json](workflows/3104-flux-image-edit.json)
  Description: This workflow handles an image inpainting request using the FLUX API. It first receives an image and a mask via a webhook, then processes the image with the AI model to generate an edited version based on a user-provided prompt.

- [3105-generate-sql-from-schema.json](workflows/3105-generate-sql-from-schema.json)
  Description: This workflow generates SQL queries based on a database schema using artificial intelligence. It extracts information from the table structure and uses the OpenAI model to create SQL statements without needing to access the actual data.

- [3106-automate-content-generator-wordpress.json](workflows/3106-automate-content-generator-wordpress.json)
  Description: This workflow automates content creation for WordPress using DeepSeek. It generates articles, titles, and images based on ideas provided in a Google Sheets spreadsheet.

- [3107-ai-chatbot-memory-router.json](workflows/3107-ai-chatbot-memory-router.json)
  Description: This workflow implements a chatbot with long-term memory that uses dynamic routing tools to store and retrieve information using Google Docs, as well as sending notifications via Telegram or Gmail.

- [3108-subworkflow-dependency-graph.json](workflows/3108-subworkflow-dependency-graph.json)
  Description: This workflow automates the creation of a dependency graph between workflows in n8n and assigns tags automatically based on detected relationships. It analyzes flows to identify which are called by others, visualizes these relationships, and creates new tags if changes are detected.

- [3109-parents-bot-memory.json](workflows/3109-parents-bot-memory.json)
  Description: This workflow uses a chatbot to handle Telegram messages, transcribes voice to text, queries information, and stores data in vectors to improve contextual memory.

- [3110-automated-pdf-invoice-processing.json](workflows/3110-automated-pdf-invoice-processing.json)
  Description: This workflow automates information extraction from a PDF using LlamaParse and saves structured data to Airtable. It detects new files in Google Drive, processes content with OpenAI to extract specific invoice details, and creates records for both the main invoice and each detailed item.

- [3111-air-quality-scheduler.json](workflows/3111-air-quality-scheduler.json)
  Description: This workflow collects and processes air quality and pollen data using the Ambee API, then uses an AI agent to generate personalized recommendations based on the user's profile, and finally sends these recommendations by email.

- [3112-track-time-pausas.json](workflows/3112-track-time-pausas.json)
  Description: This workflow tracks work time and breaks in Notion. It creates a new page at the start, updates the end time, handles interruptions, and sends messages to the webhook.

- [3113-training_feedback_automat.json](workflows/3113-training_feedback_automat.json)
  Description: This automated workflow manages training feedback by sending notifications and creating tasks based on the given rating. It detects negative feedback for immediate action, creates tasks in UserTask, and emails managers.

- [3114-chatbot_personal_shopper.json](workflows/3114-chatbot_personal_shopper.json)
  Description: This workflow implements a personal shopper chatbot for WooCommerce that uses RAG with Google Drive and OpenAI. It analyzes chat messages to search for products or answer general questions using vectors stored in Qdrant.

- [3115-hdw-lead-management.json](workflows/3115-hdw-lead-management.json)
  Description: Automated workflow for LinkedIn lead management including search, data enrichment, analysis, and contact scoring using APIs like HDW and OpenAI, with Google Sheets integration for record keeping and tracking.

- [3116-webflow-slack-submissions.json](workflows/3116-webflow-slack-submissions.json)
  Description: This automated workflow sends Webflow form submissions to Slack. First, it checks if a channel corresponding to the form name exists; if not, it creates a new one and notifies in the #general channel. Then, it composes and sends the message with form data to the appropriate channel.

- [3117-ai-search-console-chat.json](workflows/3117-ai-search-console-chat.json)
  Description: This workflow uses OpenAI and Postgres to allow a chat agent to interact with Google Search Console data, retrieving information through natural conversation.

- [3118-Vision-Scraping-Agent.json](workflows/3118-Vision-Scraping-Agent.json)
  Description: This workflow automates web data extraction using artificial vision with Google Sheets, ScrapingBee, and Gemini. It takes full-page screenshots of websites, uses the Gemini model to extract information visually, and if it fails, resorts to HTML tools to ensure accurate data.

- [3119-batch_crops_qdrant.json](workflows/3119-batch_crops_qdrant.json)
  Description: This workflow loads a dataset of agricultural images into Qdrant using Voyage AI embeddings and Google Cloud Storage. It first checks if the collection exists, creates a new one if necessary, then processes images in batches and uploads them to the vector store.

- [3120-usuarios_ficticios.json](workflows/3120-usuarios_ficticios.json)
  Description: This workflow generates and processes JSON data to create CSV files with random names and email addresses, using GPT-4. Users can be subscribed or not, with optional subscription dates.

- [3121-deteccion_objetos_gemini.json](workflows/3121-deteccion_objetos_gemini.json)
  Description: This workflow uses the Gemini 2.0 API to detect objects in an image based on a prompt. It downloads an image, uses the Gemini model to get normalized coordinates of bounding boxes, and then adjusts them to the original image size to draw them on it.

- [3122-Proxmox-AI-Agent.json](workflows/3122-Proxmox-AI-Agent.json)
  Description: This automated workflow manages tasks in Proxmox using n8n and generative AI. It analyzes commands, validates inputs, generates API commands, and executes them.

- [3123-sync-todoist-notion.json](workflows/3123-sync-todoist-notion.json)
  Description: This workflow synchronizes tagged tasks in Todoist with Notion and marks tasks as sent once synchronization is complete.

- [3124-actualizar_n8n.json](workflows/3124-actualizar_n8n.json)
  Description: This workflow automates n8n updates by checking versions on GitHub, notifying via Telegram if there's a new version, and asking for confirmation before updating.

- [3125-linkedin-stories-generator.json](workflows/3125-linkedin-stories-generator.json)
  Description: This workflow extracts LinkedIn information using the Bright Data API and generates business stories with Google Gemini. It includes data processing, information extraction, and LLM summarization.

- [3126-multi-ai-chatbot-postgres-chart.json](workflows/3126-multi-ai-chatbot-postgres-chart.json)
  Description: This automated workflow allows a chatbot to interact with a PostgreSQL or Supabase database via SQL queries and generate charts visualized in QuickChart using AI agents. The system uses OpenAI to process user questions, execute SQL queries, get table definitions, and create charts based on the obtained results.

- [3127-email-ai-responder.json](workflows/3127-email-ai-responder.json)
  Description: This workflow automates email responses using DeepSeek R1 to summarize and send professional replies.

- [3128-gmail-mcp-server.json](workflows/3128-gmail-mcp-server.json)
  Description: This workflow configures an MCP server to interact with Gmail, allowing operations like searching, deleting, marking as read, adding or removing labels, and more.

- [3129-discord_cleaner.json](workflows/3129-discord_cleaner.json)
  Description: This automated workflow deletes Discord messages older than 7 days, running daily at 9:00 PM. It uses nodes to download channels, filter messages by date, and delete old ones, with pauses to respect API limits.

- [3130-extract-google-maps.json](workflows/3130-extract-google-maps.json)
  Description: This workflow uses Google Maps and scraping tools to extract business data like name, address, phone, email, and website. It uses OpenAI to process requests and save to Google Sheets.

- [3131-ssl-expiry-monitor.json](workflows/3131-ssl-expiry-monitor.json)
  Description: This automated workflow monitors the expiration date of SSL certificates for websites stored in a Google spreadsheet. Every week, it extracts URLs, checks SSL certificate status using ssl-checker.io, and sends an email if any certificate is due to expire in less than 7 days.

- [3132-ai-agent-chatbot-memory.json](workflows/3132-ai-agent-chatbot-memory.json)
  Description: This workflow implements a chatbot agent with integrated long-term memory and note storage, using Google Docs to save memories and notes, and Telegram for responses. The system uses different language models like GPT-4o-mini and DeepSeek-V3 to process messages and maintain a contextualized conversation.

- [3133-phone-agent-lead-qualification.json](workflows/3133-phone-agent-lead-qualification.json)
  Description: This automated workflow manages outbound and inbound calls, qualifying leads and scheduling appointments using RetellAI, Google Sheets, Twilio, and Gmail. It detects new opportunities in Google Sheets, sends SMS reminders, schedules automated calls with RetellAI, handles phone appointments, records interactions, sends confirmation emails, and analyzes with OpenAI.

- [3134-line-bot-ocr-to-sheets.json](workflows/3134-line-bot-ocr-to-sheets.json)
  Description: This automated workflow collects data from an image sent to a LINE bot, processes it to extract relevant information using OCR, and then stores the data in Google Sheets.

- [3135-docker-immich-deploy.json](workflows/3135-docker-immich-deploy.json)
  Description: This workflow configures and manages Docker environments for the Immich application, including deployment, start, stop, suspend, disk mounting, and user and ACL management. It uses SSH and Webhooks to interact with the server.

- [3136-tavily-search-extract.json](workflows/3136-tavily-search-extract.json)
  Description: This workflow automates information search and extraction using the Tavily API, filtering results by relevance and summarizing content with OpenAI.

- [3137-calificacion-leads-gpt.json](workflows/3137-calificacion-leads-gpt.json)
  Description: This workflow automates lead scoring using Google Sheets and GPT-4. It detects new entries in a spreadsheet, sends them to OpenAI to assess their quality, and updates the status in the same sheet with a rating and explanation.

- [3138-qualify-leads-pipedrive.json](workflows/3138-qualify-leads-pipedrive.json)
  Description: This automated workflow qualifies lead responses in Pipedrive using artificial intelligence to determine their interest and creates an opportunity if the lead shows interest.

- [3139-AppointmentQualifierAI.json](workflows/3139-AppointmentQualifierAI.json)
  Description: Form workflow that uses artificial intelligence to qualify appointment requests and manages their approval through n8n-integrated forms.

- [3140-n8n-credentials-agent.json](workflows/3140-n8n-credentials-agent.json)
  Description: This workflow automates n8n workflow credential management by storing them in an SQLite database and uses an AI agent to perform advanced searches via SQL.

- [3141-load_prompts_github.json](workflows/3141-load_prompts_github.json)
  Description: This workflow loads prompts from a GitHub repository and processes them to dynamically replace variables.

- [3142-social-media-publisher.json](workflows/3142-social-media-publisher.json)
  Description: This automated workflow manages content publishing on social media platforms like Instagram, LinkedIn, Facebook, X, and TikTok through a form that accepts photos or videos. It detects the file type (image or video), sends the necessary information to the corresponding API, and displays success or error messages.

- [3144-chatbot_companyIdocs.json](workflows/3144-chatbot_companyIdocs.json)
  Description: This workflow automates the creation of a chatbot that uses company documents stored in Google Drive and Gemini to answer questions.

- [3145-rag_context_chunking.json](workflows/3145-rag_context_chunking.json)
  Description: This workflow automates the creation of contextual vectors from documents in Google Drive using RAG (Retrieval-Augmented Generation) with section splitting and storage in Pinecone.

- [3146-reconcile-rent-payments.json](workflows/3146-reconcile-rent-payments.json)
  Description: This workflow automates rent payment reconciliation using an OpenAI model to detect and flag discrepancies in payments against a local Excel database. It identifies misses, incorrect payments, due dates, and alerts necessary actions.

- [3147-reddit-n8n-analizador.json](workflows/3147-reddit-n8n-analizador.json)
  Description: This workflow collects and analyzes recent Reddit posts related to n8n, using OpenAI to classify and summarize the posts.

- [3148-remove_pii_from_csv.json](workflows/3148-remove_pii_from_csv.json)
  Description: This workflow automates the removal of personally identifiable information (PII) from CSV files hosted on Google Drive. It uses OpenAI to identify columns with sensitive information and generates a new file without such data.

- [3149-outlook-ai-email-assistant.json](workflows/3149-outlook-ai-email-assistant.json)
  Description: This workflow automates email management in Microsoft Outlook using artificial intelligence to categorize and prioritize emails. It extracts relevant information, processes the email body to remove HTML formatting, queries external databases like Airtable and Monday.com for additional context, and uses the OpenAI model to assign categories. It updates importance and categories in Outlook according to defined rules.

- [3150-whatsapp-ai-responder.json](workflows/3150-whatsapp-ai-responder.json)
  Description: This automated workflow manages WhatsApp messages using AI to respond professionally. It analyzes different message types (text, audio, video, and image), processes them with tools like Google Gemini and Wikipedia, and generates timely responses.

- [3151-dub-co-url-shortener.json](workflows/3151-dub-co-url-shortener.json)
  Description: This workflow configures and automates short link creation using the Dub.co API. It allows entering a long URL, optionally a custom slug and domain, and creates or updates the corresponding link.

- [3152-property_leads_enrichment.json](workflows/3152-property_leads_enrichment.json)
  Description: This workflow automates obtaining real estate property data using BatchData, performs advanced filtering and enrichment with owner information, formats results, and exports them to CRM and Excel.

- [3153-reschedule-overdue-asana.json](workflows/3153-reschedule-overdue-asana.json)
  Description: This automated workflow, scheduled to run daily at 7 AM, retrieves assigned tasks from Asana and manages job statuses. It reschedules overdue tasks to the current day if they are open and deletes those that have already been completed.

- [3154-dynamic_form_dropdown.json](workflows/3154-dynamic_form_dropdown.json)
  Description: This workflow configures a form with a dynamic dropdown field that updates with values obtained from an external data source, such as a Google Sheets spreadsheet. The structure includes nodes to capture form submission, retrieve data from the source, transform it, and update the form with new options.

- [3155-telegram-neuroai-integration.json](workflows/3155-telegram-neuroai-integration.json)
  Description: This workflow uses the NeurochainAI API to process messages and generate responses or images in Telegram. It detects commands with /flux, sends prompts, and manages errors.

- [3156-deepseek-telegram-agent.json](workflows/3156-deepseek-telegram-agent.json)
  Description: This workflow uses a DeepSeek AI agent integrated with Telegram to handle conversations, validating users and chats, processing text, audio, and image messages, retrieving long-term memories from Google Docs, and responding via the Telegram API.

- [3157-test-webhooks-n8n-postbin-example.json](workflows/3157-test-webhooks-n8n-postbin-example.json)
  Description: This workflow allows testing webhooks in n8n using PostBin and BambooHR without needing to modify the WEBHOOK_URL variable. It creates a bin in PostBin, registers a webhook in BambooHR, tests its functionality, and notifies Slack about new employees.

- [3158-scrape-news-with-ai-to-nocodb.json](workflows/3158-scrape-news-with-ai-to-nocodb.json)
  Description: This workflow extracts HTML from a webpage specifically with CSS, then summarizes links and publication dates, filters by recent date, gets individual post content, generates summaries and keywords using OpenAI, and stores data in NocoDB.

- [3159-trustpilot-sentiment.json](workflows/3159-trustpilot-sentiment.json)
  Description: This workflow extracts and analyzes Trustpilot reviews using DeepSeek for detailed information and then OpenAI to assess sentiment.

- [3160-chatgpt-email-responses.json](workflows/3160-chatgpt-email-responses.json)
  Description: This automated workflow sends a ChatGPT response via email when an email is received and records responses in Google Sheets. It also logs feedback to improve the model.

- [3162-google-analytics-to-ai-seo-analysis.json](workflows/3162-google-analytics-to-ai-seo-analysis.json)
  Description: This workflow collects web analytics data, processes and sends information to an AI model for weekly comparative SEO analysis, saving results in Baserow.

- [3163-gmail-to-drive-pdfs.json](workflows/3163-gmail-to-drive-pdfs.json)
  Description: This workflow automates the transfer of specific PDF files from Gmail to Google Drive using OpenAI to filter and upload only those matching a given term.

- [3165-sentiment-linear-slack.json](workflows/3165-sentiment-linear-slack.json)
  Description: This workflow continuously monitors conversations in Linear support issues, performs sentiment analysis on comments, and notifies via Slack if sentiment becomes negative.

- [3166-buscar_palabras_clave.json](workflows/3166-buscar_palabras_clave.json)
  Description: This workflow automates main keyword search using NocoDB and DataforSEO to analyze search volumes on Google and YouTube. It generates and updates data in batches in a database.

- [3167-slack-ai-chatbot-rag.json](workflows/3167-slack-ai-chatbot-rag.json)
  Description: Workflow for a Slack chatbot integrated with RAG that uses Qdrant embeddings and vectors to answer questions based on internal documents.

- [3168-generar_palabras_clave_seo.json](workflows/3168-generar_palabras_clave_seo.json)
  Description: This workflow generates new SEO keywords and gets their search volumes using the Google Ads API. It analyzes submitted keywords, extracts metrics like competition and average monthly volume, and updates a spreadsheet.

- [3169-siri_ai_agent.json](workflows/3169-siri_ai_agent.json)
  Description: Workflow that uses Siri to activate an OpenAI agent via Apple Shortcuts, processing voice commands and generating responses.

- [3170-auto-tag-wordpress.json](workflows/3170-auto-tag-wordpress.json)
  Description: This workflow automates tag assignment in WordPress using AI. It analyzes RSS feeds, generates and structures tags, creates new ones if necessary, and updates existing ones.

- [3171-utm-link-generator-with-analytics.json](workflows/3171-utm-link-generator-with-analytics.json)
  Description: This workflow creates custom UTM links, generates QR codes, and schedules Analytics reports to monitor their performance.

- [3172-automated-social-media-email.json](workflows/3172-automated-social-media-email.json)
  Description: This automated workflow allows analyzing LinkedIn and Twitter posts from leads, generating a personalized email using OpenAI, and sending it automatically.

- [3173-social-banner-generator.json](workflows/3173-social-banner-generator.json)
  Description: This workflow automates social banner creation using n8n Forms to capture event data, OpenAI to generate images, and BannerBear to create the final banner.

- [3174-analisis-seo-serp.json](workflows/3174-analisis-seo-serp.json)
  Description: Automates SERPBear SEO data analysis by sending information to OpenRouter for a summary and saving results in Baserow.

- [3175-google-doc-summarizer.json](workflows/3175-google-doc-summarizer.json)
  Description: This automated workflow monitors a specific folder in Google Drive, gets new .doc documents, extracts their content, and summarizes it using an AI model, then stores the summary along with metadata in a Google Sheets spreadsheet.

- [3177-email-to-line-summarizer.json](workflows/3177-email-to-line-summarizer.json)
  Description: This workflow automates reading emails, summarizing them with artificial intelligence, and sending them to the LINE messenger.

- [3178-youtube-summarizer.json](workflows/3178-youtube-summarizer.json)
  Description: This workflow automates YouTube video summarization by extracting transcriptions and using a language engine to generate concise summaries.

- [3179-google-reminder-bot.json](workflows/3179-google-reminder-bot.json)
  Description: This automated workflow sends a friendly and personalized notification via Telegram reminding of Google Calendar events up to 1 hour in advance, avoiding duplicates.

- [3180-sqlite-ai-agent.json](workflows/3180-sqlite-ai-agent.json)
  Description: This workflow allows interacting with an SQLite database using an AI agent. It downloads, extracts, and loads the database locally, then uses the SQL agent to answer questions based on the data.

- [3181-telegram-ai-bot.json](workflows/3181-telegram-ai-bot.json)
  Description: This workflow automates a Telegram chatbot that uses OpenAI and LangChain to process messages, maintain contextual memory, and generate images with Dall-E 3.

- [3182-spotify_telegram_bot.json](workflows/3182-spotify_telegram_bot.json)
  Description: This workflow uses Telegram to receive music messages, queries OpenAI for song information, and plays music on Spotify.

- [3183-ollama-chat-flow.json](workflows/3183-ollama-chat-flow.json)
  Description: This workflow processes chat messages using Ollama's Llama 3.2 model via a basic LLM chain to generate structured responses in JSON format.

- [3184-audio-transcription-notion.json](workflows/3184-audio-transcription-notion.json)
  Description: This workflow automates audio file transcription from Google Drive, uses GPT-4 to summarize content, and stores the summary in Notion.

- [3185-transform-image-to-lego.json](workflows/3185-transform-image-to-lego.json)
  Description: This workflow transforms an image received via LINE into a LEGO style using the DALL-E API.

- [3187-traductor_telegram_audio.json](workflows/3187-traductor_telegram_audio.json)
  Description: This workflow translates voice messages in Telegram using AI. It automatically detects the language and translates them to the configured language.

- [3188-ai-voice-chat.json](workflows/3188-ai-voice-chat.json)
  Description: This workflow implements a voice chatbot that uses Webhook, Memory Manager, OpenAI, Google Gemini, and ElevenLabs to maintain a contextualized conversation with the user. The process includes transcribing audio, storing and retrieving context, generating AI responses, and converting them to audio.

- [3189-ubicacion-trabajo.json](workflows/3189-ubicacion-trabajo.json)
  Description: This automated workflow automatically records clock-in and clock-out times based on location using Webhooks, Google Sheets, and Drive. It detects if the worksheet exists, creates a new one if not present, and records time data with date and address.

- [3197-slack-to-linear-tickets.json](workflows/3197-slack-to-linear-tickets.json)
  Description: This automated workflow monitors a Slack channel for messages with the ticket emoji, uses OpenAI to generate ticket titles and descriptions, and creates incidents in Linear if no duplicates exist.

- [3199-text_automation.json](workflows/3199-text_automation.json)
  Description: Workflow to automate text translation and editing tasks using Apple Shortcuts and OpenAI. Analyzes request type, performs corresponding action with GPT-4 Mini, and responds to the Shortcut.

- [3201-whatsapp-ai-sales-agent.json](workflows/3201-whatsapp-ai-sales-agent.json)
  Description: This automated workflow uses WhatsApp to receive user messages and respond via an AI agent integrated with a vectorized knowledge base. It includes downloading a PDF catalog, processing and storing it in a vector store, and managing unsupported message types.

- [3202-whatsapp-bot-process.json](workflows/3202-whatsapp-bot-process.json)
  Description: This automated workflow processes WhatsApp messages, handles different types like audio, video, and image using Google Gemini for transcription and analysis, and uses an AI agent to respond.

- [3203-video-narration-generator.json](workflows/3203-video-narration-generator.json)
  Description: This workflow automates narrative script creation for videos using OpenAI and then generates audio from that script.

- [3205-backup-n8n.json](workflows/3205-backup-n8n.json)
  Description: This automated workflow performs a daily backup of n8n workflows to Google Drive. It creates and verifies 'n8n_backups' and 'n8n_old' folders, moves old copies to the 'n8n_old' folder, and deletes those exceeding 30 days.

- [3207-waitlist-verification.json](workflows/3207-waitlist-verification.json)
  Description: Workflow to manage a waitlist including user registration, verification code generation, email sending, and validation. If the code is incorrect, the user is asked to retry. Once validated, it's saved in Google Sheets.

- [3208-sql-agent-chart-generator.json](workflows/3208-sql-agent-chart-generator.json)
  Description: This workflow uses an SQL agent and OpenAI to generate responses with real-time visualizations. The user can ask questions about data, and the system will determine whether to include a graph using Chart.js, triggering a sub-workflow to create an image compatible with Quickchart.io.

- [3210-google_maps_email_scraper.json](workflows/3210-google_maps_email_scraper.json)
  Description: This workflow extracts and processes business emails from Google Maps using a list of queries. It searches for URLs related to initial searches, filters irrelevant ones, scrapes resulting pages to find email addresses, removes duplicates, and imports results into a Google spreadsheet.

- [3211-blueSky-welcome-bot.json](workflows/3211-blueSky-welcome-bot.json)
  Description: This workflow schedules an automatic welcome message to new followers on BlueSky. It first logs in, then lists followers and compares with a saved database to detect newcomers. New followers receive a private message with defined text. The follower list is updated in a JSON file.

- [3212-cv-screening.json](workflows/3212-cv-screening.json)
  Description: This automated workflow downloads a CV from a URL, extracts its PDF content, and sends the information along with a job description to OpenAI to get a structured evaluation determining the candidate's profile based on job requirements.

- [3213-import-productboard-to-snowflake.json](workflows/3213-import-productboard-to-snowflake.json)
  Description: This workflow imports Productboard data (notes, companies, and features) into Snowflake. It uses HTTP requests to retrieve information from Productboard, performs manual mappings, and updates tables in Snowflake. Includes a Slack notifier with weekly summaries.

- [3215-linear_productboard_sync.json](workflows/3215-linear_productboard_sync.json)
  Description: This workflow synchronizes project status and end dates in Linear with a feature in Productboard. It automatically updates statuses and dates in Productboard based on Linear data and notifies changes via Slack.

- [3216-aplicacion_cv_automatizada.json](workflows/3216-aplicacion_cv_automatizada.json)
  Description: Application workflow for AI-optimized CV and application form management, including document validation, information extraction, and Airtable storage.

- [3217-appointment-scheduling-flow.json](workflows/3217-appointment-scheduling-flow.json)
  Description: This workflow automates professional appointment management using interactive forms and human approval. It receives requests, classifies inquiries with AI, validates terms, schedules dates/times, notifies the user, and manages approved or rejected appointments.

- [3218-newsletter-survey.json](workflows/3218-newsletter-survey.json)
  Description: This workflow collects user information via a multi-page form: email initially, then additional data like name, country, job level, job functions, no-code experience, and product hobbies. Data is saved to Google Sheets, and a Slack notification is sent.

- [3223-search-console-report.json](workflows/3223-search-console-report.json)
  Description: This workflow extracts data from Search Console via three different reports (keywords, pages, and dates) using the Google API. Data is processed to separate it and then update a Google spreadsheet with detailed information on clicks, impressions, CTR, and positions.

- [3227-calendly-klicktipp-sync.json](workflows/3227-calendly-klicktipp-sync.json)
  Description: This automated workflow synchronizes Calendly events with KlickTipp, handling bookings and cancellations, transforming data to ensure guests are correctly added or removed from the subscriber list.

- [3228-linear-sentiment-monitor.json](workflows/3228-linear-sentiment-monitor.json)
  Description: This workflow automates monitoring active issues in Linear, performs sentiment analysis on issue comments using OpenAI, and updates an Airtable table with emotional status. It detects negative sentiment transitions to send Slack notifications.

- [3229-ai_content_generator.json](workflows/3229-ai_content_generator.json)
  Description: This workflow uses AI to analyze existing articles and extract voice and style features, then generates new content following those guidelines and publishes to WordPress.

- [3230-gemini-bounding-box.json](workflows/3230-gemini-bounding-box.json)
  Description: This workflow uses the Gemini 2.0 API to detect objects in images and draw custom bounding boxes.

- [3231-transcription-ai-flow.json](workflows/3231-transcription-ai-flow.json)
  Description: This workflow automates real-time meeting transcription, structures data, and generates summaries using OpenAI and PostgreSQL databases.

- [3232-automated-backup.json](workflows/3232-automated-backup.json)
  Description: This workflow automates job backups in GitHub using n8n. It stores workflows as JSON files in a designated repository.

- [3234-invoice-parser-flow.json](workflows/3234-invoice-parser-flow.json)
  Description: This automated workflow detects new files in Google Drive, sends them to LlamaParse for analysis, and extracts invoice information. Processed data is stored in Airtable as invoice records and their respective detailed items.

- [3235-phishing-email-monitor.json](workflows/3235-phishing-email-monitor.json)
  Description: This automated workflow monitors Gmail and Outlook email, generates HTML screenshots, analyzes threats with ChatGPT-4, and creates Jira tickets for phishing.

- [3236-email-threat-detection.json](workflows/3236-email-threat-detection.json)
  Description: This workflow automates email threat detection through integration with Gmail and Outlook, analysis with ChatGPT, and Jira ticket creation.

- [3237-ai_magic_position.json](workflows/3237-ai_magic_position.json)
  Description: This workflow includes an AI agent with memory and vector retrieval capabilities, connected to OpenAI and HTTP tools for positioning flows.

- [3240-strava-to-sheets.json](workflows/3240-strava-to-sheets.json)
  Description: This workflow schedules a job that every two hours extracts Strava activities, filters those not saved in Google Sheets, and processes them to update a spreadsheet with details like distance, date, time, and elevation gain.

- [3241-ai-meeting-automator.json](workflows/3241-ai-meeting-automator.json)
  Description: This automated workflow uses an AI agent to process meeting transcriptions, extract tasks, and notify the client. It uses Airtable to create tasks and Google Calendar to schedule appointments.

- [3243-service-now-slack-notifications.json](workflows/3243-service-now-slack-notifications.json)
  Description: This workflow automates notifying a Slack channel of recent ServiceNow incidents every 5 minutes. It uses a timestamp to search for incidents created in the last 5 minutes and, if new ones exist, sorts them by number and sends formatted details to Slack. If an error occurs with ServiceNow, it reports the problem.

- [3245-csvToJsonParser.json](workflows/3245-csvToJsonParser.json)
  Description: This workflow processes a POST request with data in CSV or JSON format. First, it checks the content type and extracts data using ExtractFromFile. Then, it converts RAW data to CSV if necessary. If errors occur, it returns a 500 code with an error message. If conversion is successful, it adds data to the JSON body and responds with a 200 code.

- [3251-automated-social-media-email.json](workflows/3251-automated-social-media-email.json)
  Description: This automated workflow extracts LinkedIn and Twitter posts from leads, processes them to generate personalized messages with OpenAI, and sends automated emails.

- [3252-docker-registry-cleaner.json](workflows/3252-docker-registry-cleaner.json)
  Description: This automated workflow removes old images and tags from a Docker registry, keeping only the last 10 versions and notifying of changes.

- [3253-cyber-attack-vector-store.json](workflows/3253-cyber-attack-vector-store.json)
  Description: This workflow automates cyber incident management using MITRE ATT&CK. It analyzes SIEM alerts with LLM, queries Qdrant vector databases, and updates Zendesk.

- [3255-flujo-independiente.json](workflows/3255-flujo-independiente.json)
  Description: This workflow implements an independent process that starts a secondary execution via a webhook and resumes it in the main context.

- [3256-github-backup-workflow.json](workflows/3256-github-backup-workflow.json)
  Description: This workflow automates job backups in GitHub by comparing and updating JSON files. It uses a loop to process each instance, checks differences between versions, and manages create or edit operations based on status.

- [3258-automate-lead-generation-suitecrm.json](workflows/3258-automate-lead-generation-suitecrm.json)
  Description: Workflow to automate lead generation in SuiteCRM using web forms and Google Sheets. Allows creating Leads with exclusive coupons by checking for duplicates and updating a spreadsheet.

- [3259-notion-md-sincro.json](workflows/3259-notion-md-sincro.json)
  Description: This workflow automates Notion block synchronization by converting rich text to Markdown format and vice versa, allowing content updates with formatting.

- [3260-fact-checking_workflow.json](workflows/3260-fact-checking_workflow.json)
  Description: This workflow automates fact-checking and text analysis. It separates text into sentences, uses LLM to mark statements as correct or incorrect, and produces a report with identified inaccuracies.

- [3261-bbc_podcast_workflow.json](workflows/3261-bbc_podcast_workflow.json)
  Description: This workflow extracts and classifies BBC news, generates a podcast script using LLM, and sends them to Hugging Face for audio conversion.

- [3263-ai-resume-screening.json](workflows/3263-ai-resume-screening.json)
  Description: Automated workflow to evaluate resumes based on a job description using artificial intelligence. Analyzes, classifies, and organizes candidates into folders according to their profile.

- [3264-zoom-stripe-payments.json](workflows/3264-zoom-stripe-payments.json)
  Description: This automated workflow creates Zoom meetings and links secure payments with Stripe for events. It automates appointment creation, customer invoicing, and sends email notifications with necessary details.

- [3266-yt-ai-playlist.json](workflows/3266-yt-ai-playlist.json)
  Description: This workflow creates and updates a YouTube playlist with AI news, deleting the previous one and notifying of its creation.

- [3267-certificado-automatico.json](workflows/3267-certificado-automatico.json)
  Description: This workflow automates certificate generation and sending based on a Google Forms questionnaire. It collects data from responses, verifies scores, creates a personalized presentation with the user's name, converts the presentation to PDF, and emails the certificate to the user if they pass.

- [3268-prompt-generator.json](workflows/3268-prompt-generator.json)
  Description: Workflow to generate and organize optimized prompts in Airtable using Google Gemini. Allows categorizing and structuring chatbot prompts for better management in n8n.

- [3269-gong-call-processing.json](workflows/3269-gong-call-processing.json)
  Description: This workflow automates extracting relevant information from sales calls recorded in Gong and Salesforce. It searches for primary opportunities with specific values and stages, formats call data, and sends processed information to a preprocessor for further analysis.

- [3270-call-processing-flow.json](workflows/3270-call-processing-flow.json)
  Description: This workflow automates sales call data extraction and processing, integrating complementary information like competitors and integration lists to enrich transcripts before sending them to an AI system.

- [3271-gong-call-processor.json](workflows/3271-gong-call-processor.json)
  Description: This workflow extracts and processes sales call data from Gong to generate an enriched transcript with metadata like companies, internal/external attendees, and unified formatting.

- [3272-call_processing_ai.json](workflows/3272-call_processing_ai.json)
  Description: This workflow automates sales call processing using AI to extract information and store it in Notion. Includes Slack alerts and handles errors to ensure data integrity.

- [3274-procesador-llamadas-venta.json](workflows/3274-procesador-llamadas-venta.json)
  Description: This workflow processes competitor, integration, and objection data extracted from sales call analysis. It updates Notion databases with structured information and creates specific entries for each category.

- [3275-automarketing-insights.json](workflows/3275-automarketing-insights.json)
  Description: This workflow automates marketing insight creation and recurring themes in Notion from sales call data. Analyzes and organizes key information in specific databases.

- [3277-water-drink-reminder.json](workflows/3277-water-drink-reminder.json)
  Description: This workflow automates a water drinking reminder system. It collects data from Google Sheets, uses OpenAI to generate personalized motivational messages, and sends notifications to Slack with interactive buttons.

- [3278-google-sheets-analysis.json](workflows/3278-google-sheets-analysis.json)
  Description: This workflow uses an AI agent to analyze and manipulate data from Google Sheets, allowing advanced queries by filtering dates and statuses, transforming complex formats into JSON, and obtaining statistics through tools like calculation and aggregation.

- [3280-trading-agent-analysis.json](workflows/3280-trading-agent-analysis.json)
  Description: This automated workflow allows a user to perform technical stock analysis via an AI agent on Telegram. It receives messages, processes text or voice, generates custom charts, and sends the analysis to the user.

- [3281-telegram-voice-to-social.json](workflows/3281-telegram-voice-to-social.json)
  Description: This workflow receives Telegram messages, analyzes them to see if they are voice or text, and transcribes voice if it is. Then it uses OpenAI and SerpAPI to generate social media optimized content with a detailed prompt for image creation.

- [3282-analisis_medios_gemini.json](workflows/3282-analisis_medios_gemini.json)
  Description: This workflow uses different methodologies to analyze media like images and PDFs using AI agents. It includes specific routes for individual and batch image analysis, use of custom prompts, conversion to base64 format, and direct calls to the Gemini API.

- [3283-sync-email-templates.json](workflows/3283-sync-email-templates.json)
  Description: This workflow synchronizes email templates between Dartagnan and Braze. It retrieves templates from Dartagnan, compares with existing ones in Braze, and updates or creates new ones as appropriate.

- [3285-mistral-ocr-parsing.json](workflows/3285-mistral-ocr-parsing.json)
  Description: Workflow that uses Mistral OCR to analyze documents and images uploaded to Google Drive. First, it loads files from Google Drive, then sends them to Mistral Cloud to get signed URLs, processes OCR with those URLs, and finally performs document or image analysis using different models (chat completions).

- [3288-follow_up_meetings.json](workflows/3288-follow_up_meetings.json)
  Description: This automated workflow monitors past sales appointments to detect if follow-up messages have been sent and suggests new available appointments to the user to schedule a new meeting if necessary.

- [3289-ko-fi-webhook-handler.json](workflows/3289-ko-fi-webhook-handler.json)
  Description: Workflow that processes Ko-fi webhooks, verifies the token, and handles donations, subscriptions, and purchase orders.

- [3290-aprendizaje_idiomas.json](workflows/3290-aprendizaje_idiomas.json)
  Description: This workflow automates flashcard creation for language learning. It uses Google Sheets to store words, translates to Chinese using Google Translate, generates phonetics and sentences with an AI agent, searches for images on Pexels, and uploads them to Google Drive.

- [3292-breach-monitor.json](workflows/3292-breach-monitor.json)
  Description: This automated workflow continuously monitors for new breaches on haveibeenpwned.com and sends alerts when detected. It stores information from the latest breaches in a cache.json file to avoid duplicate notifications.

- [3293-youtube-notificacion-videos.json](workflows/3293-youtube-notificacion-videos.json)
  Description: This workflow uses the YouTube API to search and filter videos from subscribed channels, detecting those longer than 61 seconds and sending email notifications.

- [3295-email-processing-flow.json](workflows/3295-email-processing-flow.json)
  Description: This automated workflow processes Gmail emails using a text classifier to assign messages to specific categories like Guest Post, Youtube, or Courses. Then, it sends predefined responses using HTML templates and marks emails as read, as well as adding labels and contacts in Brevo.

- [3296-shopify-to-google-spreadsheet.json](workflows/3296-shopify-to-google-spreadsheet.json)
  Description: This workflow extracts customer information from Shopify and exports it to a Google Sheets spreadsheet. It uses a loop to retrieve paginated data until no more pages are left, processing information and updating continuously.

- [3297-dropbox-watch-files.json](workflows/3297-dropbox-watch-files.json)
  Description: This workflow monitors changes in two Dropbox folders (/z_Apps/a_iphone/RecUp Memos/ and /z_Apps/auphonic/whisper) to detect new files or folders. It uses NocoDB to store file metadata, filters those not previously processed, and executes specific flows for each detected file type.

- [3298-pomodoro-bot.json](workflows/3298-pomodoro-bot.json)
  Description: This workflow manages Pomodoro work sessions with Telegram and records activities in Google Sheets. It detects commands like /start and /stop, handles work and break intervals, and records statistics.

- [3301-antispam_discord.json](workflows/3301-antispam_discord.json)
  Description: This automated workflow detects and moderates spam messages on Discord using AI to classify texts, notifies moderators, and takes action based on human decision.

- [3302-webpage-change-monitor.json](workflows/3302-webpage-change-monitor.json)
  Description: Automated workflow to detect changes on a webpage and notify via email when there is a modification. It uses a content hash for comparison and records activities in Google Sheets.

- [3303-email-pdf-classifier.json](workflows/3303-email-pdf-classifier.json)
  Description: This automated workflow uses n8n to analyze emails with PDF attachments and classify them using OpenAI. It creates folders in Google Drive by date, checks if files are invoices/receipts, and stores them there or sends them by email.

- [3305-seo-wordpress-generator.json](workflows/3305-seo-wordpress-generator.json)
  Description: This automated workflow generates SEO-optimized content for WordPress using Perplexity research and OpenAI. It includes creating titles, slugs, and metadata, developing structured HTML, and publishing to the blog.

- [3308-historias-infantiles-arabic.json](workflows/3308-historias-infantiles-arabic.json)
  Description: Workflow that automates the creation and sending of Arabic children's stories via Telegram, using OpenAI to generate content, translate, create images, and audio.

- [3312-chatbot-curriculos.json](workflows/3312-chatbot-curriculos.json)
  Description: This workflow allows creating a custom chatbot that manages resumes and sends daily reports with conversation information via Google Drive, Gemini, Pinecone, and NocoDB.

- [3315-coin_market_cap_crypto_agent.json](workflows/3315-coin_market_cap_crypto_agent.json)
  Description: Descriptive agent workflow that uses CoinMarketCap API to analyze and provide information about cryptocurrencies through an integrated natural language analysis system with memory.

- [3317-agendamiento-citas-ai.json](workflows/3317-agendamiento-citas-ai.json)
  Description: This automated workflow uses Gmail and Google Calendar to analyze emails requesting an appointment, check calendar availability, and propose free time slots using an AI agent.

- [3318-extract_text_from_pdf_image_to_csv.json](workflows/3318-extract_text_from_pdf_image_to_csv.json)
  Description: This automated workflow extracts text from PDF files and images using Vertex AI (Gemini) and converts them to CSV for storage in Google Drive.

- [3319-umami-ai-analytics.json](workflows/3319-umami-ai-analytics.json)
  Description: This workflow extracts web analytics data from Umami, processes and sends information to an AI model for weekly summaries and comparisons, saving results in Baserow.

- [3320-supabase-vector-flow.json](workflows/3320-supabase-vector-flow.json)
  Description: This workflow integrates Supabase with n8n to perform insertions, updates, and retrievals in a vector database, using OpenAI embeddings and a vector engine optimized for efficient searches.

- [3323-hr-automatizacion.json](workflows/3323-hr-automatizacion.json)
  Description: This automated workflow manages HR automation by extracting key information from CVs, analyzing with artificial intelligence, and consolidating results in a spreadsheet.

- [3325-split-test-ab.json](workflows/3325-split-test-ab.json)
  Description: This workflow implements an A/B split test to evaluate different messages in a chatbot. Upon receiving a message, it checks if the session exists and randomly assigns a prompt between two options saved in Supabase, then uses the AI agent with the selected prompt.

- [3326-telegram-ai-bot.json](workflows/3326-telegram-ai-bot.json)
  Description: This workflow processes voice and text messages in Telegram, transcribes audio to text, and uses OpenAI to respond intelligently.

- [3327-telegram-ai-bot.json](workflows/3327-telegram-ai-bot.json)
  Description: This Telegram workflow implements a bot that processes /flux commands to generate images and textual responses with NeurochainAI. Includes error handling and retry links.

- [3328-telegram-ai-bot.json](workflows/3328-telegram-ai-bot.json)
  Description: This Telegram AI Chatbot workflow manages specific commands and uses OpenAI to respond to messages in different modes such as conversation, welcome, and image generation.

- [3330-telegram-pdf-integration.json](workflows/3330-telegram-pdf-integration.json)
  Description: This workflow processes a PDF file sent via Telegram, uploads it to Pinecone to allow searches and answers based on the content.

- [3332-text-automations-shortcuts.json](workflows/3332-text-automations-shortcuts.json)
  Description: This workflow uses Apple Shortcuts to send texts to a webhook and use OpenAI to perform different tasks like translating, correcting grammar, or adjusting text length.

- [3333-Enrich_Company_Data.json](workflows/3333-Enrich_Company_Data.json)
  Description: This workflow automates business data enrichment using Google Sheets, OpenAI, and a web extraction tool. It retrieves information from a spreadsheet, uses an AI agent to analyze websites via ScrapingBee, and updates data in real-time.

- [3335-github-releases-tracker.json](workflows/3335-github-releases-tracker.json)
  Description: This workflow tracks project releases on GitHub and extracts relevant information to send formatted messages to Slack. It configures followed repositories, checks releases periodically with a timer, and uses Redis to cache IDs.

- [3336-credenciales-transfer-n8n.json](workflows/3336-credenciales-transfer-n8n.json)
  Description: Workflow to transfer credentials between n8n instances. Allows selecting a target instance and a source credential, then exports, processes, and sends the credential to the target.

- [3339-amazon_price_tracker.json](workflows/3339-amazon_price_tracker.json)
  Description: This workflow monitors product prices on Amazon using the ScrapeOps API, records changes, and sends email alerts for significant alterations.

- [3340-transcribe-bank-statements.json](workflows/3340-transcribe-bank-statements.json)
  Description: This workflow transforms a bank statement in PDF format to markdown using the Gemini Vision AI model for easy data extraction.

- [3341-audio-translation-flow.json](workflows/3341-audio-translation-flow.json)
  Description: This workflow translates text to English, generates audio in French, transcribes that audio back to text, and then converts it into an English voice file.

- [3342-web_agent_airtop.json](workflows/3342-web_agent_airtop.json)
  Description: This workflow configures a web agent that uses Airtop to interact with a browser window, including opening URLs, clicking, and querying web pages following user instructions. The agent also uses Anthropic's Claude 3.5 to process interactions.

- [3343-Indeed_Data_Scraper_Gemini.json](workflows/3343-Indeed_Data_Scraper_Gemini.json)
  Description: This workflow extracts and summarizes company data from Indeed using Bright Data and Google Gemini. It uses Airtable to store links and processes information with AI agents and chains of thought.

- [3344-scrape-trustpilot-sentiment.json](workflows/3344-scrape-trustpilot-sentiment.json)
  Description: This workflow extracts Trustpilot reviews using DeepSeek, analyzes their sentiment with OpenAI, and records them in Google Sheets.  
