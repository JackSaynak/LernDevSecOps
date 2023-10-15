---
layout: default
title: DAST
permalink: /dast/
---
>Dynamic Application Security Testing (DAST) is the process of analyzing a web application through the front-end to find vulnerabilities through simulated attacks. This type of approach evaluates the application from the “outside in” by attacking an application like a malicious user would. After a DAST scanner performs these attacks, it looks for results that are not part of the expected result set and identifies security vulnerabilities.

A DAST scanner searches for vulnerabilities in a running application and then sends automated alerts if it finds flaws that allow for attacks like SQL injections, Cross-Site Scripting (XSS), and more. Since DAST tools are equipped to function in a dynamic environment, they can detect runtime flaws which SAST tools can’t identify.

To use the example of a building, a DAST scanner can be thought of like a security guard. However, rather than just making sure the doors and windows are locked, this guard goes a step further by attempting to physically break into the building. The guard might try to pick the locks on the doors or break windows. After finishing this examination, the guard could report back to the building manager and provide an explanation of how he was able to break into the building. A DAST scanner can be thought of in this same way – it actively attempts to find vulnerabilities in a running environment so the DevOps team knows where and how to fix them.