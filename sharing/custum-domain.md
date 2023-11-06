---
title: Custom domains
description: Assigning a Custom Domain to Your Corpus Public Page
---

# Custom domains
## Assigning a Custom Domain to Your Corpus Public Page

## Overview

Custom domains serve as a powerful branding tool, allowing you to seamlessly integrate your Corpus chatbot into your existing online presence. This document guides you through the process of setting up a custom domain for your Corpus public page, ensuring a branded and professional appearance for your chatbot interface.

## Prerequisites

Before you begin, ensure you meet the following requirements:

- **Subscription Plan:** You must have a Pro or Max plan with Corpus to use a custom domain.
- **Domain Ownership:** You need to own a domain or have permissions to modify its DNS records.

## Steps to Assign a Custom Domain

### 1. Add Your Custom Domain

Begin by navigating to the sharing page on your Corpus dashboard. Here you can add your chosen custom domain (e.g., `chat.yourdomain.com`) or subdomain (e.g., `yourchatbot.com`). This tells Corpus which domain you intend to use for your chatbot page.

### 2. Update DNS Settings

Next, you need to point your custom domain to the Corpus servers:

- **Access your Domain's DNS Settings:** Log in to your domain registrar's website and locate the DNS settings section.
- **Create a CNAME Record:** Add a new CNAME record for your domain or subdomain.
- **Set the Value:** The CNAME record should point to `hosting.corpuschat.app`.
- **Save Changes:** Ensure you save the new DNS settings.

This DNS change may take some time to propagate, typically anywhere from a few minutes to 48 hours.

### 3. Verify DNS Configuration

After updating your DNS settings, return to the Corpus sharing page:

- **Click on Verify DNS:** Use the verify option provided by Corpus to confirm that your DNS settings are correctly pointing to the Corpus servers.
- **Confirmation:** Once verified, Corpus will acknowledge that your custom domain is connected to your chatbot page.

## Accessing Your Chatbot

With DNS verification complete, your chatbot page will be accessible through your custom domain. This means users can interact with your chatbot via a web address that aligns with your brand's domain, providing a cohesive user experience.

## Conclusion

Setting up a custom domain for your Corpus chatbot page enhances your brand's professionalism and provides a seamless user experience. By following the steps outlined above, you can ensure that your chatbot is accessible through a branded domain, fostering trust and recognition with your users. If you encounter any issues during the process, Corpus's support team is available to assist you.
