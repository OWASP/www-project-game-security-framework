---

layout: col-sidebar
title: OWASP game security framework
tags: example-tag
level: 0
type: documentation

auto-migrated: 1
---

This is an example of a Project or Chapter Page.
# About the Project

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<td><h2 id="owasp_game_security_framework_gsf">OWASP Game Security Framework (GSF)</h2>
<p><strong>The OWASP Game Security Framework (GSF) represents a modular approach to understanding the security issues that surround video game ecosystems.</strong></p>
<p><strong>The OWASP Game Security Framework (GSF) represents a modular approach to understanding the security issues that surround video game ecosystems.</strong></p>
<p>In 2016 the videogame market became 99.6 Billion dollar industry... any why shouldn't it be? Some of the most prolific and complex software developed today are video games. They are professionally played, sponsored, scrutinized, monetized, and celebrated, just like many sports. They handle clients, servers, web components, monetary transfers, social interactions, virtual markets, etc, with every bit the need of security that most internet hosted apps have (if not more in some cases). The GSF is designed to help threat model gaming issues that have devastated new games. Most importantly we hope the GSF can help new developers and security testers alike root out bugs in your favorite titles.</p>
<p>In 2016 the videogame market became 99.6 Billion dollar industry... any why shouldn't it be? Some of the most prolific and complex software developed today are video games. They are professionally played, sponsored, scrutinized, monetized, and celebrated, just like many sports. They handle clients, servers, web components, monetary transfers, social interactions, virtual markets, etc, with every bit the need of security that most internet hosted apps have (if not more in some cases). The GSF is designed to help threat model gaming issues that have devastated new games. Most importantly we hope the GSF can help new developers and security testers alike root out bugs in your favorite titles.</p>
<p><em>The framework is broken into three main concepts / sections:</em></p>
<p><em>The framework is broken into three main concepts / sections:</em></p>
<p><strong>1. Identifying and clustering the components of risk within the overall game security space, and then giving instances of each component.</strong></p>
<p><strong>1. Identifying and clustering the components of risk within the overall game security space, and then giving instances of each component.</strong></p>
<p><em>Components include the following:</em></p>
<p><em>Components include the following:</em></p>
<ul>
<ul>
<li><strong>Attack Surfaces</strong>: the various surface areas that can be attacked by attackers in order to cause harm to the gaming ecosystem.</li>
<li><strong>Attack Surfaces</strong>: the various surface areas that can be attacked by attackers in order to cause harm to the gaming ecosystem.</li>
</ul>
</ul>
<ul>
<ul>
<li><strong>Vulnerabilities</strong>: the specific weaknesses in design or implementation that allows attackers to successfully target a given game.</li>
<li><strong>Vulnerabilities</strong>: the specific weaknesses in design or implementation that allows attackers to successfully target a given game.</li>
</ul>
</ul>
<ul>
<ul>
<li><strong>Attacker Goals</strong>: a list of the reasons that an attacker might want to attack a given game.</li>
<li><strong>Attacker Goals</strong>: a list of the reasons that an attacker might want to attack a given game.</li>
</ul>
</ul>
<ul>
<ul>
<li><strong>Negative Outcomes</strong>: a collection of ways that the gaming company could ultimately be impacted negatively by attacks to its game and associated infrastructure.</li>
<li><strong>Negative Outcomes</strong>: a collection of ways that the gaming company could ultimately be impacted negatively by attacks to its game and associated infrastructure.</li>
</ul>
</ul>
<p><strong>2. A natural language semantic structure for thinking about and articulating game security issues, which uses the modular risk components as sentence structure.</strong></p>
<p><strong>2. A natural language semantic structure for thinking about and articulating game security issues, which uses the modular risk components as sentence structure.</strong></p>
<p><em>Example:</em></p>
<p><em>Example:</em></p>
<dl>
<dl>
<dt></dt>
<dt></dt>
<dd>"The attacker attacked and edited the <code>LOCAL GAME CLIENT (Attack Surface)</code>, which had a <code>LACK OF CLIENT INTEGRITY CONTROLS (Vulnerability)</code>, which allowed her to <code>ARTIFICIALLY INCREASE HER ABILITIES (Attacker Goal)</code>, ultimately leading to an <code>UNHAPPY PLAYER BASE (Negative Outcome)</code> and <code>DECLINING GAME REVENUE (Negative Outcome)</code> , which could have been prevented by <code>DEFENSE.</code>”
<dd>"The attacker attacked and edited the <code>LOCAL GAME CLIENT (Attack Surface)</code>, which had a <code>LACK OF CLIENT INTEGRITY CONTROLS (Vulnerability)</code>, which allowed her to <code>ARTIFICIALLY INCREASE HER ABILITIES (Attacker Goal)</code>, ultimately leading to an <code>UNHAPPY PLAYER BASE (Negative Outcome)</code> and <code>DECLINING GAME REVENUE (Negative Outcome)</code> , which could have been prevented by <code>DEFENSE.</code>”
</dd>
</dd>
</dl>
</dl>
<p>Using this structure, security testers can clearly communicate the various aspects of a game security issue to many different types of stakeholder—from pentesting peers to business executives in the gaming industry.</p>
<p>Using this structure, security testers can clearly communicate the various aspects of a game security issue to many different types of stakeholder—from pentesting peers to business executives in the gaming industry.</p>
<p><strong>3. Examples of real-world examples of previous attacks against games, and how the attacks map to the GSF framework components.</strong></p>
<p><strong>3. Examples of real-world examples of previous attacks against games, and how the attacks map to the GSF framework components.</strong></p>
<h2 id="licensing">Licensing</h2>
<h2 id="licensing">Licensing</h2>
<p>The OWASP Game Security Framework is free to use. It is licensed under the <a href="http://creativecommons.org/licenses/by-sa/3.0/">http://creativecommons.org/licenses/by-sa/3.0/</a> Creative Commons Attribution-ShareAlike 3.0 license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.</p></td>
<p>The OWASP Game Security Framework is free to use. It is licensed under the <a href="http://creativecommons.org/licenses/by-sa/3.0/">http://creativecommons.org/licenses/by-sa/3.0/</a> Creative Commons Attribution-ShareAlike 3.0 license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.</p></td>
<p>The goal of the OWASP Game Security Framework is to provide a structure for discussing the various aspects around the security of video games.</p>
<p>The target audience for the project includes:</p>
<ul>
<li>Gamers</li>
<li>QA</li>
<li>Game designers</li>
<li>Penetration testers</li>
<li>Gaming executives</li>
<li>Anyone else with a vested interest in game security</li>
</ul>
<h2 id="project_leaders">Project Leaders</h2>
<ul>
<li>Jason Haddix</li>
<li>Daniel Miessler</li>
</ul>
<h2 id="contributors">Contributors</h2>
<ul>
<li>Kevin Hemmingsen</li>
<li>Troy Cunefare</li>
<li>Ryan Lawrence</li>
<li>Martin Mendoza</li>
<li>Koray Algan</li>
<li>Tom Simkovic</li>
<li>Matt Espinoza</li>
<li>Chad Lynch</li>
</ul>
<h2 id="related_projects">Related Projects</h2>
<ul>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
</ul></td>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="quick_download">Quick Download</h2>
<p>COMING SOON</p>
<h2 id="news_and_events">News and Events</h2>
<ul>
<li>January, 2017: Doing a complete redesign of the project.</li>
<li>March 2017: Presenting version 1.0 at HouSecCon 2017.</li>
</ul>
<h2 id="classifications">Classifications</h2>
<table>
<tbody>
<tr class="odd">
<img src="Owasp-incubator-trans-85.png" title="Owasp-incubator-trans-85.png" alt="Owasp-incubator-trans-85.png" /><figcaption>Owasp-incubator-trans-85.png</figcaption>
</figure></td>
<img src="Owasp-builders-small.png" title="Owasp-builders-small.png" alt="Owasp-builders-small.png" /><figcaption>Owasp-builders-small.png</figcaption>
</figure></td>
</tr>
<tr class="even">
<img src="Owasp-defenders-small.png" title="Owasp-defenders-small.png" alt="Owasp-defenders-small.png" /><figcaption>Owasp-defenders-small.png</figcaption>
</figure></td>
</tr>
<tr class="odd">
<img src="Cc-button-y-sa-small.png" title="Cc-button-y-sa-small.png" alt="Cc-button-y-sa-small.png" /><figcaption>Cc-button-y-sa-small.png</figcaption>
</figure></td>
</tr>
<tr class="even">
<img src="Project_Type_Files_DOC.jpg" title="Project_Type_Files_DOC.jpg" alt="Project_Type_Files_DOC.jpg" /><figcaption>Project_Type_Files_DOC.jpg</figcaption>
</figure></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

# Attack Surfaces

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>The following is a list of the attack surfaces that can be found in video games of various types.</p>
<table>
<thead>
<tr class="header">
<th><p>Attack Surface</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
</tbody>
</table></td>
<p>This section provides an overview of the various places an attacker can target to harm a given game infrastructure.</p>
<h2 id="sub_project_leader">Sub-project Leader</h2>
<ul>
<li>Daniel Miessler</li>
</ul>
<h2 id="related_projects_1">Related Projects</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/OWASP_Mobile_Security_Project">The OWASP Mobile Top 10 Project</a></li>
<li><a href="https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project">The OWASP Web Top 10 Project</a></li>
</ul>
<h2 id="collaboration_1">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="quick_download_1">Quick Download</h2>
<ul>
<li>Coming Soon</li>
</ul>
<h2 id="news_and_events_1">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Vulnerabilities

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>The following is a list of the vulnerabilities that can be found in video games of various types, and the attack surfaces they're likely to be associated with.</p>
<table>
<thead>
<tr class="header">
<th><p>Attack Surface</p></th>
<th><p>Vulnerability Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<li>Ability to edit in-game resources</li>
<li>Ability to bypass license requirement</li>
</ul></td>
</tr>
<tr class="even">
<li>Network Denial of Service (player)
<ul>
<li>Player bandwidth exhaustion</li>
<li>Player game client resource exhaustion</li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<li>Application Level Denial of Service (Player)
<ul>
<li>Player application logic Denial of Service</li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<li>Application Level Denial of Service (Server)
<ul>
<li>Server application logic Denial of Service</li>
</ul></li>
<li>Ability to modify game ladder rankings</li>
<li>Ability to modify own player resources</li>
</ul></td>
</tr>
<tr class="odd">
<li>Ability to generate unlimited money on client side</li>
<li>Ability to generate unlimited money through network/application traffic modification</li>
<li>Ability to modify prices for in-game items</li>
<li>Ability to replay financial actions such as buying or selling through network/application manipulation</li>
</ul></td>
</tr>
<tr class="even">
</tr>
</tbody>
</table></td>
<p>The Security Vulnerabilities Project provides information on what types of vulnerabilities exist within games, and which attack surfaces they fall under.</p>
<h2 id="sub_project_leader_1">Sub-project Leader</h2>
<ul>
<li>Jason Haddix</li>
</ul>
<h2 id="related_projects_2">Related Projects</h2>
<ul>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
</ul>
<h2 id="collaboration_2">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="resources">Resources</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/Top_IoT_Vulnerabilities">Top 10 IoT Vulnerabilities from 2014</a></li>
</ul>
<h2 id="news_and_events_2">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Exploits

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>This list refers to what a given attacker might use to take advantage of a given bug within the game.</p>
<table>
<thead>
<tr class="header">
<th><p>Exploit</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
</tbody>
</table></td>
<p>The Exploits provides information on what types of tools and techniques an attacker might use to accomplish his/her goal.</p>
<h2 id="sub_project_leader_2">Sub-project Leader</h2>
<ul>
<li>Daniel Miessler</li>
</ul>
<h2 id="related_projects_3">Related Projects</h2>
<ul>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
</ul>
<h2 id="collaboration_3">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="resources_1">Resources</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/Top_IoT_Vulnerabilities">Top 10 IoT Vulnerabilities from 2014</a></li>
</ul>
<h2 id="news_and_events_3">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Attacker Goals

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>This list refers to what a given attacker might be trying to accomplish within the game by performing a given attack. This could relate very closely (or not) with the technical impact or business impact cause by the behavior.</p>
<table>
<thead>
<tr class="header">
<th><p>Attacker Goal</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
</tbody>
</table></td>
<p>The Attacker Goals Project provides information on what types of outcomes attackers might try to achieve within or outside of the game they're attacking.</p>
<h2 id="sub_project_leader_3">Sub-project Leader</h2>
<ul>
<li>Daniel Miessler</li>
</ul>
<h2 id="related_projects_4">Related Projects</h2>
<ul>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
</ul>
<h2 id="collaboration_4">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="resources_2">Resources</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/Top_IoT_Vulnerabilities">Top 10 IoT Vulnerabilities from 2014</a></li>
</ul>
<h2 id="news_and_events_4">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Negative Outcomes

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>The following is a list of possible negative outcomes that can occur as the result of someone successfully attacking a given game.</p>
<table>
<thead>
<tr class="header">
<th><p>Outcomes</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
</tbody>
</table></td>
<p>The Negative Outcomes Project provides information on what types of situations could manifest within the game if bugs or exploits are not successfully addressed.</p>
<h2 id="project_leader">Project Leader</h2>
<ul>
<li>Daniel Miessler</li>
</ul>
<h2 id="related_projects_5">Related Projects</h2>
<ul>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
</ul>
<h2 id="collaboration_5">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="resources_3">Resources</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/Top_IoT_Vulnerabilities">Top 10 IoT Vulnerabilities from 2014</a></li>
</ul>
<h2 id="news_and_events_5">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Defenses

<div style="width:100%;height:160px;border:0,margin:0;overflow: hidden;">

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg
"OWASP_Project_Header.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>These are some of the common defenses that can be used to counter attacks against various components of a game.</p>
<table>
<thead>
<tr class="header">
<th><p>Outcomes</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
</tbody>
</table></td>
<p>The Security Vulnerabilities Project provides information on what types of vulnerabilities exist within games, and which attack surfaces they fall under.</p>
<h2 id="project_leaders_1">Project Leaders</h2>
<ul>
<li>Daniel Miessler</li>
</ul>
<h2 id="related_projects_6">Related Projects</h2>
<ul>
<li><a href="OWASP_Mobile_Security_Project" title="wikilink">OWASP Mobile Security</a></li>
<li><a href="OWASP_Top_Ten_Project" title="wikilink">OWASP Web Top 10</a></li>
</ul>
<h2 id="collaboration_6">Collaboration</h2>
<p><a href="https://game-security.slack.com">The Slack Channel</a></p>
<h2 id="resources_4">Resources</h2>
<ul>
<li><a href="https://www.owasp.org/index.php/Top_IoT_Vulnerabilities">Top 10 IoT Vulnerabilities from 2014</a></li>
</ul>
<h2 id="news_and_events_6">News and Events</h2>
<ul>
<li>Coming Soon</li>
</ul></td>
</tr>
</tbody>
</table>

# Examples

## Real-world Examples of Gaming Vulnerabilities

*Vulnerability*

| ID  | style="font-weight: bold;"                          | Vulnerabilty Name                                                                                                                                                                                                                                                                                                                                                                                                                               | style="font-weight: bold;" | Description             | style="font-weight: bold;" | Surface Area                | style="font-weight: bold;"                    | Goal                                                                                            | style="font-weight: bold;" | Techical Impact | Business Impact | style="font-weight: bold;" | Defense | Ref | Game | Genre |
| --- | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- | ----------------------- | -------------------------- | --------------------------- | --------------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------- | --------------- | --------------- | -------------------------- | ------- | --- | ---- | ----- |
| V1  | Local Resource Modification, Client-side Logic Flaw | In 2015 The Division experienced an exploit that allowed an attacker to switch weapons rapidly, applying weapon buffs in a stacking manner, with no cap.                                                                                                                                                                                                                                                                                        | Game Client                | Unfair Player Advantage | Player Anger               | Players leave, Lost Revenue | Cryptographic Integrity Checks on Game Client | <http://www.gamesradar.com/theres-a-division-damage-stacking-glitch-if-youve-got-fast-fingers/> |                            | 3PS/1PS/MMO     |                 |                            |         |     |      |       |
| VN1 | colspan="10" style="text-align: center;"            | "The attacker attacked and edited the `LOCAL GAME CLIENT (Attack Surface)`, which had a `LACK OF CLIENT INTEGRITY CONTROLS (Vulnerability)`, which allowed her to `ARTIFICIALLY INCREASE HER ABILITIES (Attacker Goal)`, ultimately leading to an `UNHAPPY PLAYER BASE (Negative Outcome)` and `DECLINING GAME REVENUE (Negative Outcome)` due to cheating, which could have been prevented by `CRYPTOGRAPHIC INTEGRITY CHECKS ON GAME CLIENT`” |                            |                         |                            |                             |                                               |                                                                                                 |                            |                 |                 |                            |         |     |      |       |
|     |                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                            |                         |                            |                             |                                               |                                                                                                 |                            |                 |                 |                            |         |     |      |       |
|     |                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                            |                         |                            |                             |                                               |                                                                                                 |                            |                 |                 |                            |         |     |      |       |
|     |                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                            |                         |                            |                             |                                               |                                                                                                 |                            |                 |                 |                            |         |     |      |       |
|     |                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                            |                         |                            |                             |                                               |                                                                                                 |                            |                 |                 |                            |         |     |      |       |

*Working Data Collection Spreadsheet:*

<https://docs.google.com/spreadsheets/d/1Og08wyHsqtODBDkU_M2zHAvdxc63GSu-OmT8NjCc9Ak/edit#gid=0>

  -

# Community

We are actively looking for people to help in the following areas:

  - Improving the framework schema, e.g., vulns, attack surfaces,
    technical impacts, business impacts, defenses, etc.
  - Adding content to any of the various sections
  - Input from avid gamers on how useful this is to them
  - Input from app security experts
  - Input from security types working at gaming companies
  - Input from game company business types

If you have interest in helping, reach out to us and we'll make you a
contributor.

# Testing Tools

## Commonly Used Game Hacking Tools

# Project About

__NOTOC__ <headertabs></headertabs>

[Category:OWASP_Project](Category:OWASP_Project "wikilink")
[Category:OWASP_Document](Category:OWASP_Document "wikilink")
[Category:OWASP_Download](Category:OWASP_Download "wikilink")
[Category:OWASP_Release_Quality_Document](Category:OWASP_Release_Quality_Document "wikilink")
