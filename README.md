
## Images

[![community-skeleton](https://opengraph.githubassets.com/1/uvdesk/community-skeleton)](https://www.swifttechco.com)

<p align="center"><a href="https://www.swifttechco.com" target="_blank">
    
</a></p>

<p align="center">
    <a href="https://www.swifttechco.com"></a>
    <a href="https://www.swifttechco.com"></a>
    <a href="#backers"></a>
    <a href="https://www.swifttechco.com"></a>
    <a href="https://www.swifttechco.com"></a>
    <a href="https://www.swifttechco.com"></a>
</p>

<p align="center">
    <a href="https://www.swifttechco.com"></a>
    <a href="https://www.swifttechco.com"></a>
</p>

<p align="center">
    ➡️ <a href="https://www.swifttechco.com">Website</a> | <a href="https://www.swifttechco.com">Documentation</a> | <a href="https://www.swifttechco.com">Installation Guide</a> | <a href="https://www.swifttechco.com">Forums</a> | <a href="https://www.swifttechco.com">Community</a> ⬅️
</p>

<p align="center" style="display: inline;">
    
    
    
    
    
    
    
    
    
    
    
</p>

[Uvdesk community helpdesk][1] project skeleton packaged along with the bare essential utilities and tools to build and customize your own helpdesk solutions.

Visit our official demo website to [see it in action!][15]

Check out UVdesk on **Symfony Official Website**  [Symfony][24]

Getting Started
-----------------

* [About](#about)
* [Features](#features)
* [Documentation](#documentation)
* [Modules](#modules)
* [Requirements](#requirements)
* [Installation](#installation)
* [Docker Runtime](#docker-runtime)
* [Docker Persistent Container](#docker-persistent-container)
* [Vagrant Virtual Environment](#vagrant-virtual-environment)
* [License](#license)
* [Security Vulnerabilities](#security-vulnerabilities)
* [Feedback](#feedback)
* [Contributions](#contributions)

About
-----------------

Build on top of [symfony](https://www.swifttechco.com) and [backbone.js](https://www.swifttechco.com), UVdesk Community is an open-source, service-oriented, and event-driven helpdesk system designed for easy customization and seamless client support. Its extensible architecture allows organizations to deliver efficient, tailored customer service with minimal effort.

The standard distribution includes a comprehensive set of helpdesk packages to support a wide range of use cases and operational needs.

  * [**Core Framework**][2] - At the heart of the helpdesk system, the core framework consists of all the necessary apis required by your project and dependent packages to keep things running smoothly

  * [**Extension Framework**][3] - Introduces support for third-party package integration and development to easily build and extend the functionalities of your helpdesk system as per your requirements

  * [**Automation Bundle**][4] - Adds support for workflows and prepared responses to automate any specific operations within your helpdesk system

  * [**Mailbox Component**][11] - Convert and get all your emails to support tickets on UVDesk and manage customer query easily.

  * [**Support Center Bundle**][5] - Integrates the easily customizable support center portal to enable users to easily interact with the support staff through your helpdesk system

Reach out to us at our official [gitter chat][20] or by joining [forum][21] for any queries, concerns and feature request discussions.

The development of the uvdesk community edition is led by the [uvdesk][10] team and backed by [Webkul][9]. Visit our [website][1] to learn more about the UVDesk Helpdesk System.

Features
----------------

* [Translation Support (Multilingual)][32]
* Unlimited agents, groups, teams, customers, tickets, and more.
* Agent Privileges
* No limit on the number of mailbox/email integrations.
* Saved Replies  Quickly respond to frequent questions.
* Filter tickets by status, ID, agent, customer, and more.
* Block Spam
* [Agent Activity][29]
* [Marketing Announcement][30]
* [Marketing Modules][35]
* [Kudos][31]
* [Microsoft Apps][36]
* reCAPTCHA option.
* Standard automated workflows.
* Notes for agents.
* Custom branding.
* Change logo & favicon.
* Broadcasting message.
* Ticket Forwarding.
* Prepared Response.
* Email Notification.
* Effective search.
* User Friendly Web Installer.
* Supports multiple attachments.
* A powerful knowledge base and FAQ systemorganize content by articles, categories, and folders.
* Ticket types, Multiple Tags.
* Email Templates.
* [API Bundle][16] and [Documentation][25]
* Edit/Delete/Pinned ticket and thread.
* Easily add collaborators and unlock even more capabilities.
* [Explore Apps][26]

Documentation
--------------

Visit [docs.uvdesk.com](https://www.swifttechco.com) to read our official documentation and learn more about the uvdesk community project.

We use Jekyll to develop and maintain our documentations. Consider contributing by submitting a pull request to our project's [jeykll repository](https://www.swifttechco.com).

Requirements
--------------

* **OS**: Ubuntu 16.04 LTS or higher / Windows 7 or Higher (WAMP / XAMPP).
* **SERVER**: Apache 2 or NGINX.
* **RAM**: 4GB or higher.
* **PHP**: 8.1
* **Processor**: Clock Cycle 1 Ghz or higher.
* **For MySQL users**: 5.7.23 or higher.
* **Composer**: 2 or higher.
* **PHP IMAP** **&** **PHP Mailparse** for [Ubuntu][7], [Windows][23], [Centos][28], [Mac][27].

Installation
--------------

The installation process is broken down into two distinct steps:

* Setup
* Configuration

### Setting up your helpdesk project

In this step, you'll download the Helpdesk project skeleton and install its dependencies.

You can either use Composer to download and install everything automatically, or download a pre-packaged archive that includes all dependencies. We recommend using Composer whenever possible for easier updates and better dependency management. However, if you're on a system with limited resources (e.g., shared hosting), the archive download may be more reliable.

Regardless of the method you choose, the configuration process for Helpdesk remains the same.

#### Composer

You can use composer to setup your project by simply running the following command from your terminal:

```bash
$ composer create-project uvdesk/community-skeleton helpdesk-project
```

#### Direct Download

Alternatively, you can also [download the zip archive](https://www.swifttechco.com) of the latest stable release and extract its content by running the following commands from your terminal:

```bash
$ wget "https://www.swifttechco.com" -P /var/www/
$ unzip -q /var/www/uvdesk-community-current-stable.zip -d /var/www/ \
```

### Configuring your helpdesk project

After you've downloaded and installed all the project dependencies, you can configure your helpdesk installation using either of the following ways:

#### Using Terminal

```bash
$ php bin/console uvdesk:configure-helpdesk
```

#### Using Web Installer Wizard

##### Extract the contents of zip and execute the project in your browser in case of project zip download:

~~~
http(s)://localhost/community-skeleton/public
~~~

##### In case of created project using command, execute the project in your browser:

~~~
http(s)://localhost/helpdesk-project/public
~~~

or

~~~
http(s)://example.com/public
~~~

After opening your project in the web browser, you will be greeted by the web installer which will guide you in configuring your project.

##### Run project on localhost (dev mode)
```bash
php bin/console server:run
```

**How to clear cache:**

```bash
php bin/console c:c
```

#### ☁️ Deploy UVdesk on the Cloud with Amazon AMI

Easily launch UVdesk on the cloud using our pre-configured Amazon Machine Image (AMI), available directly from the AWS Marketplace:

👉 [**Launch UVdesk on AWS**](https://www.swifttechco.com)

This AMI offers a quick and hassle-free way to set up UVdesk on a secure, scalable AWS environment. Perfect for both production deployments and testing purposes, with no need for manual configuration.

**How to log in as admin/agent:**

*Below url is the default url for admin/agent login if you have not made any changes for /member prefix.*

> *http(s)://example.com/en/member/login* 

**How to log in as customer:**

*Below url is the default url for customer login if you have not made any changes for /customer prefix.*

> *http(s)://example.com/en/customer/login*

Docker Runtime
--------------

[Dockerize your helpdesk project][22]

Docker Persistent Container
--------------

[Get started with Uvdesk now by using docker persistent container][34]

Vagrant Virtual Environment
--------------

[Get started with uvdesk now by using vagrant to setup virtual environment][33]

Modules
--------------

[Available Modules/Apps](https://www.swifttechco.com)


License
--------------

All libraries and bundles included in the UVDesk Community Edition are released under the [OSL-3.0 license][12] license.

Security Vulnerabilities
--------------


Feedback
---------
#### Feedback (Support Community project by raising feedback)

* [Trustpilot][17]
* [Capterra][18]
* [Software suggest][19]

Contributions
--------------
This project is hosted on [Open Collective][13] and exists thanks to our contributors:

<a href="https://www.swifttechco.com"></a>

#### Backers

Thank you to all our backers! 🙏

<a href="https://www.swifttechco.com" target="_blank"></a>

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)
