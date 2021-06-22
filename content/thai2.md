---
title: A8:2017-Insecure Deserialization - Thai page 2
date: 1624324500000
description: Insecure deserialization often leads to the remote code execution, or somes attacks such as replay attacks, injection attacks, and privilege escalation attacks.
---

# Summary
It is difficult to exploit deserialization without modifying exploit code. Deserializing hostile objects supplied by an attacker can result in two primary types of attacks:
* Object and data structure related attacks where the attacker modifies application logic or achieves arbitrary remote code execution if there are classes available to the application that can change behavior during or after deserialization.
* Typical data tampering attacks such as access-control-related attacks where existing data structures are used but the content is changed.

# Group "Plain-English" Explanation
An attacker can exploit insecure deserialization to get unauthorized access to a system or an application by catching the object serialization in HTTP requests that contains some information such as user ID, password hash, and other state.

Source: [OWASP](https://owasp.org/www-project-top-ten/2017/A8_2017-Insecure_Deserialization)