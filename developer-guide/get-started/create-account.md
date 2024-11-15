---
title: Creating an Account
sidebar: doc_sidebar
permalink: create-account.html
toc: false
---

# Full-Stack Implementations
Members are the users who conduct the studies. Once members have their Samsung Health Stack account, they can access all backend functionality via the web portal or otherwise.

## Web Portal
To create your account directly, independent of any study:

1. Refer to [Launch Web Portal and Create Account](../installation/install-portal.md#iii-launch-web-portal-and-create-account) in the web portal installation instructions.

To invite a team member to create their account (as part of joining a study):

1. Refer to [Inviting Members and Assigning Roles](../study-management/managing-team-members.md#inviting-team-members-and-assigning-roles) in the web portal user guide.

## API Endpoints
To create your account  directly, separate from any study:

1. Refer to [Create Initial Account](../installation/install-backend.md#xv-create-initial-account) in the backend system installation instructions.

To invite a team member to create their account (as part of joining a study):

1. Refer to `/account-service/invitations` in [Account Service API Endpoints](../../api-reference/account-service-api-endpoints.md) in the API reference.

# SDK-Only Implementations
Because Samsung Health Stack accounts are part of the Samsung Health Stack's backend system and do not interface with the participant app, creating Samsung Health Stack accounts is not required for SDK-only implementations.