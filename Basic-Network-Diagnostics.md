# 🔍 Basic Network Diagnostics Guide

## 📌 Overview

This guide documents common networking diagnostic tools and troubleshooting methods used in IT support environments.

---

# Step 1: Check IP Configuration

Command:

ipconfig

Purpose:

- View IP address
- Verify gateway
- Verify DNS settings

Checks:

☐ Valid IP address assigned

☐ Default gateway present

☐ DNS servers configured

---

# Step 2: Test Local Connectivity

Command:

ping 127.0.0.1

Purpose:

Verify TCP/IP functionality.

Expected Result:

Successful replies.

---

# Step 3: Test Router Connectivity

Command:

ping 192.168.1.1

Purpose:

Verify communication with router.

Checks:

☐ Router reachable

☐ No packet loss

---

# Step 4: Test Internet Access

Command:

ping 8.8.8.8

Purpose:

Verify internet connectivity.

Checks:

☐ External connectivity working

☐ Response times acceptable

---

# Step 5: DNS Testing

Command:

nslookup google.com

Purpose:

Verify DNS resolution.

Checks:

☐ DNS server responds

☐ Domain resolves successfully

---

# Step 6: Route Analysis

Command:

tracert google.com

Purpose:

Identify routing issues.

Checks:

☐ Route completes successfully

☐ No abnormal delays

---

# Diagnostic Record

Date:

Issue:

Tools Used:

Results:

Resolution:
