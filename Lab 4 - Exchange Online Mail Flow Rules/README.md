# Lab 4 – Exchange Online Mail Flow Rules

## Overview

In this lab, I configured and managed a mail flow rule in Exchange Online using the Exchange Admin Center.

The lab demonstrates how Microsoft 365 Administrators use mail flow rules to automatically process emails based on specific conditions and apply actions to meet organizational requirements.

---

# Objectives

The objectives of this lab were:

- Create an Exchange Online mail flow rule
- Configure conditions for email processing
- Apply automated actions to email messages
- Understand Exchange Online transport rules
- Learn how organizations use mail flow rules for compliance and email management

---

# Scenario

The organization wants to add a confidentiality disclaimer to emails sent outside the organization.

As the Microsoft 365 Administrator, the task was to create a mail flow rule that automatically appends a disclaimer to external emails.

---

# Part 1 – Create Mail Flow Rule

## Rule Details

**Rule Name:**

External Email Disclaimer

**Purpose:**

Automatically add a confidentiality disclaimer to messages sent outside the organization.

---

# Mail Flow Rule Configuration

## Condition

The rule was configured to apply when:

- Recipient is located outside the organization

This ensures the disclaimer is added only to external emails.

---

## Action

Configured the rule action:

- Append a disclaimer to the message

Disclaimer added:

> This email is confidential and intended only for the recipient. If you have received this email in error, please notify the sender and delete it immediately.

---

## Fallback Action

Configured fallback action:

**Wrap**

The Wrap option ensures the disclaimer is still delivered if Exchange Online cannot directly modify the original message.

---

# Mail Flow Rule Purpose

Exchange Online mail flow rules are commonly used by administrators to:

- Add legal disclaimers
- Block or redirect messages
- Apply security controls
- Enforce organizational email policies
- Manage email compliance requirements

---

# Screenshots

## Mail Flow Rule Creation

Created a new Exchange Online mail flow rule.

![Mail Flow Rule Creation](Lab4_Mail_Flow_Rule_Creation.png)

---

## Mail Flow Rule Action

Configured the disclaimer action and fallback behavior.

![Mail Flow Rule Action](Lab4_Mail_Flow_Rule_Action.png)

---

## Mail Flow Rule Overview

Reviewed the completed mail flow rule configuration.

![Mail Flow Rule Overview](Lab4_Mail_Flow_Rule_Overview.png)

---

# Skills Demonstrated

- Exchange Online Administration
- Exchange Admin Center
- Mail Flow Rules
- Transport Rules
- Email Compliance Management
- Microsoft 365 Administration

---

# Lab Outcome

Successfully created and configured an Exchange Online mail flow rule to automatically append a disclaimer to external emails, demonstrating email policy management and Exchange Online administration skills.
