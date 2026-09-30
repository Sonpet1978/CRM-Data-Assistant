# CRM Data Assistant

### AI Developer Toolkit for Microsoft Dynamics 365 & Dataverse

**Turn natural-language requirements into CRM-aware developer assets using your actual metadata.**

CRM Data Assistant is a Windows desktop toolkit built for Microsoft Dynamics 365 / Dataverse developers, consultants, and technical teams. It combines AI with CRM metadata so generated output can reflect the entities, fields, and relationships in your environment.

> **Private Beta — v1.0.0**  
> Source code and the beta installer are not publicly distributed.

## What you can do

| Tool | What it helps you do |
| --- | --- |
| **Metadata Explorer** | Browse CRM entities, fields, relationships, and option sets. |
| **Ask Metadata** | Ask questions about the loaded CRM metadata. |
| **FetchXML Studio** | Generate FetchXML from natural-language requirements and CRM metadata. |
| **Generate SQL** | Create SQL Server queries for CRM-oriented development tasks. |
| **Generate CRM Plugin** | Configure the Dynamics pipeline and generate C# plugin code from business requirements. |
| **JavaScript Ribbon** | Generate JavaScript for Dynamics 365 command bar / ribbon scenarios. |
| **Generate Test Cases** | Create functional and technical test cases. |
| **Compare Metadata** | Compare imported CRM metadata snapshots. |
| **Where Used** | Find where an entity or field is referenced. |
| **History / Output / Logs** | Review generated work, files, and diagnostics. |

## Why CRM Data Assistant?

Generic AI coding tools do not automatically know your CRM schema.

CRM Data Assistant is designed around a different workflow:

**Load CRM metadata → describe the requirement → generate CRM-aware output → review and test.**

The goal is to reduce repetitive Dynamics 365 development work while keeping the developer in control of the final implementation.

## Example workflows

**Natural language → FetchXML**

> Return active accounts created in the last 30 days. Include account name and account number. Sort by created date descending.

**Business requirement → CRM plugin**

> Create a plugin for Account. When the account name changes, validate that the new name is not empty. Use tracing and prevent recursive execution.

**Natural language → SQL**

> Generate a SQL query that returns active accounts created in the last 30 days, including account name, account number, created date and primary contact.

## Private Beta

CRM Data Assistant is currently being prepared for a **private beta**.

The beta is intended for evaluation and testing by Dynamics 365 / Dataverse developers and technical professionals. Access will be provided to approved beta participants rather than through a public installer download.

**Join Private Beta:** registration link coming soon.

## Beta requirements

- Windows 64-bit
- Access to a supported CRM metadata SQL source
- Your own OpenAI API key (BYOK)
- Internet access for AI-powered features

A ChatGPT subscription is not required. The current beta is designed to use the participant's own OpenAI API key.

## Safety & responsible use

CRM Data Assistant is a development-assistance tool. AI-generated SQL, FetchXML, C#, JavaScript, data-fix instructions, and other generated output should be reviewed and tested by a qualified person before use, especially before changes to production systems.

Do not include API keys, passwords, connection credentials, customer data, or other secrets in public issues, screenshots, or feedback.

## Source code

CRM Data Assistant is **not an open-source project**. This public repository is the product showcase and documentation home for the project.

The application source code and private-beta installer are maintained separately and are not published in this repository.

## Built with

Microsoft Dynamics 365 · Dataverse · C# · .NET · SQL Server · JavaScript · OpenAI API

## For Dynamics 365 teams

CRM Data Assistant is being built for developers and teams working with complex Dynamics 365 environments.

Custom Dynamics 365 development and integration work is also available, including:

**C# Plugins · Dataverse · FetchXML · SQL · JavaScript · CRM Integrations · Automation · Developer Tools**

## Roadmap for this repository

- Add product screenshots and demo
- Publish Getting Started documentation
- Add Private Beta FAQ
- Add beta registration link
- Add feedback / issue templates

---

**CRM Data Assistant v1.0.0 Beta**  
© 2026 CRM Data Assistant. All rights reserved.
