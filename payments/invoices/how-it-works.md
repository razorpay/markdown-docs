---
title: How Invoices Work
description: Create Invoices, send them to customers to receive payments and perform other actions.
---

# How Invoices Work

Given below is a complete end-to-end flow about how you can use Razorpay Invoices.

### Step 1: Create an Invoice

[Create an invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/create.md) by providing all the required details. You can set an expiry date and enable partial payments.

Save the invoice. The invoice is in `draft` status. Know more about [invoice states](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/states.md).

> **INFO**
>
> 
> **Handy Tips**
> 
> - You can [update](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/update.md), [delete](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/delete.md), or [create a duplicate](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/duplicate.md) of an invoice in `draft` status. 

> - **Invoice APIs**:
>     - [Create an invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/payments/invoices.md#create-an-invoice)
>     - [Update an invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/payments/invoices.md#update-an-invoice)
>     - [Delete an invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/payments/invoices.md#delete-an-invoice)
> 

### Step 2: Issue an Invoice

[Issue an invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/issue.md) to a customer via email and/or sms.
The customer receives a notification by email or sms with a payment link using which the customer can pay using one of the available [payment methods](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices.md#list-of-supported-payment-methods).

> **INFO**
>
> 
> **Handy Tips**
> 
> Use the [Issue an Invoice API](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/payments/invoices.md#issue-an-invoice).
> 

### Step 3: Receive Payments

Customer clicks the payment link and tries to make the payment.
- If [partial payments](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/payment-links/partial-payments.md) payments was enabled, the customer chooses the amount to be paid.
- The customer chooses the mode of payment: Pay Online or Pay via Bank Transfer

Customer makes a successful payment. The invoice is marked as `paid` or `partially paid`. You receive a notification about the payment.

> **INFO**
>
> 
> **Handy Tips**
> 
> After the payment is captured, the amount is settled to your account as per the settlement schedule. Know more about [payments](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/payments.md), [settlements](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/settlements.md), [refunds](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/refunds.md) and [disputes](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/disputes.md).
> 

### Step 4: Track Invoices and Reports

- Notifications

You receive notifications regarding activity on invoices via SMS, emails and webhook. Know more about [subscribing to Webhooks](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/subscribe-to-webhooks.md).
- Track Payments

Track payments made against the issued invoices on Dashboard. Click **Invoices** from the left menu. All the invoices are listed with their status under **Invoices**.
- Reports

Detailed insights can be gained using reports and real-time data on the Dashboard. These reports can then be used for accounting and reconciliation purposes. Know more about [reports](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/dashboard/reports.md).

### Related Information
- [Invoices](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices.md)
- [Invoices States](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/states.md)
- [Create an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/create.md)
- [Issue an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/issue.md)
- [Search an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/search.md)
- [Update an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/update.md)
- [Duplicate an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/duplicate.md)
- [Delete an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/delete.md)
- [Cancel an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/cancel.md)
- [Download and Print an Invoice](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/download-print.md)
- [Subscribe to Webhooks](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/subscribe-to-webhooks.md)
- [Invoice APIs](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/invoices/apis.md)
