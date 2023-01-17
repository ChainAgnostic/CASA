# **Chain Agnostic Standards Alliance**

The Chain Agnostic Standards Alliance (CASA) is a collection of working groups dedicated blockchain protocol-agnostic standards. CASA also publishes [Chain Agnostic Improvement Proposals](https://github.com/ChainAgnostic/CAIPs) which describe standards created by the different working groups.

### **Table of Contents**

- [Purpose](#purpose)
- [Organizational Structure](#structure)
- [Meetings](#meetings)
- [Working Groups](#working-groups)
- [Members](#members)
- [Join CASA](#join-casa)

<a name="purpose"></a>

## **Purpose**

CASA is a self-organized and autonomous alliance of crypto-blockchain developers and enthusiasts. Its aim to create standards which support interoperability and facilitate communication between blockchain protocols, software and companies.

CASA organizes working groups where proposals are debated, drafted and submitted as CAIPs for the purpose implementation and community adoption.

<a name="structure"></a>

## **Organizational Structure**

CASA participants are structured into three groups:

| Role           | Description                                                                                     |
| :------------- | :---------------------------------------------------------------------------------------------- |
| Members        | All participants. Expected to participate in working groups.                                    |
| Working Groups | Collections of members tackling specific areas of interest.                                     |
| `CAIPs/` codeowners | Subset of authors of accepted CAIPs committed to ongoing review and maintainance of CAIPs |
| Maintainers    | Members running CASA meetings (excluding working group) and ensuring overall process integrity. |

<a name="meetings"></a>

## **Meetings**

All CASA meetings are open to the public, and non-members are welcome to attend respectfully/non-disruptively.  In particular, the `editorial` meetings are a good on-boarding and overview of all the more specific workstreams and conversations happening in parallel.

Meetings can be seen on the `https://bit.ly/` links `thecasacalendar` (subscribeable via Google) and `thepubliccasacalendar` (display-only).  See individual events for teleconferencing links and agenda links.

### **Explicit and Implicit Agendas**

1. Explicit agenda items, if any have been set by WG participants, can be found linked from events pages on the calendar.
1. The implicit agenda, in addition to or absence of explicit agenda, is to review outstanding/mergeable PRs, active issues, draft PRs, and topics of general interest, in that order.  
1. Chairs or facilitators should always leave time for housekeeping, agenda requests for the following meeting, and open discussion.

*Note: the purpose of the `next meeting` tag is to allow codeowners to prioritize or stack-rank additions. Codeowners and the broader membership alike are requested to use them to prioritize them in their review process to allow swift review. Approval by any 2 codeowners is enough to merge at a future meeting. In cases where a timely merge is desired, codeowners may also chose to apply a `14-day merge` tag, which is a way of requesting more review for an approved PR (and to avoid a valid PR sitting unmerged across multiple meetings for lack of discussion).*

## **Working Groups**

### **List of working groups**

| Working Group | Scope | Meeting Frequency | Chair |
| :------------ | :----- | :----- |
| `Editorial` | New CAIPs and Namespaces | every 4 weeks | @bumblefudge |
| `Addressing` | CAIP-2, -10, -19; URN/URI systems | Sporadic/By request | @bumblefudge |
| `Json RPC`  | CAIP-25, -27 | every 2 weeks | @hmalik88 |
| `CACAO/AuthZ` | CAIP-74, -122, -168; [varint]() & [multidid](), interop with UCAN and ZCAP-LD | every 2 weeks | @bumblefudge/TBD | 
| `Browser Security` | CAIP-169, -171 | Sporadic/By request | @kdenhartog |

### **How to form a new working group**

1. Join CASA.
2. Create a description that explains the goal of your working group and related CAIP(s).
3. Submit a Pull Request to the CASA repository adding your working group.
4. Propose your working group at the next CASA editorial meeting. If approved, your PR will be merged, and your working group meeting schedule will be added to the CASA calendar.
5. Recruit participants for your working group.

## **Members**

Below, please find a list of all members and their organizations.

| Organizations | Members | Status | Working groups |
| :------------ | :------ | :----- | :------------- |
| ChainAgnostic | Ligi ([@ligi](https://github.com/ligi)), Pedro Gomes ([@pedrouid](https://github.com/pedrouid)), Antoine Herzog ([@antoineherzog](https://github.com/antoineherzog)), Amadeo Pellicce ([@pellicceama](https://github.com/pellicceama)) | Maintainer | All Working groups |
| [Epicenter](https://epicenter.tv) | Sebastien Couture ([@seb2point0](https://github.com/seb2point0)) | Member     | CAIPs discussion   |
| Tally | Tarrence ([@tarrencev](https://github.com/tarrencev)) | Maintainer (go-caip) | All Working groups |

## **Join CASA**

To pledge support for the mission and have your company listed as a member, please submit a Pull Request to this repository adding yourself as a member in the table above.

Once a maintainer has confirmed you have completed this step, they will merge your PR and we will look forward to your attendance at meetings 
