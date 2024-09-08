# DNS Leak Test Script

This repository contains a Python script designed to test for DNS leaks on your network by querying DNS servers, verifying DNS over TLS (DoT) configuration, and running tests against multiple DNS leak test websites. The script generates a visually appealing HTML report with warnings if a DNS leak is detected, along with possible solutions.

## Features

- Queries DNS servers (Cloudflare and Google) to check for proper DNS resolution.
- Verifies if DNS over TLS (DoT) is properly configured on the network.
- Tests against multiple DNS leak test websites.
- Generates a detailed HTML report with the results, including warnings and solutions for potential DNS leaks.
  
## Requirements

- Python 3.x
- Required Python packages:
  - `dnspython`
  - `requests`

To install the required packages, run:

```bash
pip install dnspython requests
