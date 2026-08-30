# Phishing Simulation Lab

## Overview

This repository documents a cybersecurity lab that I performed in an authorized test environment using an existing third-party security testing tool.

The purpose of the lab was to understand the basic workflow of a phishing simulation, observe how a test login page behaves, and study the security implications of credential phishing.

I am documenting my own lab execution and observations. The underlying tool was created by its original developers and is not my original software.

## Lab Objective

- Understand how a simulated login page is hosted in a test environment.
- Observe the available login-page simulation options.
- Understand how local hosting works during a security lab.
- Observe the type of information that a testing framework reports.
- Learn defensive measures against phishing attacks.

## Environment

- Environment: Authorized local/test lab
- Hosting: Localhost
- Test port observed: `5555`
- Login-page simulation selected: Traditional Login Page
- Tool/framework: **[ADD TOOL NAME]**

## Evidence

Screenshots from the lab execution are stored in the `screenshots/` directory.

The screenshots show:
1. Selection of a traditional login-page simulation.
2. The test service being hosted locally at `http://localhost:5555`.
3. The lab output showing test victim information and login information.

## Important Security Note

Captured credentials, tokens, cookies, personal information, and other sensitive output should not be committed to a public repository.

Any sensitive lab output should remain local or be replaced with sanitized/redacted examples before publishing.

## What I Learned

The lab helped me understand that phishing attacks can imitate familiar login interfaces and can collect information when users submit data.

It also demonstrated why organizations should use multi-factor authentication, phishing-resistant authentication, security awareness training, email filtering, and monitoring of suspicious authentication activity.

## Defensive Takeaways

- Never enter credentials into an unexpected login page.
- Verify the domain before signing in.
- Use multi-factor authentication.
- Prefer phishing-resistant authentication where available.
- Use password managers to help detect incorrect domains.
- Monitor authentication logs for suspicious activity.
- Conduct security testing only with proper authorization.

## Credits

This lab used an existing third-party security testing tool/framework.

**Original tool:** [ADD ORIGINAL PROJECT / GITHUB LINK]

The underlying tool is not my original work. This repository documents my own educational lab exercise, observations, and learning.

## Disclaimer

This project was performed for educational purposes in an authorized test environment. Do not use phishing or credential-capture techniques against systems, accounts, or people without explicit permission.
