# Lab 4 – XSS, Session Management and Authentication Assessment

## Overview

This lab assessed common web application security issues using the authorised DVWA and OWASP Mutillidae II laboratory environments.

The assessment focused on:

- Reflected, stored and DOM-based XSS
- Session management and cookies
- Authentication resilience
- Security controls at different application settings

## Scope

All testing was carried out only against the authorised local laboratory applications.

No real accounts or external systems were tested.

## XSS Testing

The assessment examined three main types of XSS:

- **Reflected XSS:** The input is returned directly in the response.
- **Stored XSS:** The input is saved by the application and displayed later.
- **DOM XSS:** JavaScript changes the page in a way that causes the payload to execute.

Harmless visual markers were used to confirm browser-side script execution. Testing was stopped once enough evidence had been collected.

## Session Management

Session behaviour was examined:

1. Before authentication
2. After login
3. After logout

Cookie and session behaviour were compared to understand how authenticated sessions were created, maintained and ended.

A session should rotate after login to reduce the risk of session fixation. It should also become invalid after logout to prevent session reuse.

## Authentication Testing

Authentication resilience was tested using a learner-controlled account and a strictly limited number of failed login attempts.

The applications rejected the incorrect login attempts. Testing was stopped after the required limited attempts.

The main protection observed was login validation and controlled testing of repeated failures.

Account lockout can also create an availability risk because an attacker could intentionally trigger failed logins and prevent a legitimate user from accessing their account.

## Safety and Cleanup

The assessment did not include:

- Cookie theft
- Session hijacking
- Credential collection
- Password spraying
- Credential stuffing
- Attacks against real accounts

After testing:

- Harmless markers were removed
- Sessions were logged out
- The testing environment was cleaned up
- The laboratory was restored

## Conclusion

The assessment provided practical evidence of how DVWA and OWASP Mutillidae II handle XSS, sessions and authentication. All testing remained within the authorised laboratory scope and was performed in a controlled manner.
