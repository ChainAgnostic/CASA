# **Chain Agnostic Standards Alliance**

The Chain Agnostic Standards Alliance (CASA) is a collection of working groups dedicated blockchain protocol-agnostic standards. CASA also publishes [Chain Agnostic Improvement Proposals](https://github.com/ChainAgnostic/CAIPs) which describe standards created by the different working groups.

### **Table of Contents**

- [Purpose](#purpose)
- [Regular Meetings](#regular-meetings)
- [Explicit and Implicit Agendas](#explicit-and-implicit-agendas)
- [Discord Server](#discord-server)
- [Working Groups](#groups)
- [Organizational Structure](#organizational-structure)
- [Members](#members)
- [Join CASA](#join-casa)


## **Purpose**

CASA is a self-organized and autonomous alliance of crypto-blockchain developers and enthusiasts. Its aim to create standards which support interoperability and facilitate communication between blockchain protocols, software and companies.

CASA organizes working groups where proposals are debated, drafted and submitted as CAIPs for the purpose implementation and community adoption.

## **Regular Meetings**

All CASA stakeholders are invited to join our regular editorial meetings every four weeks, as well as regular meetings of the more focused topical working groups, which meet every 2 or every 4 weeks depending on the consensus of the group. These take place on jitsi, and a calendar can be found [here](https://bit.ly/thepubliccasacalendar) (also [here](https://bit.ly/thecasacalendar) for Google Calendar users). Where possible, high-level minutes are taken, and entered into the notes as [closed issues](https://github.com/ChainAgnostic/CASA/issues?q=is%3Aissue+is%3Aclosed) on this repo.

We also have periodic in-person meetings, to onboard new participants and, where possible, to advance working group progress. For information on these, see the `Gatherings` repository.

#### **Explicit and Implicit Agendas**

1. Explicit agenda items, if any have been set by issues in the `meetings/` repo (e.g., instance, a working group requests the whole community's input on a decision).
1. Implicit agenda: PRs in the `CAIPs/` repo that have been marked as "next meeting" or "merge soon" by the `CAIPs/` codeowners and/or Maintainers.
1. Implicit agenda: Issues in the `CAIPs/` repo that have been marked as "next meeting", as time allows.
1. Housekeeping, agenda requests for the following meeting, and open discussion.

*Note: the purpose of the `next meeting` tag is to allow codeowners to prioritize or stack-rank additions. Codeowners and the broader membership alike are requested to use them to prioritize them in their review process to allow swift review. Approval by any 2 codeowners is enough to merge at a future meeting. In cases where a timely merge is desired, codeowners may also chose to apply a `merge soon` tag, which is a way of requesting more review for an approved PR (and avoid a valid PR sitting unmerged across multiple meetings for lack of discussion).*

## **Discord Server**

For those who prefer realtime/social-style communications, we also run a Discord server, which is secondary and non-archival-- it can be found using [this Discord invite link](https://discord.gg/-remove-this-KxqKHppC39) _(note: this link has a spam/crawler deterrent that requires manual removal)_.

## **Working Groups**

### **List of working groups**

| Working Group | Status | Description | 
| :------------ | :----- | :---------- | 
| `CAIPs discussion` | Standing | CAIPs are always being iterated and refined and introduced! | 
| `Json RPC`         | Active | Feature discovery and "session" model for dApps and wallets  | 
| `Browser Security` | Active | Working within the Browser protocols and data models | 
| `CACAOs & AuthZ`     | Active | Authorization models and token/receipt formats for Web3 | 
| `Chain Id`         | Inactive | TBC         | 
| `Account Id`       | Inactive | TBC         | 
| `Asset Id`         | Inactive | TBC         | 
| `Asset Registry`   | Inactive | TBC         | 

### **How to form a new working group**

1. Join CASA.
2. Create a description that explains the goal of your working group and related CAIP(s).
3. Submit a Pull Request to the CASA repository adding your working group.
4. Propose your working group at the next CASA meeting. If approved, your PR will be merged, and your working group meeting schedule will be added to the CASA calendar.
5. Recruit participants for your working group.

## **Organizational Structure**

CASA participants are structured into three groups:

| Role           | Description                                                                                     |
| :------------- | :---------------------------------------------------------------------------------------------- |
| Members        | All participants who contribute in any form, including github review. Expected to participate in one or more topical working groups. |
| Working Groups | Topical clusters of CAIPs and namespaces. These change over time according to activity          |
| Editors/"Codeowners" | A subset of membership including the authors of accepted CAIPs committed to ongoing review and maintainance of the CAIPs and namespaces |
| Board | Governing/steering body of core members guiding the organization and making high-level strategic decisions about its execution of its mission |
| Executive Director | Drive and oversee operations, budget, editorial processes, and events |
| Treasurer (proposed) | Oversight and reporting on any external grants or donations |

### Current Board Membership

- Pedro Gomes @pedrouid (WalletConnect Founder),
- Ligi @ligi (Independent),
- Joel Thorstenssen @oed (Ceramic Founder),
- Gregory Rocco @obstropolos (Spruce Founder),
- Olaf Tomalka @ritave (MetaMask Snaps Lead),
- Boris Mann @bmann (Fission Founder),
- Chairman/Tiebreaker: Juan Caballero @bumblefudge (Acting Executive Director, Independent)

## **Members**

Below, please find a list of all members and their organizations.

| Organizations | Members | Status | Working groups |
| :------------ | :------ | :----- | :------------- |
| ChainAgnostic | Ligi ([@ligi](https://github.com/ligi)), Pedro Gomes ([@pedrouid](https://github.com/pedrouid)), Antoine Herzog ([@antoineherzog](https://github.com/antoineherzog)), Amadeo Pellicce ([@pellicceama](https://github.com/pellicceama)) | Maintainer | All Working groups |
| [Epicenter](https://epicenter.tv) | Sebastien Couture ([@seb2point0](https://github.com/seb2point0)) | Member     | CAIPs discussion   |
| Tally | Tarrence ([@tarrencev](https://github.com/tarrencev)) | Maintainer (go-caip) | All Working groups |
| [Ceramic](https://ceramic.network) | Joel Thorstensson ([@oed](https://github.com/oed)), Sergey Ukustov ([@ukstv](https://github.com/ukstv))  | Member | All Working groups |
| [Spruce](https://spruceid.com) | Wayne Chang ([@wyc](https://github.com/wyc)), Gregory Rocco ([@obstropolos](https://github.com/obstropolos)), Oliver Terbu ([@awoie](https://github.com/awoie)) | Member | CAIPs discussion |
| [Learning Proof UG](https://learningproof.xyz) | Juan Caballero ([@bumblefudge](https://github.com/bumblefudge)) | Maintainer | CAIPs |
| [Block](https://block.xyz) | Gabe Cohen ([@decentralgabe](https://github.com/decentralgabe)), Daniel Buchner ([@csuwildcat](https://github.com/csuwildcat)), Moe Jangda ([@mistermoe](https://github.com/mistermoe)) | Member | All Working groups |
| [SKALE Network](https://skale.network) | Chadwick Strange ([@cstrangedk](https://github.com/cstrangedk)) | Member | All Working Groups |
| [Metagov](https://metagov.org) | Joshua Tan ([@thelastjosh](https://github.com/thelastjosh)) | Member | All Working Groups |
| [kycDAO](https://kycdao.xyz) | Balázs Némethi ([@nembal](https://github.com/nembal)) | Member | All Working Groups |
| [cheqd](https://www.cheqd.io/) | Ross Power ([@rosspower11](https://github.com/rosspower11)) | Member | All Working Groups |
| [Fission](https://fission.codes/) | Boris Mann ([@bmann](https://github.com/bmann)), Brooklyn Zelenka ([@expede](https://github.com/expede)), Ryan Betts ([@depatchedmode](https://github.com/depatchedmode)), Andy Vivash ([@avivash](https://github.com/avivash)) | Member | All Working Groups |
| [Danube Tech](https://danubetech.com/) | Markus Sabadello ([@peacekeeper](https://github.com/peacekeeper)) | Member | All Working Groups |
| [Obvious](https://obvious.technology/) | Jebu Ittiachen ([@jebu](https://github.com/jebu)) | Member | All Working Groups |
| [Dynamic](https://www.dynamic.xyz/) | Itai Turbahn ([@turbahn](https://github.com/turbahn)), Paolo Lim ([@paololim](https://github.com/paololim)) | Member | All Working Groups |
| [Notabene](https://www.notabene.id/) | Andrés Junge ([@ajunge](https://github.com/ajunge)) | Member | All Working Groups |
| [Ledger](https://www.ledger.com/) | Rod Carraresi ([@carraresi](https://github.com/carraresi)) | Member | All Working Groups |
| [ITSA](https://www.itsa.global/) | Valentin Seehausen ([@valleXYZ](https://github.com/valentin-seehausen)) | Member | All Working Groups |
| [Protocol Labs](https://protocol.ai/) | Eva Shon ([@eshon](https://github.com/eshon)) | Member | All Working Groups |
| [Fireblocks](https://www.fireblocks.com/) | Oren Yomtov ([@orenyomtov](https://github.com/orenyomtov)), Arik Galansky ([@arikg](https://github.com/arikg)) | Member | All Working Groups |
| [MetaMask](https://metamask.io/) | Erik Marks ([@rekmarks](https://github.com/rekmarks)), Olaf Tomalka ([@ritave](https://github.com/ritave)) | Member | All Working Groups |
| [Shovel Company](https://shovel.company/) | Prashant Mittal ([@prashant3863](https://github.com/prashant3863)) | Member | All Working Groups |
| [Status](https://status.im/) | Anthony Laibe ([@alaibe](https://github.com/alaibe)), Iuri Matias ([@iurimatias](https://github.com/iurimatias)), John ([@john-44](https://github.com/john-44)) | Member | All Working Groups |

## **Join CASA**

Submit a Pull Request to this repository adding yourself as a member in the table above.

Once a maintainer has confirmed you have completed this step, they will merge your PR.  We recommend checking that your Github email is up-to-date and you are "Watching" these repos:
 *  [Gatherings](https://github.com/ChainAgnostic/Gatherings) to stay up to date with in person gatherings
 * [CASA](https://github.com/ChainAgnostic/CASA)  to stay up to date with the organisation and scheduled calls
  * [CAIPs](https://github.com/ChainAgnostic/CAIPs)
  * [namespaces](https://github.com/ChainAgnostic/namespaces)

