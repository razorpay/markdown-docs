# Razorpay Markdown Docs

This repository contains the official Razorpay product documentation in Markdown format. It serves as the single source of truth for all Razorpay developer documentation, powering the [Razorpay Developer Docs](https://razorpay.com/docs) site and AI-powered tools like the [Razorpay MCP Server](https://razorpay.com/docs/mcp-server).

## Overview

`markdown-docs` is a structured collection of Markdown files covering the full range of Razorpay's products and APIs. Each document is written in Markdown with YAML frontmatter for metadata, making it easy to consume by documentation sites, AI assistants, and developer tools.

## Repository Structure

```
markdown-docs/
├── api/                  # Razorpay API reference docs
├── payments/             # Payment gateway documentation
├── orders/               # Orders API docs
├── mcp-server/           # Razorpay MCP Server documentation
├── webhooks/             # Webhooks reference
├── payroll/              # Razorpay Payroll docs
├── pos/                  # Point of Sale documentation
├── partners/             # Partner integration docs
├── engage/               # Razorpay Engage documentation
├── x/                    # RazorpayX (Business Banking) docs
├── errors/               # Error codes and handling
├── faqs.md               # Frequently Asked Questions
├── announcements/        # Product announcements
├── _manifest.json        # Auto-generated route manifest
└── _url-md-map.json      # URL to Markdown file mapping
```

## Usage

### Browse Documentation

All markdown files are publicly accessible via raw GitHub URLs:

```
https://raw.githubusercontent.com/razorpay/markdown-docs/master/<path-to-file>.md
```

### LLM / AI Integration

This repository is optimized for use with AI tools. You can use the `llms-txt.md` file to understand the full scope of available documentation:

```
https://raw.githubusercontent.com/razorpay/markdown-docs/master/llms-txt.md
```

### Razorpay MCP Server

The [Razorpay MCP Server](https://razorpay.com/docs/mcp-server) uses this repository as its documentation source to power AI-assisted payment operations in tools like Claude Desktop, Cursor, and VS Code.

## Document Format

Each Markdown document follows this structure:

```markdown
---
title: Document Title
description: A brief description of the document content.
---

# Document Title

Document content in Markdown...
```
