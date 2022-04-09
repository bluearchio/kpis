Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# kpis

This project collects the outputs from conversations in the Slack [#KPIs room](https://finopsfoundation.slack.com/archives/CM25PLFD5).

## List of common FinOps KPIs

### platform team, sre, eng

### finance 

| KPI | purpose | audience |   |   |
|---|---|---|---|---|
|% of resoruces considered waste (qty) | determine (1) how severe waste problem is and (2) if clean-up action is needed | eng  |   |   |
|percentage of resources that are considered waste ($) | determine (1) how severe waste problem is and (2) if clean-up action is needed | eng  |   |   |
| total cost of resources that are considered waste  | determine (1) how severe waste problem is and (2) if clean-up action is needed  | eng  |   |   |
| % of untagged resources  | baseline: determine if / when new tagging efforts are needed  | eng  |   |   |
| opportunity value of rightsizing efforts | determine when/if cleanup action is necessary  | eng  |   |   |
| % of orphaned ebs volumes  | determine when/if cleanup action is necessary  | eng  |   |   |
| % of orphaned snapshots  | determine when/if cleanup action is necessary  | eng  |   |   |
| avg age of snapshots  | determine if new lifecycle policies are needed  | eng  |   |   |
| idle instances > 30-days  | locate instances to shut-down or terminate  | eng  |   |   |
| Idle instances < 30-days  | no actions required: useful visibility metric  | eng  |   |   |
| % of oversized instances (not tagged as approved)  | targets for rightsizing  | eng  |   |   |
| % S3 storage on without recommended tier  |   |   |   |   |
| % S3 storage on the wrong tier  |   |   |   |   |
| % EBS storage on without recommended tier  |   |   |   |   |
| % EBS storage on wrong tier  |   |   |   |   |
| % unattached elastic IPs  |   |   |   |   |
| % instances without recommended instance type  |   |   |   |   |
| % dev resources running out of hours (this means, running out of non-peak hours, like nights and weekends  |   |   |   |   |
| % untagged resources  |   |   |   |   |
| % total tag coverage  |   |   |   |   |
| % taggable items tagged  |   |   |   |   |
| % of spend that is untaggable  |   |   |   |   |
| frequency of data updates  |   |   |   |   |
| avg price per hour of compute |   |   |   |   |
| unit cost (total spend divided by a business metric)  |   |   |   |   |
| SP/RI coverage percentage   | determine when or if to buy new plans   | finance  |   |   |
| SP/RI utilization percentage   | determine when or if to sell existing plans, or prefer specific resource types   | finance  |   |   |
| expiring SP/RI plans   | select when or if to purchase new plans   | finance  |   |   |
| total spot pricing opportunities (#)  | determine spot eligibility  | finance  |   |   |
| total spot pricing opportunities ($)  | determine spot viability  | finance  |   |   |
| total bill vs forecast (14, 21, 28 day)   |   | finance   |   |   |
| budget variance   |   | finance   |   |   |
| forecast variance (14, 21, 28 day)   | finance  |   |   |   |
| usage on weekdays VS weekends   |   | finance  |   |   |


## Planned Projects

* Add categories to KPIs (tags, optimization, accuracy, etc)
* Add FinOps team OKRs / Goals

## Related Links

* https://www.finops.org/blog/setting-finops-goals-okrs/
* https://www.finops.org/blog/optimization-kpis-rightsizing-workflows/
* https://www.oreilly.com/library/view/cloud-finops/9781492054610/ch16.html


