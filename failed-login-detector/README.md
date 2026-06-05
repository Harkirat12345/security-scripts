# Failed Login Detector

## Overview

Python-based log analysis tool that processes authentication logs to identify failed login attempts, track source IP addresses, and monitor targeted usernames.

## Features

- Counts failed login attempts
- Tracks source IP addresses
- Identifies repeated usernames
- Generates a summary report

## Sample Output

```text
===== Failed Login Report =====

Number of failed logins: 3

Failed logins by IP:
192.168.1.10: 2
172.16.0.8: 1

Repeated usernames:
root: 1
admin: 1
guest: 1


---

### About `auth.log`

Since this is a project repo, keep a small sample log file:

```text
auth.log
