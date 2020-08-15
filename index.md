---

layout: col-sidebar
title: OWASP Game Security Framework
tags: example-tag
level: 0
type: documentation

auto-migrated: 1
auto-migrated: 1

---


<!-- Standard Chapter Page Template
This is an example of a Project or Chapter page.
Please change these items to indicate the actual information you wish to present. In addition to this information, the 'front-matter' above the text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

{front matter for this file}

```
- layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar
- title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore
- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 
- region: This is the region you are in according to our data
```

{copy for this file (index.md)}
Replace the text above the commented area with your information in the format below:
```
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Local News
- Meeting Location
- Everyone is welcome to join us at our chapter meetings.

```
{info.md}

This separate file is where you should place links to your Google Group and Meetup page. It will be automatically rendered in the column sidebar.

{leaders.md}

Another separate file that should simply include each leaders name with mailto link as a list. It will also be automatically rendered in the column sidebar.

-->


## OWASP Game Security Framework (GSF)

The OWASP Game Security Framework (GSF) represents a modular approach to understanding the security issues that surround video game ecosystems.

In 2016 the videogame market became 99.6 Billion dollar industry... any why shouldn't it be? Some of the most prolific and complex software developed today are video games. They are professionally played, sponsored, scrutinized, monetized, and celebrated, just like many sports. They handle clients, servers, web components, monetary transfers, social interactions, virtual markets, etc, with every bit the need of security that most internet hosted apps have (if not more in some cases). The GSF is designed to help threat model gaming issues that have devastated new games. Most importantly we hope the GSF can help new developers and security testers alike root out bugs in your favorite titles.

The framework is broken into three main concepts / sections:

### 1. Identifying and clustering the components of risk within the overall game security space, and then giving instances of each component.

Components include the following:

- Attack Surfaces: the various surface areas that can be attacked by attackers in order to cause harm to the gaming ecosystem.
- Vulnerabilities: the specific weaknesses in design or implementation that allows attackers to successfully target a given game.
- Attacker Goals: a list of the reasons that an attacker might want to attack a given game.
- Negative Outcomes: a collection of ways that the gaming company could ultimately be impacted negatively by attacks to its game and associated infrastructure.

### 2. A natural language semantic structure for thinking about and articulating game security issues, which uses the modular risk components as sentence structure.

#### Example:

> "The attacker attacked and edited the `LOCAL GAME CLIENT (Attack Surface)`, which had a `LACK OF CLIENT INTEGRITY CONTROLS (Vulnerability)`, which allowed her to `ARTIFICIALLY INCREASE HER ABILITIES (Attacker Goal)`, ultimately leading to an `UNHAPPY PLAYER BASE (Negative Outcome)` and `DECLINING GAME REVENUE (Negative Outcome)`, which could have been prevented by `DEFENSE`."

Using this structure, security testers can clearly communicate the various aspects of a game security issue to many different types of stakeholder—from pentesting peers to business executives in the gaming industry.

### 3. Examples of real-world examples of previous attacks against games, and how the attacks map to the GSF framework components.

## Licensing
The OWASP Game Security Framework is free to use. It is licensed under the http://creativecommons.org/licenses/by-sa/3.0/ Creative Commons Attribution-ShareAlike 3.0 license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.