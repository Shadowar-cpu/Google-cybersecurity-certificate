# Module 2: The evolution of cybersecurity

Course: Foundations of Cybersecurity  
Coursework status: In progress  
Study point: Completed items through Introduction to the eight CISSP security domains, Part 2  
Notes status: Draft for review

## Why the history matters

Past attacks show how security problems can spread and affect people. They also give security teams examples to learn from.

This module introduces past attacks and the eight security domains in the [course outline](https://www.coursera.org/learn/foundations-of-cybersecurity).

## Historical examples

### Brain — 1986

Brain was an early virus on the DOS platform. F-Secure records its detection in January 1986 in its [Brain threat description](https://www.f-secure.com/v-descs/brain).

Malware was already a problem before today’s apps and online services.

### Morris worm — 1988

The Morris worm spread between computers on the early internet and made many of them unusable. A worm can spread without attaching to a separate host program.

The [FBI’s account of the Morris worm](https://www.fbi.gov/history/cases-and-criminals/morris-worm) describes its rapid spread and the disruption it caused.

An attack can stop people from doing their work even when it does not steal their information.

### ILOVEYOU, also called the Love Bug — 2000

This worm spread through an email attachment and used victims’ address books to spread further. The [FBI’s testimony on the Love Bug](https://archives.fbi.gov/archives/news/testimony/cyber-security) describes how quickly it reached people and organisations.

A message can use curiosity or trust to get someone to open something harmful.

### Equifax breach — 2017

Equifax identified a vulnerability in Apache Struts as the entry point into an affected application. The FTC later described failures to apply and verify a patch, along with other security failures.

These details appear in [Equifax’s incident account](https://investor.equifax.com/news-events/press-releases/detail/237/equifax-releases-details-on-cybersecurity-incident) and the [FTC’s breach findings](https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach).

Telling someone to install an update is only part of the work. The organisation also needs to check that the affected systems were found and the update was applied.

## Malware and social engineering

Malware is harmful software or code. Different types behave differently.

| Type | Simple meaning |
| --- | --- |
| Virus | Copies itself by infecting a host, such as another program. |
| Worm | Can copy itself and spread between systems without a separate host program. |
| Trojan | Appears useful or legitimate while carrying out harmful actions. |
| Spyware | Secretly gathers information. |

These are short explanations of types described in the [NIST malware glossary](https://csrc.nist.gov/glossary/term/malware). The [FBI’s Morris worm account](https://www.fbi.gov/history/cases-and-criminals/morris-worm) also explains the difference between viruses and worms.

Social engineering means manipulating a person into taking an action or sharing information. Phishing uses deceptive messages to do this. A phishing message can lead to stolen login details, malware or another harmful action.

The [CISA glossary](https://niccs.cisa.gov/about-niccs/glossary) and [NIST phishing guide](https://www.nist.gov/itl/smallbusinesscyber/guidance-topic/phishing) explain these ideas.

## The eight CISSP security domains

The domains divide security work into broad areas. One incident can involve several domains.

| Domain | Simple meaning | Practice example |
| --- | --- | --- |
| 1. Security and Risk Management | Choosing priorities, rules and responses to risk. | Setting rules for protecting customer records. |
| 2. Asset Security | Protecting valuable information throughout its life. | Restricting access to an employee file. |
| 3. Security Architecture and Engineering | Considering security when designing systems. | Choosing secure default settings. |
| 4. Communication and Network Security | Protecting connections and data moving between systems. | Separating guest Wi-Fi from office systems. |
| 5. Identity and Access Management | Checking identities and controlling allowed access. | Removing access when an employee leaves. |
| 6. Security Assessment and Testing | Checking whether security protections work. | Testing whether access restrictions work properly. |
| 7. Security Operations | Monitoring systems and handling security incidents. | Investigating an unusual sign-in alert. |
| 8. Software Development Security | Considering security when creating and maintaining software. | Checking code before a release. |

These are short summaries based on the [official ISC2 domain outline](https://www.isc2.org/certifications/cissp/cissp-certification-exam-outline). The practice examples are made up for revision.

## My employee-login example

An attacker can get an employee’s password and try to log in as that employee.

The team can check the login records, including the time, IP address, location estimate and device information when available. If something looks unusual, the team can investigate.

An unusual location is a clue to check. It does not prove by itself that the person is an attacker.

The system can also ask for multi-factor authentication, or MFA. This uses different types of proof, such as a password and a registered authenticator.

Knowing the password alone may then be insufficient to log in. MFA reduces risk, but it does not guarantee that every attack will be stopped. The different factors are explained in the [NIST digital identity glossary](https://pages.nist.gov/800-63-4/sp800-63/glossary/).

In this practice example:

- Checking who can log in connects to identity and access management.
- Investigating the login records connects to security operations.

These connections follow the domain descriptions in the [ISC2 outline](https://www.isc2.org/certifications/cissp/cissp-certification-exam-outline).

This example is based on my earlier explanation and is for revision.

## Activity completed

**Test your knowledge: The history of cybersecurity — 100%**, as shown in my Coursera progress.

## Where I am now

Coursera marks both CISSP domain introduction videos complete. Module 2 is still in progress.

My next item is **Determine the type of attack**.

The remaining readings, knowledge check, review and Module 2 challenge are listed as pending in my [course tracker](https://github.com/Shadowar-cpu/Google-cybersecurity-certificate/blob/main/README.md).

## Questions for my own revision

- How is a worm different from a virus?
- Why does a patch need to be checked after it is assigned?
- Which security domains connect to the employee-login example?
- What would make me investigate a login without assuming straight away that it is an attack?
