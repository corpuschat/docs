# Using custom domains
## Assigning a custom domain to your chatbot public page

Custom domains serve as a powerful branding tool, allowing you to seamlessly integrate your Corpus chatbot into your existing online presence. This document guides you through the process of setting up a custom domain for your Corpus public page, ensuring a branded and professional appearance for your chatbot interface.

[[info]]
Custom domains are available for customers on the [Pro](https://corpus.chat/pricing) or [Max](https://corpus.chat/pricing) plans.
[[/info]]

## Setting up a custom domain

### 1. Add your custom domain

Begin by navigating to the sharing page on your Corpus dashboard. Here you can add your chosen custom domain (e.g., `chat.yourdomain.com`) or subdomain (e.g., `yourchatbot.com`). This tells Corpus which domain you intend to use for your chatbot page.

### 2. Update DNS settings

Next, you need to point your custom domain to the Corpus servers:

- **Access your domain's DNS settings:** Log in to your domain registrar's website and locate the DNS settings section.
- **Create a CNAME record:** Add a new `CNAME` record for your domain or subdomain.
- **Set the value:** The `CNAME` record should point to `hosting.corpuschat.app`.
- **Save changes:** Ensure you save the new DNS settings.

This DNS change may take some time to propagate, typically anywhere from a few minutes to 48 hours.

### 3. Verify DNS configuration

After updating your DNS settings, return to the Corpus sharing page:

- **Click on verify dns:** Use the verify option provided by Corpus to confirm that your DNS settings are correctly pointing to the Corpus servers.
- **Confirmation:** Once verified, Corpus will acknowledge that your custom domain is connected to your chatbot page.

## Accessing your chatbot

With DNS verification complete, your chatbot page will be accessible through your custom domain. This means users can interact with your chatbot via a web address that aligns with your brand's domain, providing a cohesive user experience.

## Summary

Setting up a custom domain for your Corpus chatbot page enhances your brand's professionalism and provides a seamless user experience. By following the steps outlined above, you can ensure that your chatbot is accessible through a branded domain, fostering trust and recognition with your users. If you encounter any issues during the process, Corpus's support team is available to assist you.
