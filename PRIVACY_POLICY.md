# Privacy Policy

This Privacy Policy describes how the QBO Connector handles data when used to connect QuickBooks Online (QBO) with an Odoo instance.

## 1. Overview

This connector is used solely for personal or internal business purposes. It is not distributed to the public, does not collect data from third-party users, and does not transmit data to any external servers other than QuickBooks Online, as required for API communication.

## 2. Information Collected

The connector may access and transmit the following data to or from QuickBooks Online, strictly for synchronization purposes:

- Customer and vendor details (e.g., name, address, phone, email)
- Invoices, bills, products, payment terms, and chart of accounts

No personal information is collected beyond what is necessary to perform synchronization between Odoo and QBO.

## 3. Data Usage

All data processed by the connector is used solely to:

- Synchronize accounting records between QuickBooks Online and Odoo
- Maintain consistency of financial and contact information

No data is stored, analyzed, or shared with any third parties.

## 4. Data Storage

This connector does not store any synchronized data outside of your own systems. All information is processed in-memory or written directly to your own Odoo and QuickBooks Online accounts.

## 5. Third-Party Access

The only third-party service the connector communicates with is **QuickBooks Online** via the official Intuit API. No other external services or servers are involved.

## 6. Security

- OAuth 2.0 is used to authenticate with QuickBooks Online
- No credentials are stored or transmitted insecurely
- All communication with QBO uses HTTPS

## 7. User Control

Since this connector is used internally, you retain full control over when and how data is synced. You can disconnect the QBO integration at any time from within your Odoo system.

## 8. Changes to This Policy

If the scope of this connector changes (e.g., public distribution or multi-user features), this policy will be updated accordingly.

## 9. Contact

If you have questions about this policy, please open an issue in the GitHub repository or contact the repository owner privately.
