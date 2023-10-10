
![magento-feedbackcompany-hyva](https://github.com/magmodules/magento2-feedbackcompany-hyva-dev/assets/24823946/4ef0a776-adb4-478c-b445-0091e25d6639)

# The Feedback Company Hyvä Compatibility plugin

The Feedback Company plugin for Magento is a powerful integration that seamlessly connects the renowned review platform, The Feedback Company, with Magento. This plugin offers comprehensive functionality to enhance your online store's reputation management and streamline the customer feedback process. With its compatibility with the Hyva theme, the plugin ensures a smooth and seamless user experience while incorporating the robust features of The Feedback Company platform.


The Feedback Company plugin Hyvä Compatibility plugin for the Magento Hyva theme has the following requirements:
- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules The Feedback Company Reviews](https://www.magmodules.eu/magento2-feedbackcompany-reviews.html)    


<img width="1054" alt="feedbackcompany-magento-plugin" src="https://github.com/magmodules/magento2-feedbackcompany-hyva-dev/assets/24823946/08619509-0bdb-45f3-bc01-b0c36e4492d2">



## About The Feedback Company Plugin

The Feedback Company plugin for Magento is a robust integration that seamlessly connects your Magento store with the renowned review platform, The Feedback Company. This plugin offers a comprehensive set of features to enhance your online store's reputation management and streamline the customer feedback process.

With the Feedback Company plugin, you can effortlessly integrate the powerful review platform into your Magento store while ensuring compatibility with the Hyva theme. This ensures a consistent and visually appealing user experience throughout your website.

The plugin empowers you to effectively manage your online store's reputation by collecting and showcasing customer reviews, ratings, and testimonials. By harnessing the influence of social proof, you can build trust with potential customers and enhance your brand's reputation.

The Feedback Company plugin provides essential tools for review management, allowing you to moderate and manage reviews within your Magento admin panel. You have full control over the display of reviews on your website, ensuring that only relevant and valuable feedback is visible to your customers.

Additionally, the Feedback Company plugin offers advanced features such as automatic review requests, email notifications, customizable review widgets, and rich snippet integration for improved search engine optimization (SEO). These features enable you to actively engage with your customers, gather valuable feedback, and enhance the overall shopping experience on your Magento store.

In conclusion, the Feedback Company plugin for Magento, with its compatibility with the Hyva theme, provides a powerful solution for seamlessly integrating the Feedback Company review platform into your online store. It empowers you to effectively manage your store's reputation, collect customer feedback, and foster trust with your audience.

## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-hyva-feedbackcompany
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaFeedbackCompanySR
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## The Feedback Company Magento plugin features

- Seamless integration
- Review collection automation
- Customizable review widgets
- Rich snippet integration
- Hyvä Compatibility
- Host it all on your platform


## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.



## Checkout our other Hyva Plugins!

[- Magento 2 Hyvä Shopreview](#) 
 
[- Magento 2 Hyvä Product Review Reminder](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Checkout](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Paazl](#) 
