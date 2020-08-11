---
title: Atttack Surfaces
layout: col-sidebar
tab: true
order: 1
tags: GSF, game-attack-surface, gamesec
---

## Game Security Vulnerabilities

The Security Vulnerabilities Project provides information on what types of vulnerabilities exist within games, and which attack surfaces they fall under. 

The following is a list of the vulnerabilities that can be found in video games of various types, and the attack surfaces they're likely to be associated with.

<!--TODO: find a better way to create these tables / lists in markdown, embedding the HTML
    into the markdow table like this is very unmaintainable... -->
| Attack Surface | Vulnerability Name |
| -------------- | ------------------ |
| Local Game Client | <ul><li>Ability to edit in-game resources</li><li>Ability to bypass license requirement</li></ul>
| Game Network Traffic | <ul><li>Network Denial of Service (Player)<ul><li>Player bandwidth exhaustion</li><li>Player game client resource exhaustion</li></ul></ul> |
| Game Application Traffic | <ul><li>Application Level Denial of Service (Player)<ul><li>Player application logic Denial of Service</li></ul></ul>
| Game Server | <ul><li>Application Level Denial of Service (Server)<ul><li>Server application logic Denial of Service</li></ul><li>Ability to modify game ladder rankings</li><li>Ability to modify own player resources</li></ul> |
| Game Economy | <ul><li>Ability to generate unlimited money on client side</li><li>Ability to generate unlimited money through network/application traffic modification</li><li>Ability to modify prices for in-game items</li><li>Ability to replay financial actions such as buying or selling through network/application manipulation</li> |