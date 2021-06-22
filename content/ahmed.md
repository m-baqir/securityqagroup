---
title: A7:2017-Cross-Site Scripting XSS - Ahmed Page 1
date: 1580577200000
description: Cross-site scripting, also known as XSS, allows hackers to inject malicious scripts onto a website that would run on the user's browser when they visited the site
---
# Cross-Site Scripting
There are three different types of cross-site scripting: 
	
* A __Reflected XSS__ attack involves usinn unvalidated user inputs. This is accessed through clicking and interacting with a malicious link. This is usually done in the website's back-end.

*  __Stored XSS__ is when the malicious code is sent and stored in a database of a website and to be later accessed by users when the site is accessed.

* __DOM XSS__ manipulates the Javascript DOM nodes so that attackers can inject malicious scripts that a website's users can interact with and trigger the code. This involves attackers to use the client-side of the website.

### Threat Agents / Security Weakness /Impacts
XSS is very common, being found in around two thirds of all applications. Many back-end frameworks are capable of finding some XSS issues by default. Attackers are capable of stealing user information & credentials and sending malware to website visitors.

### Group "Plain-English" Explanation
XSS is when an attack injects scripts into a website that is sent to a user's browser to track and steal their information when they visit the compromised site.