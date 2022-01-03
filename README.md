# **Chain Agnostic Standards Alliance**

The Chain Agnostic Standards Alliance (CASA) is a collection of working groups dedicated blockchain protocol-agnostic standards. CASA also publishes [Chain Agnostic Improvement Proposals](https://github.com/ChainAgnostic/CAIPs) which describe standards created by the different working groups.

### **Table of Contents**

- [Purpose](#purpose)
- [Organizational Structure](#structure)
- [Meetings](#meetings)
- [Working Groups](#groups)
- [Members](#members)
- [Join CASA](#join)

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

### **CASA Meetings**

All CASA stakeholders are invited to join a meeting every two weeks, for the purpose of:

1. Evaluating CAIPs, registries, and related publications
2. Sharing progress in individual working groups
3. Proposing the creation of new working groups

Since CASA meetings are primarily intended to sharing the working groups progress, at least one member from each active working group is expected to attend, or entire working groups if the WG has topics agenda'd for a given meeting.

#### **Explicit and Implicit Agendas**

1. Explicit agenda items, if any have been set by issues in the `meetings/` repo (e.g., instance, a working group requests the whole community's input on a decision).
1. Implicit agenda: PRs in the `CAIPs/` repo that have been marked as "next meeting" or "merge soon" by the `CAIPs/` codeowners and/or Maintainers.
1. Implicit agenda: Issues in the `CAIPs/` repo that have been marked as "next meeting", as time allows.
1. Housekeeping, agenda requests for the following meeting, and open discussion.

*Note: the purpose of `next meeting` and `merge soon` tags is to allow codeowners to prioritize or stack-rank additions. Codeowners and the broader membership alike are requested to use them to prioritize them in their review process to allow swift review. Approval by any 2 codeowners is enough to apply a `merge soon` tag, which means the PR may be merged as-is as soon as the next meeting.*

### **Working Group Meetings**

CASA members self-organize into topic-specific working groups. Individual working groups set their own meeting schedule and communicate in designated communication channels. We expect working groups to meet frequently enough to share their progress at CASA meetings.

The CASA meetings note template may help keep stakeholders aligned.

<a name="groups"></a>

## **Working Groups**

### **List of working groups**

| Working Group | Status | Description | Repository | CAIP |
| :------------ | :----- | :---------- | :--------- | :--- |
| `CAIPs discussion` | Active | TBC         | TBC        | [All](https://github.com/ChainAgnostic/CAIPs) |
| `Chain Id`         | Active | TBC         | TBC        | [CAIP-2](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-2.md) |
| `Account Id`       | Active | TBC         | TBC        | [CAIP-10](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-10.md) |
| `Asset Id`         | Active | TBC         | TBC        | [CAIP-19](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-19.md) |
| `Json RPC`         | Active | TBC         | TBC        | [CAIP-24](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-24.md), [CAIP-25](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-25.md) |
| `Asset Registry`   | Active | TBC         | TBC        | [CAIP-19](https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-19.md) |

### **How to form a new working group**

1. Join CASA.
2. Create a description that explains the goal of your working group and related CAIP(s).
3. Submit a Pull Request to the CASA repository adding your working group.
4. Propose your working group at the next CASA meeting. If approved, your PR will be merged, and your working group meeting schedule will be added to the CASA calendar.
5. Recruit participants for your working group.

<a name="members"></a>

## **Members**

Below, please find a list of all members and their organizations.

| Organizations | Members | Status | Working groups |
| :------------ | :------ | :----- | :------------- |
| ChainAgnostic | Ligi ([@ligi](https://github.com/ligi)), Pedro Gomes ([@pedrouid](https://github.com/pedrouid)), Antoine Herzog ([@antoineherzog](https://github.com/antoineherzog)), Amadeo Pellicce ([@pellicceama](https://github.com/pellicceama)) | Maintainer | All Working groups |
| [Epicenter](https://epicenter.tv) | Sebastien Couture ([@seb2point0](https://github.com/seb2point0)) | Member     | CAIPs discussion   |
| Tally | Tarrence ([@tarrencev](https://github.com/tarrencev)) | Maintainer (go-caip) | All Working groups |

<a name="Join"></a>

## **Join CASA**

CASA will begin meetings in 2021 as we wait for the initial working groups to form.

1. Submit a Pull Request to this repository adding yourself as a member in the table above.

Once a maintainer has confirmed you have completed this step, they will merge your PR and send you a welcome email containing your invitations to the **CASA Call Calendar** and **Discord**.
