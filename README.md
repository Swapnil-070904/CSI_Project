#  CSI Final Project

This README explains how to configure advanced identity security in Microsoft Entra ID (Azure AD), including enhanced authentication, self-service password reset, and integration with third-party and on-premises applications.

## 🚀 Features Overview

## 🛡️ Multifactor Authentication (MFA) \& Two-Factor Authentication (2FA)

Strengthen security and protect user accounts with advanced authentication strategies:

- **Conditional Access Policy**: Enforce MFA based on risk, user, location, and application for flexible, security-driven controls.
- **Per-User MFA**: Enable or restrict MFA at the individual user level for granular security assignment.
- **Monitor MFA Activity**: Track sign-ins, usage patterns, and suspicious attempts with built-in monitoring and Azure AD logs.
- **2FA Methods**: Implemented via phone (calls, SMS), email-based codes, and authenticator apps to deliver layered protection.

📄 [Detailed MFA \& 2FA Task Walkthrough](./MFA_2FA.md)

## 🔑 Self-Service Password Reset (SSPR)

Empower users to reset their passwords securely, reducing admin overhead and improving end-user experience.

- Set up Azure AD Self-Service Password Reset for users, supporting robust authentication methods.
- **Monitor SSPR Activity**: Audit password reset attempts, success rates, and user trends in the Azure portal.

📄 [SSPR Task Details](./SSPR.md)

## 🚫 Account Lockout

Defend against brute force and repeated failed attempts with effective account lockout policies.

- Configured and tested account lockout settings in Azure AD for enhanced identity protection.

📄 [Account Lockout Task](./ACC_Lockout.md)

## 🌐 MFA for Third-Party Applications

Seamlessly extend Azure AD MFA to external platforms such as AWS:

- Implemented MFA for the AWS Console by integrating Microsoft Entra ID with AWS using Azure Enterprise Applications & SAML 2.0 federation.

📄 [3rd Party MFA Integration Task (AWS)](./MFA_3rd_Party.md)

## 🏢 On-Premises MFA Integration

Expand cloud security to local infrastructure:

- Extended Microsoft Entra ID (Azure AD) Multi-Factor Authentication to secure a web application hosted on an on-premises IIS server via Azure AD Application Proxy.

📄 [On-Premises MFA Integration Task](./MFA_OnPremise.md)

## 🔐 OAuth Tokens 

Developed, tested, and verified OAuth 2.0 authentication with Azure AD:

- Implemented OAuth authorization code flow using Microsoft Entra ID, with jwt.ms as the redirect URL.
- Generated client secrets, obtained authorization codes, exchanged for access tokens in Postman, and validated tokens with jwt.ms.

📄 [OAuth Task](./Oauth.md)


## 📬 Contact

For any queries reach out at: **[swapnil070904@gmail.com](mailto:swapnil070904@gmail.com)**
