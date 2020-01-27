---
title: Leveraging the NSF Awards API for Compliance Automation
header:
  image: ''
layout: single
author_profile: true
read_time: true
comments: true
share: true
related: true

---
The [NSF Awards API](https://www.research.gov/common/webapi/awardapisearch-v1.htm) provides easy programmatic access to the agency's public grant records, which can be helpful in various scenarios. For instance: RCR requirement notifications, NSF Harassment Term & Condition monitoring, and internal notifications based on the award end date. Additionally, you can quickly produce a list of active awards that includes PIs and Co-PIs.

You can access data from the API in a number of ways. In particular, python and Google Sheets are two accessible options that let you build upon the API as a base to automate repetitive tasks.

One of the simplest ways to use python is via Google Colab:

Google Sheets can also access NSF data through its XMLPARSE function.