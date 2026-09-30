# Getting Started — CRM Data Assistant

CRM Data Assistant v1.0.0 Beta is a Windows x64 developer toolkit for Microsoft Dynamics 365 / Dataverse.

## Before you start

You will need:

- Windows 64-bit
- Access to your organization's CRM metadata SQL source
- Your own OpenAI API key
- Internet access for AI-powered features

A ChatGPT subscription is not required. The OpenAI API key is stored encrypted locally for the current Windows user.

## Installation

Private-beta participants receive the installer directly after approval.

Run `CRMDataAssistant-Setup-1.0.0-Beta.exe` and follow the installation wizard.

The private beta may show a Windows security warning because the installer may not yet be code-signed.

## First-run setup

1. **AI Connection** — enter your OpenAI API key, choose the model, test the connection, and save.
2. **CRM Connection** — configure the CRM metadata SQL connection, test the connection, and save.
3. When both connections are ready, select **Start CRM Data Assistant**.

## What to try

- Metadata Explorer
- Ask Metadata
- Generate SQL
- FetchXML Studio
- Generate CRM Plugin
- JavaScript Ribbon
- Generate Test Cases
- Compare Metadata
- Where Used
- History / Output / Logs

## Important

Review and test all generated SQL, FetchXML, C#, JavaScript, data-fix instructions, and other generated output before using it in production.

Never include API keys, passwords, connection credentials, customer data, or other secrets in screenshots, public issues, or beta feedback.
