# OwnPlan Privacy Policy

**Last Updated: May 09, 2025**

## Introduction

OwnPlan ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and share information when you use our OwnPlan mobile application (the "App").

We've designed OwnPlan with privacy in mind, following a local-first architecture that keeps your data on your device whenever possible. This policy is designed to help you understand exactly what information we collect and how it's used.

## Information We Collect

### Information You Provide

- **Task Data**: Tasks, subtasks, due dates, priorities, and other task-related information you create within the app
- **App Preferences**: Settings and preferences you configure within the app
- **Subscription Information**: If you purchase a subscription, transaction information is processed by Apple (for iOS)

### Information Collected Automatically

- **Usage Data**: We collect limited usage data about how you interact with the app's AI features, specifically:
  - Count of AI subtask generations (to enforce free tier limits)
  - Acceptance/rejection of AI-generated subtasks (to improve AI quality)
  
- **Device Information**: Basic device information required for the app to function, such as device type and operating system version

### Information We Do NOT Collect

- We do NOT collect personal identifiers like name, email, or phone number
- We do NOT collect your location data
- We do NOT collect your contacts or access other apps on your device
- We do NOT track your browsing history or activities outside our app

## How We Use Information

We use the information we collect to:

- **Provide the Service**: Deliver the core functionality of the app, including task management and AI-powered subtask generation
- **Enforce Usage Limits**: Track usage of AI features to enforce free tier limits
- **Improve AI Features**: Use feedback on accepted/rejected AI suggestions to improve the quality of future suggestions
- **Manage Subscriptions**: Process and verify subscription status through Apple's payment system
- **Improve the App**: Understand how users interact with the app to improve its features and usability

## Data Transmission and Third-Party Services

### Data Transmitted Off-Device

According to Apple's definition, "collect" refers to transmitting data off the device in a way that allows you and/or your third-party partners to access it for a period longer than necessary to service the transmitted request in real time.

Based on this definition, OwnPlan **does collect** the following data:

1. **Subscription Information**: When you purchase a subscription, transaction data is processed by RevenueCat (our subscription management provider) and Apple. This includes transaction identifiers and subscription status, but does not include personal financial information like credit card details.

2. **AI Feature Usage**: When you use the AI subtask generation feature, your task title and description are sent to our secure Cloudflare proxy, which forwards the request to AI providers. This data is used only to generate subtask suggestions and is not stored beyond the time needed to process your request.

### Third-Party Services

- **RevenueCat**: Manages subscription processing and verification. See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy) for more information.
- **Cloudflare**: Acts as a secure proxy for AI API calls. See [Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/) for more information.
- **AI Providers**: We use various AI providers (such as Google's Gemini and DeepSeek) through our Cloudflare proxy to generate subtask suggestions. These providers only receive the specific task information needed to generate suggestions and do not receive any personal identifiers.

## Data Storage and Security

- **Local Storage**: Most of your data, including tasks, subtasks, and app preferences, is stored locally on your device using secure storage methods.
- **Encryption**: Data transmitted to our servers is encrypted using industry-standard protocols.
- **API Security**: Our Cloudflare Worker implementation securely manages API keys and provides a unified interface for AI services without exposing sensitive credentials.

## Your Rights and Choices

- **Access and Control**: All your task data is stored locally on your device, giving you complete control over your information.
- **Subscription Management**: You can manage your subscription through your Apple App Store account settings.
- **Delete Your Data**: You can delete all app data by uninstalling the app or using the app's data clearing function in settings.

## Children's Privacy

Our App is not directed to children under the age of 13, and we do not knowingly collect personal information from children under 13. If we learn that we have collected personal information from a child under 13, we will promptly delete that information.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:

- Email: [ownplanai@gmail.com](mailto:ownplanai@gmail.com)

## Legal Compliance

This Privacy Policy complies with applicable privacy laws, including the California Consumer Privacy Act (CCPA) and the European General Data Protection Regulation (GDPR) where applicable.
