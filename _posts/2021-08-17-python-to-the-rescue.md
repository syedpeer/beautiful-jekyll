---
layout: post
title: Python To The Rescue
subtitle: Python is your best friend for InfoSec
cover-img: /assets/img/rw-header.png
thumbnail-img: /assets/img/rw-thumb.png
share-img: /assets/img/rw-header.png
permalink: /infosec/python-to-the-rescue/
published: false
refsite1: https://en.wikipedia.org/wiki/Ransomware
refsite2: https://www.marsh.com/us/insights/research/ransomware-stats-every-business-needs-to-know.html
tags: [books, infosec]
---

Many folks from all walks of life and occupations aspire on a daily basis to gain a foothold into the new found world of Infosec, cyber security and hacking as that field continues to explode before their eyes at an exponential rate with opportunities and higher paid jobs tempting the uninitiated. As many in the field will tell you, Infosec and cyber security are frontier territory with many new and earlier unimaginable venues and opportunities opening up for entry-level would be adherents. 

<blockquote>

<p align="center">
“Talk is cheap, show me the code<br/>
 ― Linus Torvalds
</p>

</blockquote>

The highwaymen of old, masked, locked and loaded, would locate themselves in green pastures and foliage for camouflage and lay in wait for their unsuspecting victims to arrive. Then at the appropriate moment they would reveal themselves on the road and stop stage coaches in their tracks while their victims stared down the barrel of a musket and were read the un- forgettable command “Stand and deliver”. Theirs was a strategy of stealth and ambush that would confuse and confound their victims, ungentlemanly in its manner but lethal in its execution. Their prize would be a “king’s ransom” (or whatever was available) in return for the lives and property of their victims.

Fast forwarding to the present, a whole new industry has evolved of digital highwaymen better equipped than their forebear- ers and more efficient in their methods concealing their identity and leaving few traces of their pathways and steeped in a currency only the most daring can afford.

## Computer Program Definition 

As defined by Wikipedia:

<blockquote>

<p align="left"><br/>
A computer program is a collection of instructions that can be executed by a computer to perform a specific task.<br/><br/>
</p>

</blockquote>

Although this definition sounds almost too simplistic it speaks volumes in so far as trying to explain a vast and expansive field of study. An ocean of learning awaits those who would take on this seemingly Herculean task.

## Background

Python is a widely used and wildly popular high-level programming language used in the many fields such as Data Science, Artificial Intelligence (AI), Machine Learning (ML) and Cyber Security. Few languages can compare to its meteoric rise across software and mathematical analysis domains in speed and functionality. It was initially developed by Guido van Russum back in 1991 and has been developed further by the Python Software Foundation. 

Work on Python began in the late 80s when Guido van Rossum was working at the Centrum Wiskunde & Informatica (CWI) situated in the Netherlands. Begun as a hobby project it was a successor to the ABC programming language. Having helped to create the ABC programming Guido decided to take the syntax and best features of ABC into a new scripting language and worked to iron out all of ABC’s existing user complaints and flaws during the transition. He named the language “Python” after his favorite BBC TV show “Month Pythons Flying Circus”. The Python language was released in 1991 and Guido van Rossum remained the permanent “Benevolent dictator for life” (BDFL) until 2018 when he stepped down. Compared to other high-level languages such as Java, C++ and C, Python used a lot fewer codes and focused on providing readability and developer productivity out of the gate.

The graphic below clearly outlines the rise of Python (thru to 2019). 


![OSINT](/assets/img/python-thru-to-2019.png)

## Why Python? Why now?

Beyond necessary skills in networking and operating systems the greatest asset for anyone entering the InfoSec space is knowledge of programming. Specifically, the knowledge of Python. This will put you in a great place to exercise both your hacking skills and learn from the best proponents in the field. 

- Although some people may have cringed at the idea of getting into programming (and the associated math) that gets over their heads from earlier bitter experiences in high school (or elsewhere), programming in and of itself can be a very rewarding pursuit both within cyber security field and other domains. This skill is transferable!

- Python through no accident of itself has become the language of choice for hackers worldwide. Its acceptance by the developer communities has been dramatic and places it at the forefront of others languages within this domain (and others). This is evidenced by the large number of Python repositories and tools available on Github alone. A cursory review found that well over 20% of all exploits and attack tools were written in Python. 

The chart below sheds clarity on this particular programming phenomenon and the degree to which Python has taken the lead in this domain.

![OSINT](/assets/img/python-market-percentage.png)

- The two most popular Python modules used for web-based attacks were “Urllib” and “Requests”. Another newer module “Async IO” is also gaining ground recently as it fits in perfectly for “Layer 7 DDos” type attacks.

- Analysis done on sites that were attacked shows that an alarming 77% were initiated by a Python based tool and in over 30% of cases a Python based tool was responsible for the daily attacks under the APT umbrella.

![OSINT](/assets/img/percent-sites-attacked-by-python.png)

- Python is also well placed for attack on some of the most popular frameworks used on the web, such as Joomla, Drupal, WordPress, PHP and Struts. 

In short, there is ample evidence within business and industry that Python is becoming the de facto language for exploit development and attacks. 

## The “Colonial Pipeline” Case Study

The ransomware attack on the Colonial pipeline is a case study in what should and should not have happened. Organization need to review the information and take a pragmatic look at their own IT and OT systems in place.

- Though spear phishing is the flavor du jour for most breaches, in this case hackers gained access to a legacy VPN account password and started their work in earnest. How they obtained access to the that legacy VPN profile is unclear and still under investigation.
- Although the attack was significant in its reach and disruption it was NOT “nation-state” sponsored but executed by indi- viduals and private criminal teams intend on extortion. This only demonstrates how fragile our systems have become and how careless our security practices by those who operate them.
- In the year 2018 an external Audit of Colonial discovered “atrocious” information management practices and a “patch- work of poorly connected and secured systems”. Probably not alone in the energy industry for such poor findings, it still surprises that even 3 years after such a report they fell victim to such an attack and one can only assume that their “infor- mation management practices” have not improved significantly to allow orphaned VPN accounts to be still available for exploits.
- Most worrying, without an advanced Trojan Horse or a focused spear phishing campaign or malware specifically engi- neered “fit for function” or the Colonial network, hackers simply used a redundant (yet active) orphaned VPN credential login password to gain access into Colonial’s secured systems and achieved the necessary lateral movement of malicious software.
- Whether by luck or intent Colonial managed to have sufficient warning time to disable their OT systems that supplied gasoline to most of the Eastern Seaboard states.
- Ransomware often avoids anti-malware detection tools and morphs so rapidly from attack to attack that fresh variants may be unrecognizable and prevention tools totally ineffective.
- Even though they had the necessary backups, the lack of a robust recovery execution plan forced Colonial to cut a Bitcoin check (to the tune of 5 million dollars). Again, this highlights poor or inadequate practices in place and even poorer de- fense and public communications strategy. The money trail led the FBI to an Eastern Europe outfit known as “Darkside” who have since been very apologetic for their actions but have not returned the money.
- Enforcing Federal Regulatory compliance energy providers may be a viable solution, but with up to 80% of power genera- tion, distribution, refining etc. being privately owned in the US – there may be a long wait for the end game.

In short, there was ample time (3 years) and early warnings (from the 2018 audit) to have taken necessary measures but Co- lonial still fell victim to a 5th graders attack vector (credential compromise).

## Mitigations

Organizations need to looking at some of the following steps as a minimum requirement if they are to prevent embarrassing repeat attacks due to VPN vulnerabilities.

1. **VPN Known Exploits**: If there are known vulnerabilities with VPN providers and equipment, then a strategy needs to be urgently formulated for how their systems can be patched or if unpatched how they can be a part of a High Availability solution that provides for other devices to fail over. This is NOT a casual budget expense but may be necessary as a last resort if the Colonial style damage is to be avoided. VPN should be included as a critical attack vector and organizations should prepare for continuous patching and monitoring as necessary.

2. **Build Resilience**: Organizations need to have policies and procedures in place already for regular data backups, air gap enablement including necessary and better password and credential management tools to flag for archived or orphaned logins that may still work for outsiders and supply chain partners.

3. **Redraw and Remap the Network**: In the search for better security, business owners must review and possibly remap their network configuration allowing for rigorous segmentation to keep the critically impacted areas within their con- trol and containment strategy. After saving lives (which remain their first priority) Firemen rarely try to save the whole building, they are only interested in preventing the spread of the fire to adjoining homes and businesses in the surround- ing areas. Computer networks are no different and need some TLC (tender loving care) every few years is needed to be sure that networks are reviewed and optimized for security and “containment”.

4. **Use Multi-Factor Authentication (MFA)**: Every login to systems should require a secondary degree of validation that MFA can provide. Although some customers are loath to use it, due to its so called an inconvenience, the technology has been around for a number of years and provides the additional security to trust any login credential. How far would the Colonial hack have reached if MFA been implemented on all VPN logins?

5. **Audit**: Continuously ask for an audit of accounts with heightened privilege for both Super Users and Networks Admins. Ensure that a “least privilege” approach is established and all deviations from the same require manager approvals. Inter- nal Audit will be all to ready to help IT / OT with this so it should not be a burden to do regularly with a rotating schedule.

6. **Enforce More Rigid Email Restrictions**: Disable hyperlinks contained within received emails to prevent spear phish- ing and malware spread. Improve email filtering and ensure that antivirus and anti-malware software are current and up to date.

7. **Awareness Training**: Build out the employee awareness and training program and ensure that they are current with respect to recent attack vectors. Employees are the first line of defense and their education should remain a priority.
8.Password Policy: Require complex passwords and ensure that they are changed regularly based on an agreed schedule. Disable all unused credentials for any type of remote access/RDP and ensure that necessary ports and logs are reviewed regularly.


## Conclusion

As we can see clearly now, the ransomware threat is not going away anytime soon. Quite the opposite is to be expected. As long as there are pliable targets (such as Colonial) all too ready to part with the cash after the event rather than invest in bet- ter training and threat monitoring and due diligence before the attack, there will remain an army of ready and able actors to continue this trend.

Separately, the dependence on private energy providers and infrastructure who are not necessarily beholding to govern- ment regulatory edicts will further cloud the affair with few government agencies ready to take on the energy suppliers. To face the modern threat though every government needs to re-asses the private sector dependency curve and how it can strengthen its cyber security net without stifling private investment and job creation.

## References

1. Wikipedia Definition: <a href="{{page.refsite1}}">Ransomware</a>
2. Ransomware Stats: <a href="{{page.refsite2}}">Ransomware Stats Every Business Needs to Know</a>

### Published version.

[![OSINT](/assets/img/rw-mag-cover.png)](/assets/pdfs/H9-RM-VM.pdf){:target="_blank"}

<div class="views">
    <span class="views">
        <img src="https://visitor-badge.glitch.me/badge?page_id={{ .site.permalink }}" alt="Views"/>
    </span>
</div>