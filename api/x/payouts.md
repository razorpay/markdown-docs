---
title: RazorpayX Payouts API Documentation
heading: Payouts
description: Create, fetch and cancel Payouts using APIs. Set up webhooks for notifications.
---

# Payouts

A [payout](https://raw.githubusercontent.com/razorpay/markdown-docs/master/x/payouts.md) is a transfer of funds from your business account to a Contact's Fund Account(s). You can create and process payouts both on the RazorpayX Dashboard and via the Payouts API. Ensure to [create a contact](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/x/contacts/create.md) and add a [fund account](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/x/fund-accounts.md). 

> **SUCCESS**
>
> 
>     **What's New**
> 
>     [Idempotency Key](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/x/payout-idempotency.md) is mandatory for all payout requests starting March 15, 2025.
> 

To make payouts, you must [allowlist IPs](https://raw.githubusercontent.com/razorpay/markdown-docs/master/x/dashboard/allowlist-ip.md) and pass the [idempotency key](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/x/payout-idempotency.md).

Making payouts from [RazorpayX Lite](https://raw.githubusercontent.com/razorpay/markdown-docs/master/x/account-types/razorpayx-lite.md) account to RazorpayX Lite Customer Identifiers or Razorpay [Customer identifiers](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/smart-collect.md) is not supported.

Fork the Razorpay Postman Public Workspace and try the Payouts APIs using your [Test API Keys](https://raw.githubusercontent.com/razorpay/markdown-docs/master/x/dashboard/api-keys.md).
[](https://www.postman.com/razorpaydev/workspace/razorpay-public-workspace/folder/12492020-117c93d1-1a79-4958-9067-eb97a3459f08)

### Related Guides

[About Payouts](https://raw.githubusercontent.com/razorpay/markdown-docs/master/x/payouts.md)
[Set up Webhooks](https://raw.githubusercontent.com/razorpay/markdown-docs/master/webhooks/setup-edit-payouts.md)
[Webhooks Payloads](https://raw.githubusercontent.com/razorpay/markdown-docs/master/webhooks.md)

### Endpoints

- **post** `
/v1/payouts` - Creates a Payout to a Bank Account: 
Create a payout to a bank account.

- **post** `
/v1/payouts` - Create a Payout to a VPA: 
Creates a payout to a VPA.

- **get** `/v1/payouts?account_number=\{account number\}` - Fetch all Payouts: 
Retrieves details of all the payouts.

- **get** `/v1/payouts/:id` - Fetch a Payout with ID: 
Retrieves details of one payout via ID.

- **patch** `/v1/payouts/:id/cancel` - Cancel a Queued Payout: 
Cancels a payout in `queued` state.
