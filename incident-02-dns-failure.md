# Incident #02 — DNS Resolution Failure

## Date: March 2025
## Severity: Medium
## Status: Resolved

---

## Problem
Users could access internal systems but could not open any websites.
Typing IP addresses in the browser worked, but domain names did not.

---

## Initial Symptoms
- google.com not loading, but 8.8.8.8 pingable
- nslookup returning "DNS request timed out"
- Only affects internet browsing, not internal systems

---

## Logs
