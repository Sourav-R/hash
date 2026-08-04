# MOCK INTERVIEW PREPARATION SHEET

**Candidate:** Sourav Ramakrishna | **Role:** Service Desk Engineer, Level 2 (Managed Services)
**Target Company:** FUJIFILM MicroChannel Services Pty Ltd — Melbourne VIC, hybrid
**Stage:** Technical discussion, 1 hour | **Interviewer:** Craig Knight-Dawson, Support Manager

---

## 1. Candidate Snapshot — Interviewer's View

Sourav comes in with a service desk background built at ThIRU, a managed security provider running five healthcare clients on Atera for both PSA and RMM. He handled L1 and L2 tickets across that queue, administered Windows Server and Active Directory, worked Cisco routing and switching, SonicWall and Fortinet firewalls, and hands on virtualisation across VMware ESXi and Proxmox VE. He monitored and triaged Elastic alerts across multiple client tenants. He carries genuine cross platform device support, Apple alongside Windows, and holds a postgraduate qualification from Monash University while working toward CCNA and Microsoft SC-200.

The team structure matters here and works in his favour if he frames it right. Four people total: CTO, one engineer above him, Sourav, and a junior who joined recently. That means no deep bench behind him, he was the escalation point for the junior rather than having one himself, and he carried the bulk of the day to day queue. For a support manager that reads as ownership and self sufficiency, provided it is delivered as ownership rather than as a complaint about being under resourced.

The dynamic to prepare for is different from a school support role. Craig Knight-Dawson has managed support functions at CodeBlue, First Focus and Brennan IT before Fujifilm, which means his baseline for normal is a mid size MSP running thousands of seats across dozens of tenants. He is not assessing whether Sourav is technically capable, that is largely evident from the resume. He is assessing three things: whether the stated experience duration holds up to arithmetic, whether the Microsoft productivity stack gap is trainable or disqualifying, and whether someone with a visible security trajectory will still be in this queue in eighteen months.

The technical strength sits in networking, and it sits noticeably above the L2 bar. The exposure gap sits in Exchange Online, SharePoint, OneDrive and general Office 365 administration, which for a Microsoft partner MSP is a large share of daily ticket volume. That is the real contest.

---

## 2. Role & Company Relevancy

FUJIFILM MicroChannel is a business technology provider founded in 1995 as MicroChannel Services, acquired by FUJIFILM Business Innovation in 2023. Two halves to the business: enterprise software implementation, Dynamics 365, SAP, Sage, retail systems, and Managed IT Services running outsourced IT for client businesses. This role sits in the second half, supporting over 1,400 managed services customers across Australia, New Zealand, Fiji, Singapore and South East Asia.

| Area | Relevancy Notes |
|---|---|
| Networking and firewall troubleshooting | Cisco routing and switching, VLANs, SonicWall and Fortinet policy, SSL and IPSec VPNs, packet level analysis via Wireshark and tcpdump. Strongest area on the resume and above what the ad asks for. Listed requirement, direct match |
| Windows 10/11 desktop support | Direct match to a stated must have. Standard expectation rather than a differentiator |
| End user device troubleshooting, including Apple | MacBook, iPad and iPhone alongside Windows endpoints. Listed as desirable, and on a high volume shortlist the desirables decide it. Genuine differentiator, most Windows native candidates cannot cover macOS |
| Virtualisation | VMware ESXi hands on troubleshooting and Proxmox VE bare metal deployment. Listed as desirable, and hypervisor level depth exceeds what a service desk role normally sees |
| Windows Server and Active Directory | GPO and Security Group administration, plus Essential Eight configuration baselines across 1,000 plus endpoints via SaltStack. Note this last detail is not on the Fujifilm version of the resume, see Section 4 |
| Security conscious environment | DLP policy deployment, ELK SIEM monitoring, Elastic Agent EDR rollout across 40 plus endpoints. The ad names SentinelOne, Proofpoint and CrowdStrike instead, so the concepts transfer but the product names do not |
| PSA and RMM | Atera, covering ticketing, SLA policies, patch management and remote access in one platform. Real PSA discipline, on a platform pitched at smaller MSPs. Answerable and honest, see Q3 |
| Multi tenant experience | Five clients, all healthcare. Genuine multi tenant rather than internal IT, which satisfies the ad's MSP preference. Smaller than Fujifilm's 1,400 plus customer base, so expect the step up in scale to be probed rather than assumed |
| Healthcare vertical | Five healthcare clients means compliance overhead, strict change windows and low tolerance for downtime as the normal operating condition, not the exception. Underused on the resume and worth raising deliberately |
| Exchange Online, SharePoint, OneDrive, Office 365 | Not covered on the resume, and all four are named must haves. This is the most likely reason a competing candidate from a Microsoft house MSP scores higher. Prepare an honest framing rather than improvising. Worth checking tonight whether you used Atera's Microsoft 365 integration for user management, since that would partially close this |
| Printers, backup systems, UC tools | None covered. Printers are a named must have and the highest volume ticket type in any MSP queue. Backup and UC are desirables but function as tiebreakers |
| RDS, AVD, Citrix | Not covered. VPN is covered well, which is half the named remote access stack |
| Certifications | CCNA and SC-200 both in progress, none completed. The ad asks for relevant industry certifications by name including Cisco and Microsoft |
| Experience duration | The ad states a minimum of three years in a similar role. This needs a clean, precise answer, see Q2 |
| Compliance | Current clear National Police Clearance already held, which the ad names as a condition of employment. Full unrestricted Victorian licence, relevant given occasional onsite work. Confirm working rights explicitly since the resume does not state visa status |

---

## 3. Top 15 Mock Interview Questions and Ideal Answers

### Q1. Tell me about your background and why this role.

**Ideal Answer:** I have built a service desk and infrastructure background across Microsoft and virtualisation environments. At ThIRU I worked as a Service Desk Engineer across multiple client environments, managing tickets to SLA, resolving critical incidents through structured troubleshooting, and supporting everything from Windows Server and Active Directory through to VMware ESXi and Proxmox virtualisation. I picked up genuine cross platform experience supporting Apple devices alongside Windows, and worked hands on with SonicWall and Fortinet firewalls plus SSL and IPSec VPNs. What draws me to this role is scale and variety. I want to be in a mature MSP with a real tenant base and a proper support function around me, rather than a smaller environment where you are working things out alone. Fujifilm MicroChannel has 1,400 plus managed services customers and a support team with structure behind it, and that is the environment where I think I get better fastest.

**Why it is asked:** Opening question. Craig is listening for whether you have a specific reason for wanting this job or whether it is one of thirty applications. Naming the tenant count signals you actually read about the business.

---

### Q2. Take me through ThIRU. When did you start, what was the arrangement, how many clients?

**Ideal Answer:** ThIRU is a managed security provider, so it is a multi client managed services environment rather than internal IT. I covered five clients, all healthcare, handling both L1 and L2 across the queue. The team was four including me, the CTO, one engineer above me, and a junior who joined fairly recently, which meant I was carrying most of the day to day queue and I was the escalation point for the junior rather than having a deep bench behind me. Working healthcare clients also meant change windows were tight and downtime tolerance was low as a normal condition rather than an occasional one.

State your real start date, your real end date if the engagement has concluded, and whether it was fixed term or permanent, without hedging. If your total hands on service desk time is under the three years in the ad, say the number yourself before he works it out: *I want to be straight with you on the numbers. My hands on service desk time is [figure], which is under the three years in the ad. What I would say is the depth in it is not typical for that length of time, five healthcare tenants, both L1 and L2, hypervisor level virtualisation, packet level network diagnosis, and a security rollout I planned and executed myself. I would rather you assess the depth and decide than have me stretch the number.*

**Why it is asked:** The ad states a minimum of three years as a hard requirement, and Craig will do the arithmetic during the conversation. Volunteering it costs you far less than being caught on it. Managers respect the candidate who raises their own weak spot, and they discount everything else once they catch a stretch.

**Delivery warning:** The small team detail is genuinely in your favour, but only if it lands as ownership. *I was carrying most of the queue* reads as self sufficiency. *I had to do everything because nobody else did* reads as a grievance, and a manager hears that as someone who will struggle in a structured team where they are not the only one doing things. Same facts, opposite outcome. Say it flat and matter of fact, no edge in the voice.

---

### Q3. What did you run the ticket queue on, and what RMM sat behind it?

**Ideal Answer:** We ran Atera for both PSA and RMM, so ticketing, SLA policies, patch management and remote access all sat in the one platform rather than being stitched together. I worked the queue across five healthcare clients, both L1 and L2. I would be upfront that Atera is a lighter platform than what you are likely running at 1,400 plus customers, so if you are on ConnectWise or Autotask there is a genuine ramp on the tooling for me. What carries across is the discipline rather than the buttons. Prioritising by business impact rather than order of arrival, tracking SLA state actively rather than assuming the timer is where you think it is, and writing resolution notes with root cause in them so the next person is not rediscovering the same thing.

Be ready to add operational texture if he probes: how you categorised tickets, how the SLA policies were configured, how time entry worked, where documentation lived, and whether you built any of the automation profiles yourself.

**Why it is asked:** Craig came from Brennan IT and First Focus, both of which run enterprise PSA and RMM. Naming Atera tells him immediately that you have real queue and SLA discipline on a smaller platform. That is a perfectly good answer. Volunteering the ramp yourself is what makes it land, because he was going to conclude it anyway and it is far better coming from you.

---

### Q4. A user is getting repeated credential prompts and Outlook is disconnected. Domain joined, hybrid tenant. Walk me through it.

**Ideal Answer:** First thing I would establish is whether this is an identity problem or a client problem, and whether the failure is on premises or in the cloud, because in a hybrid tenant those are two different places to look. I would check whether the account is locked in on premises Active Directory or whether the sign in is being blocked in Entra, and check the sign in logs rather than guessing. On the device I would run dsregcmd status to confirm the device is still properly joined and the primary refresh token is valid, because a broken device trust produces exactly this symptom. I would clear stale entries in Credential Manager, since an old cached password after a reset is one of the most common causes. If the account is healthy and the device trust is healthy, then I start looking at the Outlook profile and modern authentication rather than the identity layer.

**Why it is asked:** Highest frequency L2 ticket in a hybrid Microsoft environment. Craig is listening for whether you can separate on premises identity from cloud identity. Reaching for dsregcmd is the marker that separates someone who has worked hybrid tenants from someone who has read about them.

---

### Q5. Onboard a new starter for me, hybrid tenant, in order.

**Ideal Answer:** The first thing I would do is check the client's documented onboarding runbook, because every tenant does this slightly differently and getting it wrong on a new starter is visible immediately. In a hybrid tenant I would create the account in on premises Active Directory rather than directly in Entra, because the sync runs one direction and creating it in the wrong place gives you a duplicate object to clean up. Then force or wait for the sync, assign licensing through group based licensing rather than individually so it stays maintainable, add security group membership since that is what should be driving access rather than direct permissions, confirm the mailbox provisions, add any shared mailbox or distribution list membership the role needs, and make sure MFA registration and device enrolment are completed rather than left for the user to figure out. Then I would confirm with whoever raised it that the user can actually do their job, not just that the account exists.

**Why it is asked:** Directly tests the Entra and AD user administration requirement. The sync direction detail is the tell. So is checking client documentation first, which signals multi tenant thinking rather than single environment habits.

---

### Q6. A client wants a mailbox three people can send from, with shared history, that external people can email. Shared mailbox, distribution list, or Microsoft 365 group?

**Ideal Answer:** This is your weakest named must have, so prepare it properly. The answer is a shared mailbox, because it keeps a single stored history all three can see, it supports both Send As and Send on Behalf with separate permission models, and it does not consume a licence while it stays under the size cap. A distribution list fails because it only forwards to individual mailboxes, so there is no shared history and no ability to send from the address. A Microsoft 365 group would technically work but brings a Teams and SharePoint site along with it that the client did not ask for and will not maintain. If you genuinely do not know this, do not improvise. Say: *I have not administered Exchange Online directly, so I would want to check rather than guess on the permission model. My instinct is a shared mailbox because that is the one that keeps a single history, but I would confirm the licensing threshold before telling a client.*

**Why it is asked:** This is the standard question for separating people who have administered Exchange Online from people who have read documentation. It is also the exact gap on your resume, which makes it a highly likely question. An honest do not know delivered with a reasoned instinct scores better than a confident wrong answer.

---

### Q7. A user has left. The manager needs their OneDrive files, and two folders were shared externally with auditors.

**Ideal Answer:** The sequence matters here because OneDrive content is retained on a timer after account deletion rather than kept indefinitely, so the first thing I would do is delegate access to the manager or move the content before that window closes, not after. For the mailbox I would convert it to a shared mailbox or apply a hold rather than deleting it outright. The part people get wrong is the external sharing. Removing the user from a security group does not kill sharing links they created, those links exist independently, so I would go and find every external sharing link on those folders specifically and revoke them rather than assuming group removal handled it. Then confirm with the client that the auditors either lost access intentionally or have been reissued access through the right person.

**Why it is asked:** Offboarding plus broken permission inheritance plus external sharing is a real weekly MSP job and a genuine security exposure. The sharing links detail is the marker. If Exchange and SharePoint are your gap, this is worth thirty minutes tonight because it is the highest value thirty minutes available to you.

---

### Q8. Twelve users at one site cannot print. Everyone else in the tenant is fine.

**Ideal Answer:** I would scope it before touching anything, because twelve users at one site tells me something about the boundary of the fault. Is it one printer or all printers, one subnet or the whole site, and did anything change recently. Then I would check how those printers are actually deployed, whether that is Group Policy, Intune, Universal Print or a print server, because that determines where the fault can be. If it is a print server, spooler state and queue state. If the timing lines up with a Windows update or Patch Tuesday, I would look at driver and point and print behaviour, since driver installation permissions changed significantly after the PrintNightmare patches and that breaks deployments that worked the week before. And I would check whether that site can actually reach the print server, because a connectivity fault presents as a printing fault to the user.

**Why it is asked:** Printers are a named requirement, they are absent from your resume, and they are the highest volume lowest glamour ticket type in any MSP. Scoping before acting is what is being assessed, not printer trivia.

---

### Q9. An entire site is down. Forty users, no internet, no line of business application. You are first responder.

**Ideal Answer:** I would scope before touching anything, because on a site wide outage the worst thing you can do is start at somebody's desktop. I would check the firewall and the monitoring first to establish whether the WAN link is down, the firewall has failed, or something has happened at the switch layer. If the WAN interface is down I raise the carrier ticket immediately and in parallel with my own investigation rather than after it, because carrier clock time is the long pole and every minute you spend before raising it is a minute added to the outage. Then I would get a holding update to the client inside the first ten minutes with what I know and when they will hear from me next, even if what I know is very little. In my experience the thing that turns an outage into a complaint is not the outage length, it is silence during it.

**Why it is asked:** Networking is your strongest area, so this question is where you should be visibly better than the shortlist. The parallel carrier escalation and the ten minute holding update are the two markers Craig will note, because both are learned in real MSP work rather than from documentation.

---

### Q10. Remote user cannot reach the corporate network. VPN says connected.

**Ideal Answer:** Connected but no access tells me the tunnel came up and authentication succeeded, so this is a routing or DNS problem rather than an authentication one. I would check the assigned tunnel address, then route print to see whether the expected internal routes were actually pushed down, then whether split tunnelling is configured in a way that is sending internal traffic out the wrong path. Then DNS, whether the internal resolvers and the DNS suffix came down with the tunnel, and I would test by IP address versus by name to isolate whether it is name resolution or reachability. If routing and DNS are both healthy, I move to firewall policy on the SonicWall or Fortinet side to see whether that user or subnet is actually permitted. On RDS, AVD and Citrix specifically I have not worked with those directly, my remote access experience is VPN, but the connectivity and routing layer underneath them is the same ground.

**Why it is asked:** Plays to your strength, and the last sentence handles the RDS, AVD and Citrix gap on your own terms rather than waiting to be asked about it separately.

---

### Q11. Your EDR flags a PowerShell process on a finance user's laptop overnight. Talk me through triage. And separately, a user forwards you a suspicious email.

**Ideal Answer:** On the EDR alert, the first thing I want is what actually ran, so parent process, full command line, whether it was encoded, what it touched on disk and where it went on the network. Then whether it correlates to something legitimate, a scheduled task or a management tool, because most of these do. The decision on whether to isolate is a business decision as much as a technical one, isolating a finance machine at month end has a real cost, so I would establish blast radius first and have a conversation with the client rather than isolating unilaterally unless the evidence is strong. On the phishing report, I would get the original with full headers rather than a forward, establish whether anyone clicked or entered credentials, and search the tenant for other recipients and purge, because one report usually means twenty deliveries. If credentials were entered then password reset, revoke active sessions, re register MFA, check the sign in logs for unusual locations, and check for mailbox rules the attacker created, which is the step people forget. And I would thank the user, because reporting behaviour is worth reinforcing.

**Why it is asked:** Tests whether your Elastic based security experience transfers to the tools they actually run. The mailbox rules check and the tenant wide purge are the two markers that separate real incident handling from ticket closing.

**Precision point, worth getting right:** You said the Elastic knowledge transfers to Sentinel. Be careful which Sentinel you mean, because the two are unrelated products and conflating them in front of a support manager undoes the credibility you just built. SentinelOne is an endpoint agent, and the thing that maps to it is Elastic Agent and Elastic Defend. Microsoft Sentinel is a cloud SIEM, and the thing that maps to it is your ELK and Elastic Security alert triage work. Your experience genuinely covers both sides, which is a stronger position than most candidates, so say it as two mappings rather than one: *my endpoint work was Elastic Agent, which is the same category as SentinelOne or CrowdStrike, and my SIEM triage was on ELK, which is the same category as Microsoft Sentinel.* Do not claim the query languages are the same. Elastic and Kusto are both abbreviated KQL and they are different languages, which is exactly the kind of thing someone will check.

---

### Q12. Monday, 8:40am. Forty tickets across twelve tenants. Three P1s, one about to breach. Two engineers out.

**Ideal Answer:** I would triage the whole queue before working anything, because the worst outcome is spending forty minutes on the first thing I opened while something bigger sits. I am separating genuine P1s from mislabelled ones, and separating tickets I can close in two minutes from ones that will take an hour, because clearing the quick ones reduces the queue and the noise. On the one about to breach, I would communicate before I troubleshoot, because a breach the client knew about and a breach they discovered are two completely different conversations. Then I would raise the staffing gap with my manager immediately rather than absorbing it quietly, because two engineers down is a resourcing decision, not something I should be silently soaking up. And I would weight impact by client, a P1 for a five seat client and a P1 for a four hundred seat client are not the same P1 even when the SLA tier is.

**Why it is asked:** This is the core of the job and the question a documentation reader cannot fake. Craig has run this exact Monday many times. Triaging before working, communicating before the breach, and escalating staffing are the three things he is listening for.

---

### Q13. What is the difference between priority and severity, and when does the SLA clock stop?

**Ideal Answer:** Severity is the technical impact of the issue itself. Priority is that severity weighted by urgency and business context, so a low severity issue on a system that is critical for a client this week can carry a higher priority than something technically worse. They diverge more often than people expect. On the clock, it typically pauses when the ticket goes to a customer pending or scheduled with customer state and resumes on response. The honest part of that answer is that pending status gets abused, because it is the easiest way to protect your numbers without actually resolving anything, so the value of the metric depends on the discipline behind it.

**Why it is asked:** Direct test of MSP fluency, and almost nobody outside a real MSP gets the clock behaviour right. The remark about pending status being gamed is optional but it will land, because every support manager has dealt with it.

---

### Q14. Two P1s, two different clients, same SLA tier, same minute. And separately, a client contact who is angry after four days on an open ticket.

**Ideal Answer:** On the two P1s, I make the call on business impact rather than which one arrived first, so number of users affected, whether anything is revenue critical, whether one has a workaround available. Then I escalate for a second pair of hands immediately. The part that matters more than the choice is what the second client hears, and they should hear from me proactively with an honest position and a realistic time, not discover the delay themselves. In this business silence is what turns a delay into a lost account. On the angry client, I would let them finish rather than defending, and acknowledge that four days is genuinely too long rather than explaining why it happened, because at that point they do not want the reason. Then separate what I can fix right now from what I cannot, commit to a next update time and actually hit it. And afterward I would want to know what in our process let it sit for four days, because the fix is that, not the apology.

**Why it is asked:** Client facing composure is weighted heavily, the ad asks for a vibrant personality and exceptional communication skills, and it is the easiest thing for a technically strong candidate to under sell. The process fix at the end is what separates a good answer from a memorable one.

---

### Q15. Your background leans security. This is a service desk queue. Why this role, and where are you in two years? And do you have questions for us?

**Ideal Answer:** On the motivation, own it rather than denying it, because the SC-200 and HackTheBox entries are on the resume and denying the interest would be transparently false. Something like: *I am not going to pretend the security interest is not there, it is on my resume. What I would say is that the engineers I have seen who are actually good at security are the ones who understood infrastructure and support properly first, and I would rather build that at an MSP with real tenant variety than skip it. Two years out I would want to be the person other people on the team escalate the network and infrastructure problems to. That is a support career, not a stepping stone out of one.*

For your questions, pick three: What does the escalation path look like day to day, when does something move from L2 onward? What PSA and RMM does the team run on? What does a strong first three months look like in this role? And if the conversation has gone well, one more that only someone who did their homework would ask: you have come through CodeBlue, First Focus and Brennan IT before Fujifilm, what does the support function here do differently from those?

**Why it is asked:** Retention risk, and it is the highest probability question from a manager who has watched people use a service desk as a route into a SOC. Expect a follow up probe such as whether you would take a SOC role internally in six months. Have an answer that is honest rather than convenient.

---

## 4. Interview Tips for Sourav

### Before the interview

- **Fix the resume dates and tense tonight, regardless of how tomorrow goes.** The Fujifilm version reads June 2025 to Present with a present tense summary. If that engagement has concluded, this surfaces at employment verification, which is after the interview and at a stage where you have no opportunity to explain it. Same applies to the degree name if the awarded testamur differs from what is printed. These are the only two things in this document that can cost you an offer you have already won.
- **Lead the healthcare angle deliberately, it is underused.** Five healthcare tenants means compliance obligations, tight change windows and low downtime tolerance were your normal operating condition. Fujifilm serves mid size to large businesses and government agencies, so a candidate who already treats change control as routine rather than as an inconvenience is worth more than one who has only worked forgiving environments. It also gives the after hours EDR rollout its real weight, that window was tight because the client was clinical, not because someone preferred it.
- **Check whether you used Atera's Microsoft 365 integration.** If you handled user creation, licence assignment or mailbox tasks through it, that is a partial answer to your biggest gap and it is currently going unclaimed.
- **Spend thirty minutes on Exchange Online and SharePoint basics.** Specifically shared mailbox versus distribution list versus Microsoft 365 group, Send As versus Send on Behalf, and what happens to OneDrive content after an account is deleted. This is the highest value half hour available to you, because it is your only real must have gap and these are the three questions that get asked about it.
- **Have the SaltStack detail available but do not lead with it.** Essential Eight configuration baselines across 1,000 plus endpoints is real experience and it is not on the version of the resume Fujifilm has, so it is fresh material. Deploy it if the conversation opens toward automation, scale or documentation. Leading with it makes the overqualification concern worse rather than better.
- **Rehearse Q2 out loud twice.** Your knowledge holds under pressure but delivery is where things slip, and Q2 is the one answer where a stumble reads as evasion rather than nerves.

### During the interview

- Lead with the service desk substance and let the security background be the bonus. Craig is a support manager hiring for a queue, not a security lead. The Elastic and EDR work is a differentiator but it is not the headline.
- When you do not know something, say so plainly and follow it with how you would approach it. Craig has interviewed enough service desk engineers to recognise improvisation instantly, and honesty from a candidate at this level reads as competence rather than weakness.
- Answer with what you actually did rather than what the correct process is. A support manager can tell the difference between a remembered incident and a described procedure within about two sentences.
- Networking is where you should be visibly better than the shortlist. Q9 and Q10 are your questions. Do not rush them.
- The ad asks for a vibrant personality. Energy and warmth in delivery carry real weight in a customer facing MSP role and it is easy for a technically strong candidate to arrive flat.

### Closing

- Ask about the escalation path and the PSA stack, both are genuinely useful to you and both signal you are thinking about the job rather than the offer.
- Confirm working rights explicitly if it has not come up, since the resume does not state visa status and it is a hard gate for this employer.
- Send a short note within 24 hours referencing something specific from the conversation rather than a generic thank you.

---

*Prepared as a mock interview practice aid based on the Fujifilm MicroChannel job description, the resume submitted for this role, and the interviewer's background.*
