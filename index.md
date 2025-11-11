# Privacy Policy for Scrolling Announcement Bar PRO

**Last Updated:** November 11, 2025

**Developer:** Devloop Labs  
**Contact Email:** labsatdevloop@gmail.com  
**Address:** 468, 3rd Main Road, Saraswathi Nagar South, Neelankarai 600115, Tamil Nadu, India

---

## Introduction

This Privacy Policy describes how Scrolling Announcement Bar PRO ("we", "us", "our", or "the App") collects, uses, stores, and protects information when you install or use our application on your Shopify store. We are committed to protecting your privacy and handling your data transparently and securely.

By installing or using Scrolling Announcement Bar PRO, you agree to the collection and use of information in accordance with this Privacy Policy.

---

## 1. Information We Collect

### 1.1 Information Collected Automatically from Shopify

When you install our App, we automatically collect the following information through Shopify's OAuth authentication:

- **Shop domain** (e.g., yourstore.myshopify.com)
- **Shop owner email address** (for billing and critical notifications)
- **OAuth access token** (securely encrypted and stored for API authentication)
- **Session information** (session ID, expiration time, user ID for online sessions)

### 1.2 Billing Information

Subscription and billing data is managed entirely by Shopify through their Billing API:

- Current subscription plan (Free, Growth, or Advanced)
- Subscription status and billing cycle
- Payment processing is handled exclusively by Shopify - we never see or store payment card information

### 1.3 Information We Do NOT Collect

**Important:** Scrolling Announcement Bar PRO does NOT collect, access, or store:

- ❌ Customer personal information (names, email addresses, phone numbers, addresses)
- ❌ Customer order information or purchase history
- ❌ Customer payment or financial information
- ❌ Product catalog data or inventory information
- ❌ Customer browsing behavior or analytics
- ❌ IP addresses or device information from your customers
- ❌ Click tracking or interaction data from announcement bars
- ❌ Any cookies on your customers' browsers

### 1.4 Announcement Bar Content

The announcement bars you create (text, links, design settings) are stored as part of your Shopify theme configuration, not in our database. These are managed by Shopify's theme system and remain within your Shopify store.

---

## 2. How We Use Your Information

We use the collected information solely for the following purposes:

### 2.1 App Functionality

- **Authentication:** Verifying your store's identity and maintaining secure access to your Shopify admin
- **API Communication:** Enabling the App to integrate with your store's theme system
- **Session Management:** Maintaining your logged-in state while using the App

### 2.2 Billing and Subscription Management

- Processing subscription upgrades, downgrades, and cancellations through Shopify's Billing API
- Sending billing-related notifications (handled by Shopify)

### 2.3 Service Improvement

- Identifying and fixing technical issues
- Understanding app performance to improve functionality
- Note: We do not currently use analytics tools, but may add privacy-friendly analytics in the future with updated disclosures

### 2.4 Legal Compliance

- Complying with applicable laws and regulations
- Responding to valid legal requests
- Protecting our rights and preventing misuse

### 2.5 What We Do NOT Do With Your Data

- ❌ Sell, rent, or trade your information to third parties
- ❌ Use your data for advertising or marketing purposes
- ❌ Share your data with third parties except as described in this policy
- ❌ Track or profile your customers in any way

---

## 3. Data Sharing and Disclosure

### 3.1 No Third-Party Sharing

We do not share your information with any third-party services, analytics providers, or advertising platforms. Your data stays within the Shopify ecosystem and our secure database.

### 3.2 Hosting and Infrastructure

Your data is stored on secure servers provided by our hosting infrastructure:

- **Database:** PostgreSQL (in production) or SQLite (in development)
- **Hosting Options:** Shopify-managed hosting, Heroku, Railway, or similar Shopify-approved platforms
- **Location:** Servers may be located in the United States or other regions
- **Security:** All data is transmitted over encrypted HTTPS connections and stored with industry-standard encryption

### 3.3 Shopify Platform

As a Shopify app, we necessarily share authentication data with Shopify to enable core functionality. This includes:

- OAuth tokens for API authentication
- Subscription status for billing management
- This data sharing is essential for the App to function and is governed by Shopify's own privacy policies

### 3.4 Legal Requirements

We may disclose your information if required by law or in response to:

- Valid court orders, subpoenas, or legal processes
- Requests from government or regulatory authorities
- Situations involving potential safety threats or fraud prevention
- Enforcement of our Terms of Service or protection of our legal rights

### 3.5 Business Transfers

In the event of a merger, acquisition, or sale of assets, your information may be transferred to the successor entity. We will notify you via email at least 30 days before any such transfer occurs.

---

## 4. Data Storage, Security, and Retention

### 4.1 How We Store Your Data

- **Database:** Secure PostgreSQL or SQLite database with encrypted connections
- **Access Tokens:** OAuth tokens are encrypted and never displayed in plain text
- **Session Data:** Stored securely with time-based expiration
- **Transport Security:** All data transmission uses HTTPS/TLS encryption

### 4.2 Security Measures

We implement the following security practices:

- **Encryption:** Data encrypted in transit (TLS/HTTPS) and at rest
- **Authentication:** Shopify's OAuth 2.0 protocol for secure authentication
- **Access Control:** Limited access to data, following principle of least privilege
- **Session Management:** Automatic session expiration and renewal
- **Secure Development:** Following Shopify's app security best practices
- **Regular Updates:** Keeping dependencies and security patches current

### 4.3 Data Retention

**While App is Installed:**
- Session data is retained to maintain your authenticated connection
- Data remains stored as long as the App is active on your store

**After App Uninstallation:**
- All session data is automatically deleted within **48 hours** of uninstalling the App
- Shopify triggers a webhook notification that initiates our data deletion process
- Once deleted, data cannot be recovered

**Database Backups:**
- Hosting provider may maintain automatic backups for 7-30 days depending on platform
- Backup data is subject to the same security and encryption standards
- Backups are automatically deleted after the retention period expires

### 4.4 Your Control Over Data

You can permanently delete all your data by:
1. Uninstalling the App from your Shopify admin
2. Your data will be automatically deleted within 48 hours
3. Emailing us at labsatdevloop@gmail.com to confirm deletion

---

## 5. GDPR and Privacy Rights Compliance

### 5.1 Mandatory Shopify GDPR Webhooks

Our App implements Shopify's three mandatory GDPR compliance webhooks:

**customers/data_request:** When a customer requests their data
- **Our Response:** We return confirmation that no customer data is stored by our App

**customers/redact:** When a customer requests data deletion
- **Our Response:** We confirm no customer data exists to delete

**shop/redact:** When you uninstall the App (triggered after 48 hours)
- **Our Action:** We permanently delete all session data and shop information from our database

### 5.2 Your Rights Under GDPR (For EU/UK Merchants)

If you are located in the European Economic Area, United Kingdom, or Switzerland, you have the following rights:

**Right to Access:** Request a copy of the personal data we hold about you

**Right to Rectification:** Request correction of inaccurate data

**Right to Erasure:** Request deletion of your data (fulfilled by uninstalling the App)

**Right to Restriction:** Request limitation of how we process your data

**Right to Data Portability:** Receive your data in a structured, machine-readable format

**Right to Object:** Object to processing of your data

**Right to Withdraw Consent:** Withdraw consent at any time (by uninstalling the App)

### 5.3 Legal Basis for Processing (GDPR)

We process your data based on:

- **Contract Performance:** Providing the App services as agreed in our Terms of Service
- **Legitimate Interests:** Improving app functionality, security, and user experience
- **Legal Obligations:** Complying with applicable laws and regulations

### 5.4 International Data Transfers

If you are located outside the hosting region (typically United States):

- Your data may be transferred to and processed in countries with different data protection laws
- We ensure appropriate safeguards through Standard Contractual Clauses (SCCs) approved by the European Commission
- All transfers comply with GDPR requirements for international data transfers

---

## 6. California Privacy Rights (CCPA/CPRA)

For California residents, you have the right to:

**Right to Know:** What personal information we collect and how we use it (detailed in Section 1)

**Right to Delete:** Request deletion of your personal information (uninstall the App)

**Right to Opt-Out:** We do NOT sell personal information, so opt-out is not applicable

**Right to Non-Discrimination:** We will not discriminate against you for exercising privacy rights

**Right to Correct:** Request correction of inaccurate information

**Categories of Personal Information Collected:**
- Identifiers (shop domain, email address)
- Commercial information (subscription plan)
- Internet activity (session data)

**Business Purpose:** Operating the App and providing services as described in Section 2

---

## 7. Other Privacy Laws Compliance

We comply with privacy laws in all jurisdictions where we operate, including:

- **Canada (PIPEDA):** Personal Information Protection and Electronic Documents Act
- **Australia (Privacy Act 1988):** Australian Privacy Principles
- **Brazil (LGPD):** Lei Geral de Proteção de Dados
- **India (DPDPA):** Digital Personal Data Protection Act

---

## 8. Children's Privacy

Scrolling Announcement Bar PRO is intended for use by business owners and merchants who are at least 18 years old. We do not knowingly collect information from individuals under 18. If you believe a minor has provided us with personal information, please contact us immediately at labsatdevloop@gmail.com.

---

## 9. Cookies and Tracking

### 9.1 Our Use of Cookies

The App uses minimal, essential cookies only for:

- **Authentication:** Maintaining your logged-in session in the Shopify admin interface
- **Security:** Preventing cross-site request forgery (CSRF) attacks

These cookies are set by Shopify's authentication system, not directly by our App.

### 9.2 No Customer-Facing Cookies

**Important:** We do NOT place any cookies, tracking pixels, or analytics scripts on your storefront that would track your customers. The announcement bars are purely client-side HTML/CSS elements with no tracking capabilities.

### 9.3 Future Analytics

If we add analytics tools in the future to improve the App:

- We will update this Privacy Policy with details
- We will notify you via email before implementing
- We will only use privacy-friendly analytics that do not track individual customers
- You will have the option to opt out

---

## 10. Third-Party Links

Announcement bars may contain links that you configure to direct customers to other pages or websites. We are not responsible for the privacy practices or content of any third-party websites. We encourage you and your customers to review the privacy policies of any linked websites.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect:

- Changes to our data practices
- New features or functionality
- Legal or regulatory requirements
- User feedback and best practices

### 11.1 How We Notify You of Changes

When we make material changes:

- We will update the "Last Updated" date at the top of this policy
- We will send an email notification to the shop owner email address
- We may display a notice in the App dashboard
- For significant changes affecting your rights, we will request your consent to continue using the App

### 11.2 Your Continued Use

Continuing to use the App after changes to this Privacy Policy constitutes your acceptance of the updated terms. If you do not agree with the changes, please uninstall the App before the changes take effect.

---

## 12. How to Exercise Your Privacy Rights

To exercise any privacy rights described in this policy:

### 12.1 Contact Information

**Email:** labsatdevloop@gmail.com  
**Subject Line:** "Privacy Request - [Your Shop Domain]"  
**Mailing Address:** 468, 3rd Main Road, Saraswathi Nagar South, Neelankarai 600115, Tamil Nadu, India

### 12.2 What to Include in Your Request

- Your shop domain (e.g., yourstore.myshopify.com)
- Specific right you wish to exercise
- Any additional details to help us process your request

### 12.3 Response Timeline

- We will acknowledge your request within **48 hours**
- We will fulfill valid requests within **30 days** (or as required by applicable law)
- We may require identity verification before processing requests
- If we cannot fulfill your request, we will explain why

### 12.4 Simple Data Deletion

To delete all your data immediately:
1. Go to your Shopify Admin
2. Navigate to Apps
3. Click "Delete" next to Scrolling Announcement Bar PRO
4. Your data will be automatically deleted within 48 hours

---

## 13. Data Protection Officer

We do not currently have a designated Data Protection Officer (DPO) as we are not required to under applicable law. For all privacy inquiries, please contact us directly at labsatdevloop@gmail.com.

If you are in the EU/UK and wish to lodge a complaint with a supervisory authority, you can find your local authority at:
- EU: https://edpb.europa.eu/about-edpb/board/members_en
- UK: https://ico.org.uk/

---

## 14. Support and Questions

If you have any questions, concerns, or feedback about this Privacy Policy or our data practices:

**Primary Contact:** labsatdevloop@gmail.com  
**Developer:** Devloop Labs  
**Response Time:** We aim to respond within 48 hours during business days

**For App Support:** Please use the same email address for technical support, billing questions, or feature requests.

---

## 15. Transparency Commitment

We believe in complete transparency about data handling. This Privacy Policy describes all data we collect and how we use it. We commit to:

- ✅ Never collecting more data than necessary for App functionality
- ✅ Never selling or renting your data
- ✅ Never tracking your customers
- ✅ Promptly deleting data when you uninstall
- ✅ Responding quickly to privacy requests
- ✅ Keeping this policy accurate and up-to-date

---

## Summary - Quick Reference

**What We Collect:**
- Shop domain and owner email
- OAuth authentication tokens
- Session data for app functionality

**What We DON'T Collect:**
- Customer personal information
- Order or product data
- Analytics or tracking data
- Payment information

**How We Use Your Data:**
- App authentication and functionality
- Subscription management (via Shopify)
- Service improvements

**Data Sharing:**
- No third-party sharing
- Data stays within Shopify ecosystem
- Stored on secure hosting infrastructure

**Data Retention:**
- Kept while App is installed
- Automatically deleted within 48 hours of uninstallation
- Backups retained 7-30 days by hosting provider

**Your Rights:**
- Access, correct, or delete your data
- Uninstall the App to delete all data
- Contact us with privacy requests

**Security:**
- Encrypted data transmission (HTTPS)
- Secure database storage
- OAuth authentication
- Regular security updates

**Contact:**
- Email: labsatdevloop@gmail.com
- Developer: Devloop Labs
- Location: Chennai, Tamil Nadu, India

---

**By installing and using Scrolling Announcement Bar PRO, you acknowledge that you have read, understood, and agree to this Privacy Policy.**

---

*This Privacy Policy is effective as of November 11, 2025, and applies to all users of Scrolling Announcement Bar PRO.*
