# Overview

## Introduction to the Bootcamp

This bootcamp focuses on a high-impact use case for Retail Banking (FinServ): 

Proactive Debt Collection and Contention Resolution. 

We will see how streamlining debt recovery can be achieved while enhancing customer experience. The scenario centers on a proactive journey where the bank identifies customers with upcoming debt maturity dates and initiates contact through automated channels.

The strategy is divided into two phases:

1. Proactive Outbound & AI Agent Automation: Using AI to handle routine payments and inquiries securely.
2. Contention Escalation & AI-Assisted Resolution: Transitioning to human experts when a customer disputes a transaction, supported by real-time AI guidance to resolve fraud concerns and lock compromised cards.

Participants will explore a "frictionless" journey where customers are notified of upcoming debt maturity dates and provided with instant, secure payment options. The bootcamp also covers complex "contention" scenarios, where AI-assisted human agents step in to resolve disputes, lock compromised cards, and ensure regulatory compliance.

## Learning Objectives :open_book:

Participants will gain hands-on experience in the following areas:

- Proactive Engagement: Configuring the Native Campaign Manager to trigger outbound voice calls based on database maturity dates.
- AI-Driven Automation: Building AI Agent flows that can authenticate users, query debt databases, and process payments via API.
- Frictionless Payments: Integrating with NovaPay to generate unique payment URLs delivered via SMS or Email.
- Contextual Escalation: Implementing seamless handovers from AI to Human Agents, ensuring all context (VA Summary) is preserved.
- Agent Empowerment: Utilizing RT Assist (Real-Time Assist) to guide agents through complex compliance steps, such as card locking and address verification.
- Operational Efficiency: Automating post-call work using AI-generated Wrap-Up summaries.

## Bootcamp Structure: Labs

The bootcamp is organized into four core labs that follow the lifecycle of the debt collection use case:

### Lab 1: Proactive Outbound Reach (Campaign Manager)
Configure the Native Campaign Manager to trigger calls based on debt maturity dates and manage retry logic.
### Lab 2: Automated Customer Engagement (AI Agent)
Build an AI Agent flow that integrates with the Customer Debt DB and NovaPay API to handle payments and inquiries independently.
### Lab 3: Value of the Human Touch (Escalation)
Design the escalation path to a specialized "Financial Contention" queue, ensuring the agent receives the full Virtual Assistant (VA) summary.
### Lab 4: AI Assisted Human (RT Assist)
Enable RT Assist to provide live guidance, automate card-locking in the backend, and generate automatic call wrap-ups.

## Getting Started: Partner Tenant Pre-requisites

To participate in the labs, ensure you have access to the following resources:

- Your Partner tenant (Gold Tenant or NFR Demo/Lab)
- Your <a href="https://admin.webex.com/login" target="_blank">Control Hub portal</a>
- Your Campaign Management portal

Furthermore, you will need the following features enabled in your tenant: 
- AI Agent
- AI Assistant
- Cisco Campaign Manager

For the purpose of the use case, additional tools are required throughout the labs: 

1. Airtable: you will use Airtable to generate customer data that simulates a customer CRM or DB
2. Novapay Payment Service: you will get access to a Cisco Mock Payment service for the purpose of the Bootcamp. You will find instructions on how to replicate this Mock payment service for your demos, although this will not be part of the Bootcamp content.

## Disclaimer

- The use case and the data used in this Bootcamp are fiction and do not correspond to any real customer or user.
- The availability of the Novapay Payment Service is guaranteed for the duration of the Bootcamp. Usagefor demos outside the purpose of the Bootcamp labs is under the partner responsibility and Cisco does not guarantee a continuous maintenance of the service. 
- Although the lab design and configuration examples could be used as a reference, for design related questions please contact your representative at Cisco, or a Cisco partner.


