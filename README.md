# scammy-bbp
Bug bounty programs that are "scammy" or unethical can sometimes involve promising rewards to researchers for identifying security flaws, but either delay payments, don't pay at all, or misuse the disclosed vulnerabilities. 


Signs of a Potentially Scammy Bug Bounty Program:

- Unclear Terms and Conditions: Programs that don't clearly specify what vulnerabilities qualify for rewards or the amount of the reward.
- No Transparent Payment Structure: Lack of details about payment timelines, payout methods, or cases where people report not getting paid.
- Little to No Community Feedback: Lack of reputation or negative reviews from the infosec community.

`Hits: # of reports of being scammy`

| Program Name              | Issues Reported                                        | Platform | Source     | Hits
|---------------------------|-------------------------------------------------------|------------|----------------------| ------
| **[Standard.com](https://www.standard.com/get-to-know-standard/responsible-disclosure-program)**    | No rewards<sup>1</sup> |Self hosted| Trusted hacker        | 1
| **[H&M](https://www.hm.com/security.txt)** | No rewards<sup>1</sup> |Self hosted|  Trusted hacker | 2
| **[Celonis](https://www.celonis.com/pdf/vulnerability-disclosure-program/)** | Ignored reports<sup>2</sup> | Self hosted |Trusted hacker        | 1
| **[Kaseya](https://www.kaseya.com/trust-center/vulnerability-disclosure-policy/)** | Report triaged, then no replies| Self hosted| Trusted hacker     | 1 
| **[TataPlay](https://www.tataplay.com/bug-bounty-hunter)** | Automated Response, then no response | Self hosted| Trusted Hacker | 1
| **[Synack](https://synack.responsibledisclosure.com/hc/en-us)** | They will assign a reward only if you have an account in their site (which is very difficult to get) |Self hosted | Trusted Hacker | 1
| **[Zeiss](https://www.zeiss.com/disclosure-policy.pdf)**| Ignored reports<sup>2</sup> | Self hosted |Trusted hacker| 1
| **[Alefed](https://vdp.alefeducation.com/p/Vulnerability-Disclosure-Policy-and-Submission-Form)**| No impact but fixed<sup>3</sup> |Self hosted+YesWeHack|Trusted hacker | 1
| **[Cex.io](https://blog.cex.io/news/cex-io-bug-bounty-program-and-policy-22948)**| Failed to pay<sup>4</sup> | Self hosted | Trusted hacker | 1 
| **[Roche](https://hackerone.com/roche?type=team)** | Patch & Pass<sup>5</sup>. They won't invite you to their private program unless you report a P1/P2 bug. They mark report as duplicated when they are fresh subdomain takeovers. They claimed all DNS takeovers were dups without having the full list of domains (150 cases). |Self hosted | Trusted Hacker | 2
| **[Zopa](https://zopa.com/.well-known/security.txt)** | Scope Surprise!<sup>8</sup> |Self hosted | Trusted hacker | 1

## Details


- <sup>1</sup>No rewards: They promise rewards for reports in their program, but fail to pay them. Sometimes they just say they stopped paying rewards or they can't do it anymore.
- <sup>2</sup>Ignored reports: They never replied back to researcher. Never > 2 months and counting.
- <sup>3</sup>No impact but fixed: Bug triaged as CVSS 0, no impact or similar but fixed anyways.  
- <sup>4</sup>Failed to pay: Agreed to pay a bounty but never accomplished it. Often ignoring follow-up emails.
- <sup>5</sup>Patch & Pass: They fix reported bugs but mark them as Out of scope.
- <sup>8</sup>Scope Surprise!: They define their  Inscope and Outscope after you send the report, they dont write down in their program brief.

