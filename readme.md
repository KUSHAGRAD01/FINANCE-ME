[![Packagist][packagist-shield]][packagist-url]
[![License][license-shield]][license-url]
[![Stargazers][stars-shield]][stars-url]
[![Donate][donate-shield]][donate-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://FINANCE-ME-iii.org/">
    <img src="https://raw.githubusercontent.com/FINANCE-ME-iii/FINANCE-ME-iii/develop/.github/assets/img/logo-small.png" alt="FINANCE-ME III" width="120" height="178">
  </a>
</p>
  <h1 align="center">FINANCE-ME III</h1>

  <p align="center">
    A free and open source personal finance manager
    <br />
    <a href="https://docs.FINANCE-ME-iii.org/"><strong>Explore the documentation</strong></a>
    <br />
    <br />
    <a href="https://demo.FINANCE-ME-iii.org/">View the demo</a>
    ·
    <a href="https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/issues">Report a bug</a>
    ·
    <a href="https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/issues">Request a feature</a>
    ·
    <a href="https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/discussions">Ask questions</a>
  </p>

<!-- MarkdownTOC autolink="true" -->

- [About FINANCE-ME III](#about-FINANCE-ME-iii)
  - [Purpose](#purpose)
- [Features](#features)
- [Who's it for?](#whos-it-for)
- [The FINANCE-ME III eco-system](#the-FINANCE-ME-iii-eco-system)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Support the development of FINANCE-ME III](#support-the-development-of-FINANCE-ME-iii)
- [License](#license)
- [Do you need help, or do you want to get in touch?](#do-you-need-help-or-do-you-want-to-get-in-touch)
- [Acknowledgements](#acknowledgements)

<!-- /MarkdownTOC -->

## About FINANCE-ME III

<p align="center">
	<img src="https://raw.githubusercontent.com/FINANCE-ME-iii/FINANCE-ME-iii/develop/.github/assets/img/imac-complete.png" alt="FINANCE-ME III on iMac" />
</p>

"FINANCE-ME III" is a (self-hosted) manager for your personal finances. It can help you keep track of your expenses and income, so you can spend less and save more. FINANCE-ME III supports the use of budgets, categories and tags. Using a bunch of external tools, you can import data. It also has many neat financial reports available.

FINANCE-ME III should give you **insight** into and **control** over your finances. Money should be useful, not scary. You should be able to *see* where it is going, to *feel* your expenses and to... wow, I'm going overboard with this aren't I?

But you get the idea: this is your money. These are your expenses. Stop them from controlling you. I built this tool because I started to dislike money. Having money, not having money, paying bills with money, you get the idea. But no more. I want to feel "safe", whatever my balance is. And I hope this tool can help you. I know it helps me.

### Purpose

<p align="center">
  <img src="https://raw.githubusercontent.com/FINANCE-ME-iii/FINANCE-ME-iii/develop/.github/assets/img/ipad-complete.png" alt="FINANCE-ME III on iPad" width="600">
</p>

Personal financial management is pretty difficult, and everybody has their own approach to it. Some people make budgets, other people limit their cashflow by throwing away their credit cards, others try to increase their current cashflow. There are tons of ways to save and earn money. FINANCE-ME III works on the principle that if you know where your money is going, you can stop it from going there.

By keeping track of your expenses and your income you can budget accordingly and save money. Stop living from paycheck to paycheck but give yourself the financial wiggle room you need.

You can read more about the purpose of FINANCE-ME III in the [documentation](https://docs.FINANCE-ME-iii.org/).

## Features

FINANCE-ME III is pretty feature packed. Some important stuff first:

* It is completely self-hosted and isolated, and will never contact external servers until you explicitly tell it to.
* It features a REST JSON API that covers almost every part of FINANCE-ME III.

The most exciting features are:

* Create [recurring transactions to manage your money](https://docs.FINANCE-ME-iii.org/explanation/financial-concepts/recurring/).
* [Rule based transaction handling](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/features/rules/) with the ability to create your own rules.

Then the things that make you go "yeah OK, makes sense".

* A [double-entry](https://en.wikipedia.org/wiki/Double-entry_bookkeeping_system) bookkeeping system.
* Save towards a goal using [piggy banks](https://docs.FINANCE-ME-iii.org/explanation/financial-concepts/piggy-banks/).
* View [income and expense reports](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/finances/reports/).

And the things you would hope for but not expect:

* 2 factor authentication for extra security 🔒.
* Supports [any currency you want](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/features/currencies/).
* There is a [Docker image](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/installation/docker/).

And to organise everything:

* Clear views that should show you how you're doing.
* Easy navigation through your records.
* Lots of charts because we all love them.

Many more features are listed in the [documentation](https://docs.FINANCE-ME-iii.org/explanation/FINANCE-ME-iii/about/introduction/).

## Who's it for?
<img src="https://raw.githubusercontent.com/FINANCE-ME-iii/FINANCE-ME-iii/develop/.github/assets/img/iphone-complete.png" alt="FINANCE-ME III on iPhone" align="left" width="250">

 This application is for people who want to track their finances, keep an eye on their money **without having to upload their financial records to the cloud**. You're a bit tech-savvy, you like open source software and you don't mind tinkering with (self-hosted) servers.
 
 <br clear="left"/>

## The FINANCE-ME III eco-system

Several users have built pretty awesome stuff around the FINANCE-ME III API. [Check out these tools in the documentation](https://docs.FINANCE-ME-iii.org/references/FINANCE-ME-iii/third-parties/apps/).

## Getting Started

There are many ways to run FINANCE-ME III
1. There is a [demo site](https://demo.FINANCE-ME-iii.org) with an example financial administration already present.
2. You can [install it on your server](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/installation/self-managed/).
3. You can [run it using Docker](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/installation/docker/).
4. You can [deploy via Kubernetes](https://FINANCE-ME-iii.github.io/kubernetes/).
5. You can [install it using Softaculous](https://www.softaculous.com/softaculous/apps/others/FINANCE-ME_III).
6. You can [install it using AMPPS](https://www.ampps.com/).
7. You can [install it on Cloudron](https://cloudron.io/store/org.FINANCE-MEiii.cloudronapp.html).
8. You can [install it on Lando](https://gist.github.com/ArtisKrumins/ccb24f31d6d4872b57e7c9343a9d1bf0).
9. You can [install it on Yunohost](https://github.com/YunoHost-Apps/FINANCE-ME-iii).

## Contributing

You can contact me at [james@FINANCE-ME-iii.org](mailto:james@FINANCE-ME-iii.org), you may open an issue in the [main repository](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii) or contact me through [gitter](https://gitter.im/FINANCE-ME-iii/FINANCE-ME-iii) and [Mastodon](https://fosstodon.org/@ff3).

Of course, there are some [contributing guidelines](https://docs.FINANCE-ME-iii.org/explanation/support/#contributing-code) and a [code of conduct](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/blob/main/.github/code_of_conduct.md), which I invite you to check out.

I can always use your help [squashing bugs](https://docs.FINANCE-ME-iii.org/explanation/support/), thinking about [new features](https://docs.FINANCE-ME-iii.org/explanation/support/) or [translating FINANCE-ME III](https://docs.FINANCE-ME-iii.org/how-to/FINANCE-ME-iii/development/translations/) into other languages.

[Sonarcloud][sc-project-url] scans the code of FINANCE-ME III. If you want to help improve FINANCE-ME III, check out the latest reports and take your pick!

[![Quality Gate Status][sc-gate-shield]][sc-project-url] [![Bugs][sc-bugs-shield]][sc-project-url] [![Code Smells][sc-smells-shield]][sc-project-url] [![Vulnerabilities][sc-vuln-shield]][sc-project-url]

There is also a [security policy](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/security/policy).

[![CII Best Practices][bp-badge]][bp-url]

<!-- SPONSOR TEXT -->

## Support the development of FINANCE-ME III

If you like FINANCE-ME III and if it helps you save lots of money, why not send me a dime for every dollar saved! 🥳

OK that was a joke. If you feel FINANCE-ME III made your life better, please consider contributing as a sponsor. Please check out my [Patreon](https://www.patreon.com/jc5) and [GitHub Sponsors](https://github.com/sponsors/JC5) page for more information. You can also [buy me a ☕️ coffee at ko-fi.com](https://ko-fi.com/Q5Q5R4SH1). Thank you for your consideration.

<!-- END OF SPONSOR TEXT -->

## License

This work [is licensed](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/blob/main/LICENSE) under the [GNU Affero General Public License v3](https://www.gnu.org/licenses/agpl-3.0.html).

<!-- HELP TEXT -->

## Do you need help, or do you want to get in touch?

Do you want to contact me? You can email me at [james@FINANCE-ME-iii.org](mailto:james@FINANCE-ME-iii.org) or get in touch through one of the following support channels:

- [GitHub Discussions](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/discussions/) for questions and support
- [Gitter.im](https://gitter.im/FINANCE-ME-iii/FINANCE-ME-iii) for a good chat and a quick answer
- [GitHub Issues](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/issues) for bugs and issues
- <a rel="me" href="https://fosstodon.org/@ff3">Mastodon</a> for news and updates

<!-- END OF HELP TEXT -->


## Acknowledgements

Over time, [many people have contributed to FINANCE-ME III](https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/graphs/contributors). I'm grateful for their support and code contributions.

The FINANCE-ME III logo is made by the excellent Cherie Woo.

<a href="https://hellogithub.com/repository/a8c64f04cb3643c2a4423c4ad924dec9" target="_blank"><img src="https://abroad.hellogithub.com/v1/widgets/recommend.svg?rid=a8c64f04cb3643c2a4423c4ad924dec9&claim_uid=1bPi7O2rTGREZXN&theme=small" alt="Featured｜HelloGitHub" /></a>

[packagist-shield]: https://img.shields.io/packagist/v/grumpydictator/FINANCE-ME-iii.svg?style=flat-square
[packagist-url]: https://packagist.org/packages/grumpydictator/FINANCE-ME-iii
[license-shield]: https://img.shields.io/github/license/FINANCE-ME-iii/FINANCE-ME-iii.svg?style=flat-square
[license-url]: https://www.gnu.org/licenses/agpl-3.0.html
[stars-shield]: https://img.shields.io/github/stars/FINANCE-ME-iii/FINANCE-ME-iii.svg?style=flat-square
[stars-url]: https://github.com/FINANCE-ME-iii/FINANCE-ME-iii/stargazers
[donate-shield]: https://img.shields.io/badge/donate-%24%20%E2%82%AC-brightgreen?style=flat-square
[donate-url]: #support-the-development-of-FINANCE-ME-iii
[build-shield]: https://api.travis-ci.com/FINANCE-ME-iii/FINANCE-ME-iii.svg?branch=master
[build-url]: https://travis-ci.com/github/FINANCE-ME-iii/FINANCE-ME-iii
[sc-gate-shield]: https://sonarcloud.io/api/project_badges/measure?project=FINANCE-ME-iii_FINANCE-ME-iii&metric=alert_status
[sc-bugs-shield]: https://sonarcloud.io/api/project_badges/measure?project=FINANCE-ME-iii_FINANCE-ME-iii&metric=bugs
[sc-smells-shield]: https://sonarcloud.io/api/project_badges/measure?project=FINANCE-ME-iii_FINANCE-ME-iii&metric=code_smells
[sc-vuln-shield]: https://sonarcloud.io/api/project_badges/measure?project=FINANCE-ME-iii_FINANCE-ME-iii&metric=vulnerabilities
[sc-project-url]: https://sonarcloud.io/dashboard?id=FINANCE-ME-iii_FINANCE-ME-iii
[bp-badge]: https://bestpractices.coreinfrastructure.org/projects/6335/badge
[bp-url]: https://bestpractices.coreinfrastructure.org/projects/6335 
