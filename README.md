# AI Voice Lead Qualification System

An AI-powered lead qualification workflow that combines Voice AI, workflow automation, transcript analysis, and CRM integration.

The system uses a Retell AI voice agent to conduct qualification calls, sends call transcripts to n8n through webhooks, analyzes conversations using Gemini 2.5 Flash, and automatically updates lead records in Airtable.

## Project Overview

Many businesses lose potential customers because leads are contacted too late or sales teams spend time on unqualified prospects.

This project explores how AI can automate the lead qualification process by:

* Conducting conversations through a voice agent
* Capturing call transcripts automatically
* Evaluating qualification criteria using an LLM
* Updating CRM records without manual intervention

## Tech Stack

* Retell AI
* n8n
* Google Gemini 2.5 Flash
* Airtable
* Webhooks

## Workflow Architecture

Voice Call

↓

Retell AI Voice Agent

↓

Call Transcript

↓

Webhook (n8n)

↓

Lead Lookup (Airtable)

↓

Transcript Analysis (Gemini)

↓

Qualification Decision

↓

CRM Update

## Qualification Criteria

The AI agent evaluates whether a lead:

* Is located in Texas
* Owns their home
* Has at least $10,000 available for a solar project

Based on the conversation, the system classifies leads as:

* Qualified
* Disqualified

## Features

* AI Voice Agent
* Automated Lead Qualification
* Webhook-Based Processing
* Transcript Analysis
* Structured LLM Outputs
* Airtable CRM Integration
* Automated Status Updates

## Learning Outcomes

Through this project, I gained experience with:

* Voice AI systems
* Workflow automation
* Event-driven architectures
* Webhook integrations
* CRM automation
* Structured output parsing
* LLM-powered business workflows

## Project Status

This project was developed as a learning and portfolio project to explore AI-powered sales automation workflows.

The workflow architecture, integrations, and qualification logic have been implemented and tested as part of the learning process.

## Screenshots

Add screenshots here:

* Retell AI Agent Configuration
* n8n Workflow
* Airtable CRM Structure
* Transcript Analysis Workflow
* Qualification Logic

## Future Improvements

* End-to-end deployment with live phone numbers
* Outbound calling support
* Advanced lead scoring
* Multi-region qualification rules
* CRM integrations beyond Airtable

## Author

Built by a VIT Bhopal student exploring AI Automation, AI Agents, Workflow Design, and Business Process Automation.
