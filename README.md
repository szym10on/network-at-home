# Plan, build and connect home network

_[?] In this project I will grant information about how I independently planed, built and connected home network_

_The guide covers single family house with router in living room, two rooms with network and hub in the attic that connects everything_

---

## Plan of the network at home.

**`Planning everything before doing is a great idea to not mess anything up.`**

<b>1. Full plan that i drew when I needed to see what will be necessary:</b>

![networkplan](https://github.com/szym10on/owning-a-server/assets/123908381/0a0141c5-0f76-4a5e-ae88-f2bedd172f6b)<br>

<b>2. List of things that I ordered(or bought in local shop):</b><br>

➤ 35 meteres of ethernet cable. Bought more then needed just in case ~$0.3/m, 35 * 0.3 = $10.5<br>
➤ 1x router sponsored from our internet provider, ussually cost of ~$25-$200<br>
➤ 1x 8 slot hub for connecting all the cables together $~25<br>
➤ 3x network sockets installed in a wall ~$5, 3 * 5 = $15<br>
➤ 9x network plugs. Bought pack of 20 just in case ~$0.3/each, 20 * 0.3 = $6<br>
➤ 1x network tool kit with tester, stripping tool and crimping tool ~$15<br>
Costs may depend on country you live in.<br>
All together: $71.5 without router cost.

---

## Types and categories of things used for a network.

**`There are a lot of type of cables, routers, hubs or other things that the network is made of.`**

<b>1. Ethernet cables:</b><br>

_If you want, you can just choose the latest Cat number (8 at the moment) for future-proofing and not worry about the rest. Or, you could take a look at what each Category is suitable for in our handy list below:_

- Cat 1 to 5:<br>
Skipping these categories because they are very old, technically not even official Ethernet standards, and they have been discontinued or are too slow to be usable.

- Cat 5e:<br>
The “e” in Cat 5e stands for “enhanced.” There are no physical differences between Cat 5 and Cat 5e cables. However, manufacturers build Cat 5e cables under more stringent testing standards to eliminate unwanted signal transfers between communication channels (crosstalk). Cat 5e is currently the most commonly used cable, mainly due to its low production cost and support for speeds faster than Cat 5 cables.

- Cat 6:<br>
The Cat 6 Ethernet cable supports higher bandwidths than Cat 5 and Cat 5e cables. They’re tightly wound and usually outfitted with foil or braided shielding. Said shielding protects the twisted pairs of wires inside the Ethernet cable, which helps prevent crosstalk and noise interference. Cat 6 cables technically support speeds up to 10Gbps for up to 55 meters. That speed comes with a price, however, as a Cat 6 cable is more expensive than Cat 5 and Cat 5e variants.

- Cat 6a:<br>
The “a” in Cat 6a stands for “augmented.” Cables based on this standard are a step up from Cat 6 versions by supporting twice the maximum bandwidth. They’re also capable of maintaining higher transmission speeds over longer cable lengths. Cat 6a cables come shielded, and the sheathing — which is thick enough to eliminate crosstalk — makes for a much denser, less flexible cable than Cat 6.

- Cat 7 and 7a:<br>
Cat 7 and Cat 7a cables are high-performing but tend to be useless for most people. Cat 7 cables support higher bandwidths and significantly faster transmission speeds than Cat 6 cables — much more akin to Cat 6A. Cat 7 cables reach up to 100Gbps at a range of 15 meters, making them one of the most capable categories of Ethernet cables. Cat 7 cables are always shielded, and they use a modified GigaGate45 connector, which is backward compatible with RJ45 Ethernet ports. That modified GG45 connector is a proprietary component, though, and while the backward compatibility helps a little, there are still issues with following previous Ethernet standards. This led to most manufacturers avoiding the Cat 7 standard, which is why it’s quite rare today. That difficulty led to the development of Cat 6a — and a lot of marketing confusion since some sellers started referring to Cat 6a as the new Cat 7. Always check the specs before you buy — and when in doubt, we suggest just going for Cat 8 instead. Cat 7a offers one of the highest-specification Ethernet cables you can buy, but it’s not widely available and offers only a few supporting networking hardware options. The 7a standard was designed to support 40 Gigabit Ethernet connections up to 50 meters and — just like Cat 7, but with improvement to the overall bandwidth — more than 50%. This improvement may be useful in some instances, but Cat 7a cables are far more expensive than any other option and its lack of industry support is something you can avoid by using Cat 8 cables.

- Cat 8:<br>
This standard promises a maximum frequency of 2,000MHz and speeds of up to 40Gbps at 30 meters. That high frequency also requires shielding, meaning you’ll never find unshielded Cat 8 cables. Even more, Cat 8 supports two connectors. Thus it only allows for three connected cables with a combined length of 30 meters. Cat 8 cables cost more than other options, but they have become more affordable in recent years. You can find options for a 10-foot Cat 8 under $15. Cat 8 also is the only cable to meet the latest IEEE standards (the aforementioned 40Gbps and 2,000MHz frequency), which is one reason it’s a great choice for future-proofing, despite the significantly higher costs. As a bonus, it also skips the connector mess of Cat 7.<br>

All information borrowed from the [Digital Trends](https://www.digitaltrends.com/computing/different-types-of-ethernet-cables-explained/) website.

<b>2. Routers:</b><br>

_I will grant information on what to look for when buying a network router for your home:_

- Wireless Standard (Wi-Fi Version): Check the wireless standard (also known as Wi-Fi version) supported by the router. The most common standards are 802.11n (Wi-Fi 4), 802.11ac (Wi-Fi 5), and 802.11ax (Wi-Fi 6). Newer standards offer faster speeds and better performance. Consider a Wi-Fi 6 router if you have devices that support this standard for optimal performance.

- Speed and Performance: Look at the router's maximum data transfer speeds. Routers may advertise speeds like AC1200 or AX3000, where the number indicates the theoretical maximum speed in megabits per second (Mbps). Consider your internet plan and the devices you'll connect to the router to ensure it provides sufficient speed for your needs.

- Ethernet Ports: Check the number and speed of Ethernet ports on the router. Gigabit Ethernet (1000 Mbps) ports are ideal for wired connections to devices like PCs, gaming consoles, and smart TVs.

- Compatibility: Ensure that the router is compatible with your internet service provider (ISP) and any specific devices or platforms you plan to use.

- Security Features: Ensure the router has robust security features, including WPA3 encryption, a firewall, and the ability to set up a guest network. Look for routers that receive firmware updates to address security vulnerabilities.

<b>3. Hubs:</b><br>

_Hubs are similar to routers, I will list things to look for when buying one:_

- Port Count: Determine how many devices you need to connect to the hub. Network hubs come in various port configurations, such as 4, 8, 16, or more ports. Choose a hub with enough ports for your current and future devices.

- Speed: Network hubs are typically available in Fast Ethernet (10/100 Mbps) or Gigabit Ethernet (10/100/1000 Mbps) versions. Gigabit hubs offer faster data transfer speeds and are more suitable for modern networks.

- Managed or Unmanaged: Most network hubs are unmanaged, which means they operate without any user configuration. Managed hubs offer features like Quality of Service (QoS), VLAN support, and remote management but are typically more expensive and are commonly used in enterprise settings.

- Cabling: Consider the type of Ethernet cables you plan to use. Ensure that the hub has the appropriate connectors (e.g., RJ45) and supports the cable category (e.g., Cat 5e, Cat 6, Cat 6a) you intend to use.

<b>4. Other things:</b><br>

Things like network sockets, plugs, or network tools are all almost identical. But check if everything is well made or if there is not damage done to it.

---

## How to do particular things

**`Making your network haven't been easier.`**

<b>1. Laying cables:</b><br>

- Calculate distances then cut your cables. Keep in mind to save more then needed just in case.

- Use conduits in walls to make it more aesthetically.

- Use pipe/conduit holders to attach conduit/cables on the attic.

- Save more cable (10-15cm on each end for sockets and plugs)

<b>2. Making ethernet sockets and plugs:</b>
 
- [How to make ethernet socket](https://www.youtube.com/watch?v=IHxTbtAEd-E)

- [How to make ethernet plug](https://www.youtube.com/watch?v=NWhoJp8UQpo)

<b>3. Test your netowrk cables:</b>

- You can use a previously purchased tester or connect your network and test it on your PC.<br>
[How to test ethernet cables with tester](https://www.youtube.com/watch?v=y3DmOPrmBio)
