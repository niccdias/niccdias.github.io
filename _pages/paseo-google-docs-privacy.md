---
layout: page
permalink: /paseo-google-docs/privacy/
title: Paseo Google Docs privacy policy
description: How this personal Google Docs connection handles data.
nav: false
---

Last updated: October 24, 2026.

This policy covers [Paseo Google Docs](/paseo-google-docs/), a personal connection maintained by Nic Dias for local Paseo agents working with his own Google account.

## Data accessed and purpose

The connection accesses Google account identity information, such as the signed-in account's name and email address, to identify the connected account. For requested document tasks, it can access file names and metadata, document contents, and comments and replies.

The Google Docs permission allows reading, creating, and editing documents. The Google Drive permission is broad: it can cover files across the connected Drive, rather than only files created by this connection. It supports finding existing documents and reading or managing their comments. Agents use this access to carry out the document tasks I request.

## Processing and sharing

The Google Workspace CLI runs on my computer and communicates with Google's APIs. Relevant document content, comments, metadata, and tool results may become part of the agent conversation and be sent to the selected AI provider, such as OpenAI or Anthropic, to complete a requested task. That provider processes the information under the terms, privacy policy, and data controls of the account being used.

This connection does not sell Google user data or use it for advertising. Its use and transfer of information received from Google APIs are subject to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Storage and retention

OAuth credentials are stored privately on my computer. The CLI encrypts the saved authorization credentials using an operating-system keyring. These website pages do not receive or store OAuth credentials or document contents.

Documents and comments remain in Google Drive until changed or deleted there. Local task files, Paseo or agent conversation history, and AI-provider records may also retain content used during a task. Their retention and deletion depend on the applicable local files, application controls, and provider account settings; revoking Google access does not automatically remove those copies.

## Revoking access and deleting data

Google access can be revoked through [Google Account connections](https://myaccount.google.com/connections). Saved local authorization credentials can also be removed from the computer. To delete task content, separately remove the relevant local files or conversations and use the selected provider's deletion controls. Deleting the connection does not delete the original Google documents or their comments.

For questions about this connection or requests to remove locally retained task data, contact [niccdias@ps.au.dk](mailto:niccdias@ps.au.dk).

## These website pages

The informational pages are hosted by GitHub Pages. GitHub may process website request information under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). These pages contain no sign-in form and add no analytics or tracking code.
