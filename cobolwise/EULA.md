# Cobolwise: COBOL & Copybooks — End User License Agreement

Last updated: 10 October 2026

This End User License Agreement ("EULA") is concluded between You and KITSS TECH (the "Developer") with respect to the
Cobolwise: COBOL & Copybooks plugin (the "Plugin"). JetBrains s.r.o. is not a party to this EULA.

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

2.4. Third-Party Components. The Plugin bundles the COBOL Language Support server of the Eclipse Che4z project
(`server.jar`, Eclipse Public License 2.0); its license and notice are shipped next to it, in the `language-server`
folder of the Plugin, and this EULA does not apply to it. The Plugin requires the LSP4IJ plugin (Eclipse Public License
2.0), installed separately by the IDE. GnuCOBOL (GNU GPL and LGPL) and COBOL Check (Apache License 2.0) are not part of
the Plugin: You install them, or You build the toolchain image that contains them as described in Section 4.2. Nothing
in this EULA limits Your rights under those licenses.

2.5. Duration. The license to the Paid Features is time-limited to the duration of Your Subscription Period, including
any free trial period offered through JetBrains Marketplace.

## 3. Subscription

3.1. Subscription Limits. You must use the Paid Features in accordance with the limits of Your subscription plan,
including the number of Plugin Users.

3.2. Subscription Period. The Subscription Period can be either annual or monthly. Purchases, renewals, refunds and
cancellations are handled by JetBrains as reseller, under the terms shown at purchase.

## 4. Your Files, Your Tools and the Network

4.1. Your Data. The Plugin reads the source and project files You open, locally, in Your IDE. The Developer does not
collect, receive or store Your files or usage data. The Plugin contains no telemetry and does not call the network.

4.2. Your Tools. The Plugin runs the GnuCOBOL compiler (`cobc`) and COBOL Check that You installed on Your computer, or
runs them in a Docker image built on Your computer. The Plugin never downloads nor installs them by itself. When You
click Build Image in the settings, the Plugin starts `docker build` with the Dockerfile shipped in the Plugin, in a
console You see; Docker then downloads a Debian base image, the GnuCOBOL sources from ftp.gnu.org and COBOL Check from
GitHub, checked by SHA-256. You are responsible for holding valid licenses for these tools and for Docker.

4.3. Files Written. The Plugin does not rewrite Your source files, except when You edit them or apply a change You
asked for. Programs it builds, and the files written by COBOL Check, go to the `.cobolwise` folder of Your project. A
data layout is exported only to the file You choose. Help | Open Cobolwise Example Project copies an example project to
the folder `CobolwiseExample` of Your home folder.

4.4. Results. Data layouts, compiler messages, test reports and code insight are aids to Your work. Layouts are computed
by the Plugin and may differ from those of Your production compiler and its options. You remain responsible for
verifying Your code, record layouts and results before any use.

4.5. Error Reports. When the IDE shows an error of the Plugin, You may choose to send a report through JetBrains
Marketplace. Nothing is sent unless You do so.

4.6. No Affiliation. The Plugin is an independent product of the Developer. It is not affiliated with, endorsed by or
sponsored by IBM, Micro Focus (OpenText), the Eclipse Foundation, the Open Mainframe Project, the GnuCOBOL project or
the Free Software Foundation, or Docker, Inc. "COBOL", "JCL", "GnuCOBOL" and "COBOL Check" are used only to name the
languages and tools the Plugin supports. IBM, z/OS and Enterprise COBOL are trademarks of International Business
Machines Corporation. Docker is a trademark of Docker, Inc.

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
