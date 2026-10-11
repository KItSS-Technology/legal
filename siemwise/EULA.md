# Siemwise: KQL, SPL & YARA — End User License Agreement

Last updated: 11 October 2026

This End User License Agreement ("EULA") is concluded between You and KITSS TECH (the "Developer") with respect to the
Siemwise: KQL, SPL & YARA plugin (the "Plugin"). JetBrains s.r.o. is not a party to this EULA.

## 1. Definitions

"Confirmation" means an email from JetBrains confirming Your rights to use the Plugin and containing important
information about Your license or Subscription.

"Developer" means KITSS TECH, the licensor of the Plugin. Contact: support@kitss-tech.com.

"Documentation" means the latest versions of all online technical documentation available for the Plugin at JetBrains
Marketplace and any other relevant Plugin documentation provided either by JetBrains or the Developer.

"Free Features" means the features of the Plugin that the Documentation describes as available without a license.

"JetBrains" means JetBrains s.r.o., which has its registered office at Na Hřebenech II 1718/8, Prague, 14000, Czech
Republic.

"JetBrains Marketplace" means any platform operated by JetBrains or a JetBrains affiliate on which Plugins for JetBrains
Products are marketed, including https://plugins.jetbrains.com.

"JetBrains Product" means any software program or service made available by JetBrains.

"Paid Features" means the features of the Plugin that the Documentation describes as requiring a license.

"Plugin Users" means users that are able to access and use the Plugin concurrently.

"Subscription" means Your right to use the Paid Features during the Subscription Period.

"Subscription Period" means the Subscription period described in Your Confirmation.

"You" means an individual or an entity concluding this EULA.

## 2. Grant of License

2.1. Free Features. The Developer grants You a limited, worldwide, non-exclusive, non-transferable, royalty-free license
to install the Plugin and use its Free Features, without time limit, subject to the limits set out in this EULA.

2.2. Paid Features. The Developer grants You a limited, worldwide, non-exclusive, non-transferable license to use the
Paid Features (including any generally available updates and upgrades released during Your rightful use of the Plugin)
as long as the use is in line with Your Confirmation, the Documentation and the limits set out in this EULA.

2.3. Restrictions. You may not modify, reverse-engineer, decompile or disassemble the Plugin in whole or in part,
create any derivative works from the Plugin, circumvent its license verification, or sublicense any rights to the
Plugin, unless expressly authorized in writing by the Developer.

2.4. Third-Party Components. The Plugin bundles no third-party library. It includes the JSON schema of Sigma rules taken
from the Sigma specification, which is in the public domain (see its notice in the Plugin). Its KQL and SPL function
catalogs and its Microsoft Sentinel and Defender table schema list names, parameters and column types; their summaries
are written by the Developer. YARA and sigma-cli with pySigma and its backends are not part of the Plugin: the Plugin runs
them as external programs, installed by You or built by You into a local Docker image from the Dockerfile shipped with
the Plugin, under their own licenses.

2.5. Duration. The license to the Paid Features is time-limited to the duration of Your Subscription Period, including
any free trial period offered through JetBrains Marketplace.

## 3. Subscription

3.1. Subscription Limits. You must use the Paid Features in accordance with the limits of Your subscription plan,
including the number of Plugin Users.

3.2. Subscription Period. The Subscription Period can be either annual or monthly. Purchases, renewals, refunds and
cancellations are handled by JetBrains as reseller, under the terms shown at purchase.

## 4. Your Files and the Network

4.1. Your Data. The Plugin reads the queries, rules, schemas and samples You open or select, locally, in Your IDE. The
Developer does not collect, receive or store Your files, Your rules, Your samples or usage data. The Plugin contains no
telemetry and does not call the network. It does not connect to any SIEM, Kusto cluster, Log Analytics workspace,
Splunk instance, VirusTotal or other online service.

4.2. Samples. Files You test YARA rules against may be malicious. They stay on Your machine: the Plugin passes them to
YARA running on Your machine, or in a Docker container started without network that only sees Your project folder. You
remain responsible for handling malicious files safely and lawfully.

4.3. Files Written. The Plugin does not rewrite Your files, except when You edit them or apply a change You asked for:
a reformat, a quick-fix or a rename. Sigma conversions open in a new editor tab that is saved only if You save it. The
sample project is copied only to a folder You choose. Keep Your rules under version control.

4.4. Results. Completion, inspections, YARA test results and Sigma conversions are aids to Your work. The Plugin does not
run Your queries; schema-based checks may differ from Your environment, and converted queries must be reviewed before
use. You remain responsible for verifying Your detections and their results before any use.

4.5. Error Reports. When the IDE shows an error of the Plugin, You may choose to send a report through JetBrains
Marketplace. Nothing is sent unless You do so.

4.6. No Affiliation. The Plugin is an independent product of the Developer. It is not affiliated with, endorsed by or
sponsored by Microsoft Corporation, Splunk LLC, Cisco Systems, VirusTotal or the Sigma project. "KQL", "SPL", "YARA" and
"Sigma" are used only to name the languages and formats the Plugin supports. Microsoft, Microsoft Sentinel, Microsoft
Defender and Kusto are trademarks of the Microsoft group of companies; Splunk is a trademark of Splunk LLC, a Cisco
company.

## 5. Intellectual Property

The Plugin is protected by copyright and other intellectual property laws and treaties. The Developer or its licensors
own all title, copyright and other intellectual property rights to the Plugin.

## 6. Disclaimer of Warranty

THE PLUGIN IS PROVIDED TO YOU ON AN "AS-IS" AND "AS AVAILABLE" BASIS WITHOUT WARRANTIES. YOUR USE OF THE PLUGIN IS AT
YOUR OWN RISK. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE DEVELOPER DISCLAIMS ALL WARRANTIES AND
CONDITIONS, EITHER EXPRESS OR IMPLIED, INCLUDING IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE, TITLE AND NON-INFRINGEMENT. THE DEVELOPER DOES NOT WARRANT THAT THE PLUGIN MEETS YOUR REQUIREMENTS, THAT IT
WILL BE AVAILABLE UNINTERRUPTED, OR THAT ANY DEFECT WILL BE CORRECTED. UPDATES ARE PROVIDED AT THE DEVELOPER'S SOLE
DISCRETION.

## 7. Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE DEVELOPER SHALL NOT BE LIABLE FOR ANY INDIRECT OR CONSEQUENTIAL
DAMAGES OR LOST PROFITS, AND THE DEVELOPER'S AGGREGATE LIABILITY ARISING OUT OF OR RELATED TO THIS EULA OR THE USE OF
THE PLUGIN SHALL NOT EXCEED THE FEES YOU PAID FOR THE PLUGIN VIA JETBRAINS MARKETPLACE IN THE THREE-MONTH PERIOD
PRECEDING THE CLAIM. JETBRAINS' LIABILITY IS EXCLUDED IN ITS ENTIRETY, AS JETBRAINS IS NOT A PARTY TO THIS EULA.

## 8. Termination

This EULA terminates automatically if You fail to comply with it. The license to the Paid Features also ends when Your
Subscription ends. Upon termination You must stop using the Plugin, or the Paid Features as the case may be.

## 9. Governing Law

This EULA is governed by the laws of France, without regard to its conflict-of-laws rules, and without prejudice to
mandatory consumer protection rules of Your country of residence.
