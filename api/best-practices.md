---
title: Razorpay APIs | Best Practices
heading: Best Practices
description: Find the best practices to follow while working with Razorpay APIs.
---

# Best Practices

Follow these best practices while working with APIs.

- **Do not share your API Key secret with anyone or on any public platforms.** This can pose security threats for your Razorpay account.
- While sending API requests to Razorpay servers, it is recommended to honour the TTL of the entries and not cache the DNS aggressively at your end. This is applicable when you are not using Razorpay SDKs.
- If you are using our SDKs, our SDKs can handle DNS caching and honour the TTLs that are set in the records.

> **SUCCESS**
>
> 
> **What's New**
> 
> Razorpay has added support for zero decimal currencies, such as JPY, and three decimal currencies, such as KWD, BHD, and OMR, allowing businesses to accept international payments in these currencies. Know more about [Currency Conversion](https://raw.githubusercontent.com/razorpay/markdown-docs/master/payments/international-payments/currency-conversion.md) (May 2024).
> 

### Related Information
- [Understand Razorpay APIs](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/understand.md)
- [API Authentication](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/authentication.md)
- [Sandbox Setup](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/sandbox-setup.md)
- [Errors](https://raw.githubusercontent.com/razorpay/markdown-docs/master/errors.md)
- [Glossary](https://raw.githubusercontent.com/razorpay/markdown-docs/master/api/glossary.md)
