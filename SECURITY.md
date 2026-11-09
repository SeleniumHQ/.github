Reporting Security Issues and Vulnerabilities
=============================================

At the Selenium project we take security seriously. Whether it is the code we write or the dependencies we 
use, security is always extremely important. 

Please do not open an issue or pull request as this makes the problem immediately visible to everyone 
including malicious actors. 

Security issues in this project can be safely reported via the the following 
address:

security@seleniumhq.org

In the report, please provide a [concise reproducible test case](http://sscce.org/) and describe 
what results you are seeing and what results you expect.

A member of the Selenium project will be notified and will begin the triage process.

Release Signing Keys
====================

The Java artifacts published to Maven Central under the `org.seleniumhq.selenium` groupId are
signed with this OpenPGP key:

| | |
|---|---|
| Name | Selenium Release Signing Key <releases@selenium.dev> |
| Fingerprint | `328B 1E61 822C F53D B1EA 7C47 F461 A321 02C9 36BB` |
| Type | RSA 4096 |
| Created | 2026-01-17 |
| Expires | Does not expire |
| Signs | Java artifacts, from version 4.40.0 |

Other Selenium bindings are not signed with this key.

The public key is available at https://www.selenium.dev/keys/selenium-release-signing-key.asc
and on public keyservers. If the key changes, this page will be updated.
