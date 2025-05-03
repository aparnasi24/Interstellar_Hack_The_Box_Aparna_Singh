# Hack The Box: Interstellar Challenge – Exploitation Script

This repository contains a set of commands used to exploit the **Interstellar** machine on [Hack The Box](https://www.hackthebox.com/) using two menthods. The first method is through tool 'Curl' and the second mentod is through python code. This attack showcases the exploitation of an insecure internal service via SSRF and SQL injection, leading to remote code execution.

## Overview

Below are the steps:

1. **User Registration & Login**  
2. **Session Capture via Cookies**
3. **SSRF to Internal Service**
4. **SQL Injection for Remote Code Execution (Web Shell Upload)**
5. **Command Execution through Web Shell**
6. **Recursive Directory Listing**
7. **Flag File Discovery**
8. **Flag Retrieval**

---

## File: `interstellar_attack_commands.sh`

Each step is annotated for clarity and uses `curl` to interact with the vulnerable web application.

---

## Usage

Run each command step-by-step in your terminal. Ensure `curl` is installed and your environment allows outbound HTTP connections
