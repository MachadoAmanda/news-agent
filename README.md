# AI Agent – Executive Demo Guide

This short guide explains how to set up and test the **AI Agent demo** that will be used during our talk with directors.  
The objective is to demonstrate **how an AI Agent can be created in n8n and use email as a tool**.

All required configurations are already prepared in the template file.


## Overview

In this demo you will:

1. Import a pre-configured **AI Agent workflow** into n8n.
2. Review the **agent prompt and tool configuration**.
3. Configure your **email address** in the email node.
4. Run the agent and see it **send emails as a tool action**.

The workflow template already includes:

- AI Agent configuration
- Prompt setup
- Email tool integration
- Basic automation flow

You only need to import the template and update the email address.

---

## Step 1 — Access n8n

Open the n8n instance in your browser: `https://n8npub.xptoai.com.br/`.

Log in as: 
- Username: `news@xptoai.com.br`
- Password: `Oracle!2026`


## Step 2 — Import the Workflow

Inside n8n:

1. Click **Import Workflow**
2. Import from url and add the link: `https://raw.githubusercontent.com/MachadoAmanda/news-agent/refs/heads/main/Agent%20-%20Template.json`
3. Confirm the import

*(Follow the same process illustrated in the images)*
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/161285b9-4df9-436d-9359-b5f03f49c75d" />
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/a13b0882-0a16-4b67-8890-c1fc974c4e1b" />
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/114eec79-93fa-4b12-a214-a337912e6f52" />

After importing, the workflow will appear with **all nodes already configured**.

**(Change the workflow name adding your name on it)**
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/115a9f4d-80a0-4a53-9d52-a8aa57a40959" />

## Step 3 — Configure the Email Node

Locate the **Email Node** in the workflow.
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/443a010e-9c89-4cd3-9a14-e3883a7afeab" />

Update the configuration:

- Replace the **email address** with **your own email**
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/b455abb5-3131-468f-8740-27f6620a2b9a" />

No other configuration changes are required.

## Step 4 — Review or Adjust the Agent Prompt (Optional)

The **Agent Prompt** is already configured in the template.
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/17130967-201f-450f-851e-47fa70d42768" />

However, you may adjust it if desired to:

- Change the agent behavior
- Modify the instructions
- Adapt the email style or message content

<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/676c81b8-052e-49d2-bf74-e671e95cde8b" />

This step is optional.


## Step 5 — Run the Workflow

Once the email is configured:

1. Run the workflow
2. Send a message in the chat or into the public chat page (Follow image steps)
3. Observe the agent using the **email tool to send a message**

### Step 5.1 - Opening chat node:
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/266debbe-3015-4f3d-b5be-26e62487b9da" />

### Step 5.2 - Accessing webpage chat:
<img width="800" height="441" alt="image" src="https://github.com/user-attachments/assets/b4b42dfb-212a-4bfb-bc0a-1666ba9bd62d" />

This demonstrates how **AI agents can interact with external tools inside automation workflows**.

---

## What This Demo Shows

This example illustrates how easily an **AI Agent can be integrated into business automation** using n8n:

- AI agents embedded in workflows
- Tool usage (email sending)
- Prompt-driven behavior
- Fast deployment using templates

---

## Key Takeaway

With a simple template and minimal configuration, it is possible to deploy **AI-powered agents that interact with enterprise tools**, enabling new levels of automation and productivity.
