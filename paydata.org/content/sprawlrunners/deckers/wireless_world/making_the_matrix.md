---
title: Making the Matrix
linkTitle: Making the Matrix
type: docs
description: "What the Matrix is made of: the backbone and the local mesh; hosts and other icons"
date: 2020-11-21
lastmod: 2020-12-22
weight: 100
---

The third-generation Matrix of the 2070s is a technological marvel, delivering immersive AR and VR applications to users without the need for wires. But how does it manage such fast connections without requiring the user to physically connect a cable? The answer comes in two parts.

{{% alert title="Notes" %}}
*The design intent here is to keep deckers close to the action by tying their hacking activities to a short-range mesh network.*
{{% /alert %}} 

## The backbone

The first part is the *global grid*, also known colloquially as **the backbone**. This is broadly equivalent to what was known in the early 21st century as "the cloud"; it's the sum of all the physical infrastructure of fibre trunks, satellite uplinks, and other super-speed connections that connect all the Matrix's hosts together. Within the backbone, speed is functionally infinite, and distance is no issue. But you can only use the backbone if you have a physical, wired connection to it. Nobody wants that.

Early 21st century cellular wireless standards are no help. The Matrix demands very fast high-frequency ultra-wideband radios, but they are easily blocked by the gleaming steel-and-glass towers of the sprawl. You'd never get a signal. How to square this circle? 

## The local mesh

The answer is a *short range, peer-to-peer mesh network*. Suppose Alice wants to check the latest updates on her P2.1 social feed. Her commlink sends the request to her neighbour Bob's commlink. From there, it's forwarded to Charlie's commlink. And so it travels, until it reaches an *uplink host* - which has a hardline connection to the backbone. From there, it can speed off to its final destination. The P2.1 host sees the request, and sends the response back down the same link. This all happens in the blink of an eye.

Every Matrix device automatically self-organises itself into a reliable mesh network, and sets up forwarding and routing so that everything transparently works. This is the **local mesh**. At all times, your Matrix devices exist in a bubble, extending perhaps a hundred meters around you. Somewhere in that bubble is your closest uplink host, the one you will send backbone traffic to. But where is your traffic going? Well, for most people, it's usually a host.

## Hosts

Hosts come in a few major types, depending on what kind of connection they have.

First, there are the aforementioned **uplink hosts**, sometimes called *beanstalks*. These bridge between the backbone and the local mesh, a bit like an old-time cell tower. People don't really think about them too much; like any piece of reliable infrastructure, they fade into the background. But they're there, scattered around the sprawl.

The most common type people interact with in their personal lives are **cloud hosts**. These are hosts made up of many physical servers distributed around the planet, all with their own connection to the backbone. They exist everywhere and nowhere at once. Cloud hosts are very powerful and very secure.

However, you can't use cloud hosts for everything. When Wally Wageslave sits working in his office like a good little drone, that office's various systems - heat, light, power, security, Wally's files and emails - are all run by a host located inside the building. These **local hosts** work exclusively on the local mesh, without a backbone connection. Local hosts have one defined place of existence; somewhere, there's some computers in a rack you can point to and say "this is the host for this building." 

Some of the more prominent and successful hacker collectives might run illicit local hosts, sometimes called **dark hosts** as they (for obvious reasons) do not advertise their existence like most legal hosts do.

**Offline hosts** are computers that are totally air-gapped, with no connection to the local mesh or the backbone. The only way to connect to them is directly via a cable. Offline hosts are often used for very important, secret file storage, and are placed in locations that are very physically secure.

But how do you actually get stuff done on the Matrix? Well, you interact with icons.

## Icons

Everything on the Matrix is represented by an *icon*. Icons can look like anything; cartoonish symbols, abstract runes, photorealistic 3d images; anything (although most sane Matrix designers use icons that at least vaguely resemble what they are used for). Icons can represent one of a few different types of thing:

* **Tags**: tiny little passive chips. They have no batteries or computing power of their own; they are powered by wireless power gathered from the Matrix. They typically hold and/or broadcast some number of files. They cannot be hacked, as such, as they lack any processor of their own. See [Tags]({{< relref "other_stuff.md#Tags" >}}) for more.  
* **Files**: any type of data (text, audio, video, computer code, ...), stored on any type of medium (in a tag, on a commlink, in a host, on a storage chip, ...).
* **Devices**: toasters, cars, door locks, speakers, microwaves, etc etc etc. In the Sixth World, near enough everything that has electrons flowing through it also has a functioning Matrix connection of its very own. Devices can be directly connected to the matrix (*unattended*) or protected inside a network run by a commlink, 'deck, or host. 
	* **Commlinks**: special devices that people use to see and interact with the Matrix.
	* **Cyberdecks**: souped-up commlinks that can be used to bend the rules of the Matrix by hackers and counter-hackers. There's also **drone decks**, which are similar but specialised and used to remotely control drones.
* **Hosts**: as mentioned above, these are the "servers" of the Matrix; big computer systems you can go into and do stuff within. So the social network P2.1 has a host that you go into to read your friends' updates, post messages, play games with them; that sort of thing.
	* Some hosts are so big that internally they are sub-divided into zones called **nodes**.






