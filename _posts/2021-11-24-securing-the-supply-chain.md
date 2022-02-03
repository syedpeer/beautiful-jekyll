---
layout: post
title: Securing The Supply Chain
subtitle: How fragile is your supply chain?
cover-img: /assets/img/securing-the-supply-chain-header.png
thumbnail-img: /assets/img/python-thumb.png
share-img: /assets/img/python-to-the-rescue-header.png
permalink: /infosec/securing-the-supply-chain/
published: true
refsite1: https://en.wikipedia.org/wiki/Supply_chain_attack
refsite2: https://www.upguard.com/blog/how-to-prevent-supply-chain-attacks
refsite3: https://www.wired.com/story/hacker-lexicon-what-is-a-supply-chain-attack/
refsite4: https://www.sonatype.com/resources/white-paper-state-of-the-software-supply-chain-2020
tags: [books, infosec]
---

At no time since the dawn of the Industrial Revolution have manufacturing businesses thrived on the diversification and choice of vendors, the globalization of suppliers and manpower services, and the accelerated growth of the customer base due to improved infrastructure, shipping routes, and the internet...

However, as software has brought immense accessibility and reach to billions of customers, it has also become an Achilles heel when used in concert with bad actors to disrupt, destroy and debilitate otherwise healthy and profitable organizations.

<blockquote>

<p align="center">
“Software is eating the world" ― Marc Andressen
</p>

</blockquote>

## Definition

As defined by Wikipedia:

<blockquote>

<p align="left"><br/>
As defined by Wikipedia "A supply chain attack is a cyber-attack that seeks to damage an organization by targeting less- secure elements in the supply chain. A supply chain attack can occur in any industry, from the financial sector, oil indus- try, to a government sector.”. Although there are many ways to define and explain this term, the key takeaway from this definition is the “less-secure” element that is a constant in all forms of cyber security defense conversations.<br/><br/>
</p>

</blockquote>

Although this definition sounds almost too simplistic it speaks volumes in so far as trying to explain a vast and expansive field of study. An ocean of learning awaits those who would take on this seemingly Herculean task.

## Background

The “modus operandi” of a supply chain attack centers around an individual or team of bad actors targeting an organization not directly (as that would be too obvious) but rather through an external trusted partner or supplier who may have some manner of access to the organization’s systems. This new route for hackers has grown within the last few years and has transformed the attack surfaces significantly from not just the target organization itself but now across all companies, sup- pliers, and service providers that have any manner of touchpoints within the organization.

![OSINT](/assets/img/securing-the-supply-chain-01.png)

This now presents a clear and present danger to organizations as sensitive data inside the organization that is accessible by trusted partners outside the organization can now become the source of a data breach or worse still a malware injection. This danger can be compounded if the target organization is a “supplier-of-suppliers” who happen to house sensitive infor- mation about other suppliers on their systems. Like almost everything in the internet age, the danger growth curve is expo- nential in nature.

## Prevent Cyber Attacks

Besides the basic rule of thumb to always work to reduce the attack surface of an organization, a number of steps can be taken both by manufacturers and suppliers to prevent attacks and harden system integrity.

1.	**Supplier Security Standards and Policy**: Suppliers should implement improved controls on their code deliv- ery platforms that aggregate, compile, build and distribute software to prevent malware injection and root-kit infusion into the customer deliverable. The recent Solar Winds debacle is just one of the most notable instances of an upgrade in- staller being compromised and affecting hundreds of customers. Ironically, one of the highest-profile companies compro- mised in that attack was FireEye, a notable cybersecurity provider itself. Other firms, like MalwareBytes, were also tar- geted together with behemoths like Microsoft.

2.	**Software Development Life Cycle Hardening**: Python is both Free and Open Source and has been available for several platforms (Windows, Mac, Linux etc.) for download from its official website at python.org. The source code is freely available to the public.

3.	**Secure Access and Privileges**: Organizations should ensure that Suppliers’ Access and Privileges are regularly re- viewed and strengthened as part of the Annual Risk Assessment Cycle. Too often, organizations are engrossed in their pe- rimeter defenses looking both inwards and outwards without realizing that their most potent adversary may be using the front door to enter their compound.

4.	**Industry Security Certification**: Manufacturers may demand that their suppliers work towards implementing a recog- nized industry supply chain security certification standard such as ISO 28000. This may not be reasonable for smaller out- fits but the largest suppliers will have no trouble implementing the necessary framework and obtaining the associated cer- tification. Attackers will frequently seek out some of the smaller suppliers knowing full well that they may not have the finances or expertise in-house to implement sophisticated controls necessary to thwart their intrusion.

5.	**Zero Trust Architecture (ZTA)**: When dealing with vendors’ interactions, their customers should be prepared to adopt a Zero Trust Architecture (ZTA) approach. All network activity with the vendor must be considered malicious by default. Only after each connection request passes a strict list of policies is it permitted to access the sensitive and intellec- tual property within the customer systems.

6.	**Cyber Security Awareness Program**: Manufacturers may require their suppliers to institute a meaningful Cyber Se- curity Awareness Program in-house to educate their staff and all data-facing team members of the dangers of malicious attacks and methods of recognizing a threat vector. Even the most administrative of roles such as accounting, payroll, and HR would have access to some of the most sensitive data yet are oblivious of the simplest of measures required to im- prove their security posture whilst being targeted continually by phishing emails. Awareness programs should not be treated as a panacea but rather another complementary tool in the armor to improve defenses, as too often humans pre- sent the most vulnerable of interfaces for hackers.

7.	**Open Source Software & Platforms**: Vendors should regularly review the usage and suitability of Open Source soft- ware to ensure that the tools they take for granted have not been compromised and are contributing to disseminating mal- ware to their customers. Software build tools require particular attention here as they are the ones responsible for packag- ing the final executable for distribution that ships to the customer at large. In fact, according to Sonatype’s 2020 State of the Software Supply Chain Report, 90 % of all apps use open-source code, and 11 % of them have known vulnerabilities.

8.	**Independent 3rd party Risk Assessments**: Although we all try to abide by an honor system in our daily lives and business transactions, this may not be the same when working with vendors. Rather than leaving this to chance, manufac- turers are encouraged to require vendors to allow access to Third Party Risk Assessments that generate reports to be re- turned to the manufacturer to validate their trust. Vendors will rarely do this voluntarily so it’s up to their customers to insist on these checks and balances being in place. Such third-party risk assessments will demonstrate clearly to custom- ers the security posture of vendors and if they need to improve their position further or risk losing business because of it.

9.	**Reduce Outsourcing**: The globalization of manufacturing and services during the last three decades has led to a web of interdependencies that has been brought into sharp contrast due to the COVID-19 pandemic and its associated restric- tions. This has expanded the attack surface greatly, allowing hackers to focus on low-hanging fruit, such as poorly pre- pared and defended downstream supply chain vendors, thereby getting backdoor access to some of the largest corpora- tions and their systems through the supplied products. Compromised electronics and semiconductors products used within the US military, government, and vital civilian platforms provide foreign adversaries with possible backdoors to attack these systems at will. This is especially concerning in the energy and power distribution industry with many IoT devices being supplied from abroad.

This list is by no means final or conclusive of all opportunities for improving the supply chain conundrum. At best, it pro- vides some minimum guidelines on areas that need to be addressed to reduce the attack surface.

## Conclusion

For businesses, both large and small, all the reasons above, and probably some not listed, demonstrate how the threat land- scape has changed when building products and services are reliant on an advanced supply chain of trusted partners and 3rd party tools. The seaports in Los Angeles account for around 60% of all in-bound import merchandise and products arriving into the US. Yet they have been backed up for months with a whole armada of container ships waiting to dock and unload. The pandemic of 2019/2020/2021 has laid bare just how fragile our supply chain networks are with shortages predicted in the near and long term. Car dealerships are flush with pre-owned models while the latest models float aimlessly in the holds of ships anchored at the Pacific ports waiting their turn to unload. Manufacturers are unable to meet or ship orders due to chip shortages that may not recede for months to come. The supply chain is the oxygen of the world economy and needs to be protected if industry and the whole economic system is to survive.

## References

1. Wikipedia Definition: <a href="{{page.refsite1}}" target="_blank">Computer Program </a>
2. 11 Ways to Prevent Supply Chain Attacks in 2021 (HighlyEffective): <a href="{{page.refsite2}}"  target="_blank">How to prevent</a>

### Published version.

[![OSINT](/assets/img/H9-python-to-the-rescue-mag-cover.jpg)](/assets/pdfs/H9-Best-Hacking-Tech.pdf){:target="_blank"}

<div class="views">
    <span class="views">
        <img src="https://visitor-badge.glitch.me/badge?page_id={{ .site.permalink }}" alt="Views"/>
    </span>
</div>
