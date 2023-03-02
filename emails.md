---
title: Emails
description: Set up emails
---

# Emails

In this step, we'll set up emails.

## NodeMailer

Neorepo uses [NodeMailer](https://nodemailer.com/about/) to send emails. NodeMailer is a module for Node.js applications to allow easy as cake email sending. The project got started back in 2010 when there was no sane option to send email messages, today it is the solution most Node.js users turn to by default.

## SMTP Configuration

NodeMailer uses SMTP to send emails. SMTP is a protocol for sending emails. It's used by email servers to send and receive emails. It's also used by email clients to send emails.

### Add your environment variables

1. Open the Vercel project you created in the previous step
2. Click the "Environment Variables" tab
3. Add the following environment variables (replace example values with your own)):

|`EMAIL_SMTP_HOST` |`smtp.mailgun.org` |
|`EMAIL_SMTP_PORT`|`587`|
|`EMAIL_SMTP_USER`|`postmaster@mg.neorepo.com`|
|`EMAIL_SMTP_PASSWORD`|`password`|

## React Email

Neorepo uses [React Email](https://react.email) to generate emails. React Email is a library for generating HTML emails using React. It's designed to be used with NodeMailer.

You can use React Email to leverage the power of React to generate emails.
