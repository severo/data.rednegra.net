---
layout: post
title: D012 - dependency between AS in Bolivia as seen from Tigo
description: Dependency between autonomous systems which manage IPv4 prefixes assigned to Bolivian entities, as seen from Tigo/Telecel network
date: 2018-11-12 8:00:04 -0400
---

Traceroute on 12 Nov 2018 from a machine located inside the Tigo / Telecel autonomous system (27882) to the first possible IPv4 address of every prefix assigned to a Bolivian entity (ie. `traceroute 45.4.98.1` for the prefix "45.4.98.0/23"), measured on 4 Nov 2018 (see the [20181103_dependencias_as_bolivia code repository](https://framagit.org/severo/20181103_dependencias_as_bolivia) to create data from another viewpoint). The code used to realize the measurements is available in a [public repository](https://framagit.org/severo/20181103_dependencias_as_bolivia).

|          |                                                    |
| -------- | -------------------------------------------------- |
| Copy URL | `{{ 'data/D012/traceroute.json' | absolute_url }}` |
| Download | [JSON]({{ 'data/D012/traceroute.json'              | relative_url }}) |

List of the autonomous systems seen in the traceroutes, with their name.

|          |                                            |
| -------- | ------------------------------------------ |
| Copy URL | `{{ 'data/D012/as.json' | absolute_url }}` |
| Download | [JSON]({{ 'data/D012/as.json'              | relative_url }}) |
