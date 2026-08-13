# 🌐 Lab 02 – DNS Troubleshooting

**Status:** 🟡 In Progress

## 🎯 Objective

Understand how the Domain Name System (DNS) translates human-readable domain names into IP addresses and develop practical troubleshooting skills for identifying and resolving DNS-related connectivity problems.

This lab will demonstrate how DNS works on both Windows and macOS and how common command-line tools can be used to investigate DNS issues.

---

# 🧠 What is DNS?

The Domain Name System (DNS) is responsible for translating domain names such as:

```text
google.com
github.com
microsoft.com
```

into IP addresses that computers can use to communicate with the destination server.

For example:

```text
google.com → IP Address
```

Instead of requiring users to remember numerical IP addresses, DNS allows us to use human-readable domain names.

---
# 🔎 Lab Exercises

## Exercise 1 – Identify Configured DNS Servers

### Objective

Identify which DNS servers are being used by the operating system.

### Windows

Run:

```cmd
ipconfig /all
```

Locate:

```text
DNS Servers
```

### macOS

Run:

```bash
scutil --dns
```
