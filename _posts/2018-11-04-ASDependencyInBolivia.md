---
layout: post
title: D008 - dependency between AS in Bolivia
description: Dependency between autonomous systems which manage IPv4 prefixes assigned to Bolivian entities
date: 2018-11-04 8:00:04 -0400
---

Traceroute from a machine located inside the Entel autonomous system (6568) to the first possible IPv4 address of every prefix assigned to a Bolivian entity (ie. `traceroute 45.4.98.1` for the prefix "45.4.98.0/23"), measured on 4 Nov 2018 (see the [20181103_dependencias_as_bolivia code repository](https://framagit.org/severo/20181103_dependencias_as_bolivia) to create data from another viewpoint).

|          |                                                    |
| -------- | -------------------------------------------------- |
| Copy URL | `{{ 'data/D008/traceroute.json' | absolute_url }}` |
| Download | [JSON]({{ 'data/D008/traceroute.json'              | relative_url }}) |

List of the autonomous systems seen in the traceroutes, with their name.

|          |                                            |
| -------- | ------------------------------------------ |
| Copy URL | `{{ 'data/D008/as.json' | absolute_url }}` |
| Download | [JSON]({{ 'data/D008/as.json'              | relative_url }}) |
