# Julimate for Julia — End User License Agreement

Last updated: 10 October 2026

This End User License Agreement ("EULA") is concluded between You and KITSS TECH (the "Developer") with respect to the
Julimate for Julia plugin (the "Plugin"). JetBrains s.r.o. is not a party to this EULA.

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

2.4. Third-Party Components. The Plugin requires the LSP4IJ plugin (Eclipse Public License 2.0), installed separately by
the IDE. The Julia packages LanguageServer.jl, SymbolServer.jl and JuliaFormatter.jl (MIT License) are not part of the
Plugin: they are installed by Julia's package manager, only when You ask for it. Nothing in this EULA limits Your rights
under those licenses.

2.5. Duration. The license to the Paid Features is time-limited to the duration of Your Subscription Period, including
any free trial period offered through JetBrains Marketplace.

## 3. Subscription

3.1. Subscription Limits. You must use the Paid Features in accordance with the limits of Your subscription plan,
including the number of Plugin Users.

3.2. Subscription Period. The Subscription Period can be either annual or monthly. Purchases, renewals, refunds and
cancellations are handled by JetBrains as reseller, under the terms shown at purchase.

## 4. Your Files, Your Tools and the Network

4.1. Your Data. The Plugin reads the source and project files You open, locally, in Your IDE. The Developer does not
collect, receive or store Your files or usage data. The Plugin contains no telemetry.

4.2. Your Tools. The Plugin runs the Julia installation that You installed on Your computer, or the official `julia`
Docker image when You choose the Docker mode, with Your files. It never downloads nor installs Julia by itself and does
not call the network. Network access happens only through the tools You start from the Plugin: Julia's package manager
when You install the language server or run a package action, and Docker when it fetches the `julia` image for a run
You started. You are responsible for holding valid licenses for these tools and for the packages You install with them.

4.3. Files Written. The Plugin does not rewrite Your source files. Package actions that You start (add, rm, update,
instantiate) are performed by Julia's package manager, which updates `Project.toml` and `Manifest.toml` as Julia
documents. The language server goes to its own Julia environment (`~/.julia/environments/julimate-ls`). Figures are
written to a temporary folder, and to the folder You choose when You save them. In Docker mode the package depot is kept
in the Docker volume `julimate-depot`.

4.4. Results. Results, plots, test reports and code insight are aids to Your work. You remain responsible for verifying
Your code and results before any use.

4.5. Error Reports. When the IDE shows an error of the Plugin, You may choose to send a report through JetBrains
Marketplace. Nothing is sent unless You do so.

4.6. No Affiliation. The Plugin is an independent product of the Developer. It is not affiliated with, endorsed by or
sponsored by the Julia project, JuliaHub, Inc., the authors of LanguageServer.jl, Plots.jl or Makie, or Docker, Inc.
"Julia" is used only to name the language the Plugin supports. Docker is a trademark of Docker, Inc.

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
