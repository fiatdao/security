# Overview

Our security is important. For this reason we have a number of public [audits](./audits), as well as private individual auditors. We also have a section for [disclosures](./disclosures) that we made public and we hope that others can help from our experience.

To deter black hats, we have to set up a correct incentive structure. We have a bounty system for bugs and bounties for security vulnerabilities.

If you want to contact us directly, please use a private communication channel. We will try to respond to you as soon as possible.

The best people to talk to when you're ready with your report are:

- [Daniel Luca](https://twitter.com/cleanunicorn)
- [0xJohannes](https://twitter.com/0xjohannes)

The scope, terms and rewards remains at the discretion of the team. We will try to keep the bounty system as open as possible.

## Scope

Our program includes vulnerabilities and bugs in our core system. Bugs in the website, or 3rd party libraries are not eligible.

Repositories eligible for bug bounties:

- [fiat](https://github.com/fiatdao/fiat)
- [vaults](https://github.com/fiatdao/vaults)
- [actions](https://github.com/fiatdao/actions)
- [guards](https://github.com/fiatdao/guards)
- [delphi](https://github.com/fiatdao/delphi)

The following void the eligibility:

- Bugs in any 3rd party contract, library or platform that interacts with FIAT DAO;
- Vulnerabilities to DNS, IPFS, or any other system that is not FIAT DAO;
- Vulnerabilities related to servers or websites;
- Already reported bugs or vulnerabilities;
- Exploitation or the of the system;
- Engaging in any unlawful conduct when disclosing the bug, threats, demands, or other coercive action;
- Submitting a separate vulnerability caused by an underlying issue that is the same as the one being reported;
- Being one of the audit companies we worked with, except on specific cases, where the we determine the vulnerability was not kept private to retrieve the bounty afterwards;
- Gas optimization by adding `payable` to methods.

Eligibility is determined by:

- Previously unreported vulnerability or bug;
- Vulnerabilities must be unique and not already described in any previous audit;
- Sufficient technical knowledge to describe the identified problem to the team;
- Communication is completely private, no public information is shared until the team deals with the issue; (public disclosure is possible after confirmation from our team);
- Bugs in our core system;
- Locking funds in the system (loss of funds);

The eligibility, score and terms related to the rewards are at the team's discretion.

## Disclosure process

Any vulnerability or bug discovered must be reported as soon as possible (ideally within 24 hours following the discovery). It's also imperative that the vulnerability was not used to exploit our system in any way prior or after the disclosure.

It is mandatory to keep the vulnerability private and to help the team understand the underlying problem in order to fix it.

## Rewards

All submissions are evaluated by the team on a case by case basis. Rewards are determined by the team and have the following factors: impact, likelihood, proof of concept / instructions for reporductibility, overall quality of report, identifying the problem in our code, collaboration process. 

A detailed report and a good collaboration process is likely to increase the reward size.

Likelyhood: low, med, high
Impact: low, med, high


<!-- ---

Alternatively we run external bug bounties. Following are the current running bug bounty programs:

## Ongoing bounties

- Immunefy
- Code4rena
- Hats.Finance

### Immunefy

- Link
- Description
- ...
 -->
