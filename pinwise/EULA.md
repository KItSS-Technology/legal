# Pinwise: Python Requirements — End User License Agreement

Last updated: 15 October 2026

This End User License Agreement ("EULA") is concluded between You and KITSS TECH (the "Developer") with respect to the
Pinwise: Python Requirements plugin (the "Plugin"). JetBrains s.r.o. is not a party to this EULA.

## 1. Definitions

"Confirmation" means an email from JetBrains confirming Your rights to use the Plugin and containing important
information about Your license or Subscription.

"Developer" means KITSS TECH, the licensor of the Plugin. Contact: support@kitss-tech.com.

"Documentation" means the latest versions of all online technical documentation available for the Plugin at JetBrains
Marketplace and any other relevant Plugin documentation provided either by JetBrains or the Developer.

"Free Features" means the features of the Plugin that can be used without a Subscription.

"JetBrains" means JetBrains s.r.o., which has its registered office at Na Hřebenech II 1718/8, Prague, 14000, Czech
Republic.

"JetBrains Marketplace" means any platform operated by JetBrains or a JetBrains affiliate on which Plugins for JetBrains
Products are marketed, including https://plugins.jetbrains.com.

"JetBrains Product" means any software program or service made available by JetBrains.

"Package Index" means PyPI or any other Python package index configured in Your files or settings (file options,
pip.conf / pip.ini, uv settings, environment variables).

"Plugin Users" means users that are able to access and use the Plugin concurrently.

"Pro Features" means the features of the Plugin marked as Pinwise Pro features in the Documentation, which require a
Subscription.

"Subscription" means Your right to use the Pro Features during the Subscription Period.

"Subscription Period" means the Subscription period described in Your Confirmation.

"You" means an individual or an entity concluding this EULA.

## 2. Grant of License

2.1. License. The Developer grants You a limited, worldwide, non-exclusive, non-transferable license to use the Plugin
(including any generally available updates and upgrades released during Your rightful use of the Plugin) as long as the
use is in line with this EULA, the Documentation and, for the Pro Features, Your Confirmation. You may install the
Plugin, use it, and make backup copies for archival purposes.

2.2. Free Features. You may use the Free Features free of charge, for any purpose, including commercial use, without a
Subscription and without time limit.

2.3. Pro Features. You may use the Pro Features only during Your Subscription Period, including any free trial period
offered through JetBrains Marketplace, and within the limits of Your subscription plan.

2.4. Restrictions. You may not modify, reverse-engineer, decompile or disassemble the Plugin in whole or in part,
create any derivative works from the Plugin, circumvent its license verification, or sublicense any rights to the
Plugin, unless expressly authorized in writing by the Developer.

## 3. Subscription

3.1. Subscription Limits. You must use the Pro Features in accordance with the limits of Your subscription plan,
including the number of Plugin Users.

3.2. Subscription Period. The Subscription Period can be either annual or monthly. Purchases, renewals, refunds and
cancellations are handled by JetBrains as reseller, under the terms shown at purchase.

## 4. Your Data

4.1. Network Requests. To show versions, hashes and licenses, the Plugin sends the names of the packages of Your files to
the Package Index of these files. To show vulnerabilities (Pro Features), it sends package names and versions to the OSV
database (api.osv.dev), operated by Google under its own terms. No other content of Your files is sent. All these
requests can be turned off in the settings of the Plugin; the Plugin then works from its local cache. The Plugin
contains no telemetry and does not send Your code, Your files or any usage data to the Developer. License verification
is performed by the JetBrains Product through JetBrains' own licensing mechanism.

4.2. Credentials. Credentials of private Package Indexes are read from the index URL, from Your ~/.netrc file or from
the password safe of the JetBrains Product. The Plugin uses them only for requests to that Package Index, never writes
them to a file of its own and never logs them. You remain responsible for these credentials and for Your compliance with
the terms of Your Package Index.

4.3. Commands You Start. The Plugin never installs any package by itself. When You choose to compile requirements or to
sync an environment, the Plugin runs pip-compile, pip-sync or uv on Your computer, which may download and install
packages from Your Package Index under their own configuration and terms.

4.4. Your Files. The Plugin changes Your files only when You ask it to, for example when You accept a quick fix, sort or
format a file, update dependencies or regenerate hashes. You remain responsible for Your files and for keeping them
under version control.

4.5. Information Only. Versions, vulnerabilities and licenses are shown as reported by the Package Index and the OSV
database. The Developer does not guarantee that they are complete, accurate or up to date, and they are no substitute
for Your own security and legal review.

## 5. Intellectual Property

5.1. The Plugin is protected by copyright and other intellectual property laws and treaties. The Developer or its
licensors own all title, copyright and other intellectual property rights to the Plugin.

5.2. Names of third-party products mentioned by the Plugin or its Documentation, such as Python, PyPI, pip, pip-tools,
uv, Poetry and OSV, are trademarks of their respective owners. The Plugin is an independent product of the Developer and
is not affiliated with, endorsed by or sponsored by these owners.

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

This EULA terminates automatically if You fail to comply with it. When Your Subscription ends, Your right to use the
Pro Features ends and You may keep using the Free Features under this EULA. Upon termination You must stop using the
Plugin.

## 9. Governing Law

This EULA is governed by the laws of France, without regard to its conflict-of-laws rules, and without prejudice to
mandatory consumer protection rules of Your country of residence.
