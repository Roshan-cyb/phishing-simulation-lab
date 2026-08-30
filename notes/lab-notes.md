# Lab Notes

1. Lab Title

Phishing Simulation and Local Hosting Lab

 2. Purpose

The purpose of this lab was to study the behavior of a phishing simulation in a controlled and authorized environment.

The exercise was performed using an existing third-party security testing tool. The goal was to learn how a simulated login page can be presented and how a security-testing framework reports activity.

3. Lab Configuration Observed

From the terminal output:

- Login page type selected: **Traditional Login Page**
- Hosting option selected: **LocalHost**
- Port forwarding option: LocalHost
- Port used: **5555**
- Local service address displayed by the tool: `http://localhost:5555`

4. Lab Execution Summary

The testing framework presented several login-page simulation choices. The Traditional Login Page option was selected.

The framework then presented different hosting options. LocalHost was selected for the controlled test environment.

The service was initialized on port 5555 and the terminal reported that it was successfully hosted on localhost.

This kept the exercise within the local test environment rather than documenting or targeting a real external account.

5. Observations

The lab demonstrated that:

- A testing framework can provide different simulated login-page templates.
- A local web service can be used to host a test page.
- The framework provides status information during initialization.
- Login submissions and other test information can become visible to the testing framework.
- Sensitive output should be handled carefully and should not be published.

6. Security Relevance

Phishing commonly relies on convincing users to interact with a fraudulent login interface.

A successful defense therefore involves more than detecting malicious software. Users should verify the website address, avoid unexpected login links, and use strong authentication protections such as multi-factor authentication.

 7. Evidence

The `screenshots/` directory contains screenshots captured during the lab.

Sensitive credentials and raw captured data are intentionally excluded from this repository.

 8. Lessons Learned

- Understand the difference between a security-testing tool and the underlying attack technique.
- Perform security experiments only in environments where permission has been obtained.
- Keep captured credentials and other sensitive information out of Git repositories.
- Document observations and defensive lessons rather than publishing unnecessary sensitive data.

9. Conclusion

This lab provided practical exposure to the workflow of a phishing simulation in a controlled environment.

The main takeaway is that phishing can exploit user trust through familiar-looking authentication pages, making user awareness and strong authentication controls important parts of cybersecurity defense.

10. Credits

The tool used for this lab was developed by third parties. The repository should credit the original project and its developers.

Tool/project: ShellPhish
Original repository: https://github.com/AbirHasan2005/ShellPhish.git
