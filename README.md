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

## Step 1 — Download the Template

Download the file: `Agent template.json`

This file contains the **entire pre-configured workflow**, including:

- Agent setup
- Prompt instructions
- Email tool configuration

---

## Step 2 — Access n8n

Open the n8n instance in your browser: `https://n8npub.xptoai.com.br/`.

Log in as: 
- Username: `news@xptoai.com.br`
- Password: `Oracle!2026`


## Step 3 — Import the Workflow

Inside n8n:

1. Click **Import Workflow**
2. Upload the file **`Agent template.json`**
3. Confirm the import

*(Follow the same process illustrated in the images)*
<img width="1857" height="1023" alt="image" src="https://github.com/user-attachments/assets/217e9dc3-e66e-41e4-9ac0-d878f7a8abe1" />

<img width="1897" height="1017" alt="image" src="https://github.com/user-attachments/assets/e70c600a-db0b-4f94-867f-49c9cc566cb5" />

After importing, the workflow will appear with **all nodes already configured**.

<img width="1274" height="598" alt="image" src="https://github.com/user-attachments/assets/7c8d8cc6-19ef-48e6-840d-1baa73138ee7" />

## Step 4 — Configure the Email Node

Locate the **Email Node** in the workflow.
<img width="1907" height="1027" alt="image" src="https://github.com/user-attachments/assets/443a010e-9c89-4cd3-9a14-e3883a7afeab" />

Update the configuration:

- Replace the **email address** with **your own email**
<img width="1882" height="1012" alt="image" src="https://github.com/user-attachments/assets/b455abb5-3131-468f-8740-27f6620a2b9a" />

No other configuration changes are required.

## Step 5 — Review or Adjust the Agent Prompt (Optional)

The **Agent Prompt** is already configured in the template.
<img width="1903" height="1013" alt="image" src="https://github.com/user-attachments/assets/17130967-201f-450f-851e-47fa70d42768" />

However, you may adjust it if desired to:

- Change the agent behavior
- Modify the instructions
- Adapt the email style or message content

<img width="1885" height="1021" alt="image" src="https://github.com/user-attachments/assets/676c81b8-052e-49d2-bf74-e671e95cde8b" />

This step is optional.


## Step 6 — Run the Workflow

Once the email is configured:

1. Run the workflow
2. Send a message in the chat or into the public chat page (Follow image steps)
3. Observe the agent using the **email tool to send a message**

### Step 1 - Opening chat node:
<img width="1903" height="1012" alt="image" src="https://github.com/user-attachments/assets/266debbe-3015-4f3d-b5be-26e62487b9da" />
### Step 2 - Accessing webpage chat:
<img width="1886" height="1017" alt="image" src="https://github.com/user-attachments/assets/b4b42dfb-212a-4bfb-bc0a-1666ba9bd62d" />

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
