# Community Canvas (Structure layer) & Governance

> Status: 🚧 In progress

> `⏩` marks subsections that are deferred until later; skip them for now.
> **[§5.2 Governance model](#52-governance-model) is the exception: it is adopted, in force today, and the binding core of this entire worksheet.**
> Every other section, in this file and the others, operates under the decision rules it sets. Read it first.

## 5.1 Legal structure decision

**We will operate as:**

- [x] Unincorporated meetup (months 0–12) - **current**
- [ ] Ontario ONCA non-profit ❓ (TBD)
- [ ] Federal CNCA non-profit
- [ ] Ontario co-operative (only if member-ownership is central)
- [ ] Affiliate / SIG under OpenHW Foundation
- [ ] CRA registered charity

**Rationale:** Start lean and unincorporated to validate the community without overhead. If the group wants it and sees a benefit, we incorporate under ONCA once activity is steady and a concrete trigger appears (bank account, grant eligibility, liability cover, contracts).

**⏩ Incorporation execution checklist (Ontario nonprofit path):**

- [ ] Reserve / confirm corporate name (NUANS report if required)
- [ ] Articles of Incorporation filed under ONCA ($200-300?)
- [ ] Registered office address set
- [ ] Bylaws drafted (CLEO Bylaw Builder) and legally reviewed
- [ ] Organizational / first directors meeting held (appoint officers, adopt bylaws, authorize bank account)
- [ ] CRA business number obtained
- [ ] Dissolution / asset-distribution clause in bylaws (remaining assets pass to a qualified entity; required by ONCA and for charitable status)

## 5.2 Governance model

_This section is adopted and binding. It defines how every decision in RVO gets made and what is expected of the people who make them. When any other section is unclear about who decides or how, this one governs._

**Who this binds ("organizing team"):** today, the organizing team; if incorporated, the steering group. These are the people who hold decision authority under this section, defined in [§5.3](#53-steering-group--board-composition) and constituted at incorporation per [§5.1](#51-legal-structure-decision). They are distinct from the operational roles in [§4.5](04-community-experience.md#45-roles): doing a job (running the meetup, moderating Discord) is not the same as holding a governing seat.

Very importantly, **the organizing team should help ensure the entire extended RVO community is aware and tries to adhere to this model as well.**
The organizing team are expected to act as examples, upholding this model completely.

In the language of open-source governance, RVO runs as a self-appointing organizing team: the founding members hold and renew the governing seats themselves ([§5.3](#53-steering-group--board-composition)). If incorporation is done in the future, this becomes an elected board under ONCA ([§5.1](#51-legal-structure-decision)).
RVO delegates reversible day-to-day work to whoever picks it up (Tier 1 below) while holding the consequential decisions to the tiers above it.

> **Organizing team vs. steering group.**
>
> These are the same group, but at two different stages.
> Today, while RVO is unincorporated, it is the *organizing team*: the founders and members who hold and renew the seats themselves.
> If RVO incorporates under ONCA ([§5.1](#51-legal-structure-decision)), it becomes the *steering group*, a formal elected board bound by ONCA's quorum and voting rules ([§5.3](#53-steering-group--board-composition)).
> The steering group only exists in that future incorporated case.
> Every rule this section places on the organizing team applies to the steering group as well, and even more strictly, since a formal board also carries legal duties on top of them.

Decisions fall into three tiers. Every decision belongs to exactly one tier, and the escalation rules below decide which.

---

**Tier 1 - Day-to-day (default to action + lazy consensus).**

Scope: small, reversible, low-stakes calls, the kind a single person can undo cheaply if it goes wrong.

Rule: whoever is doing the work decides and acts. Anyone may act, provided the action is genuinely reversible and low-cost. For anything announced ahead of time, lazy consensus applies: the proposal is agreed unless a reasoned objection lands in the relevant Discord channel within **48 hours**. "If you want to do it, do it, be excellent."

---

**Tier 2 - Operational (organizing team consent).**

Scope: programs, venues, invited speakers, spending under the escalation threshold, partnerships, and anything said or committed in the group's name.

Rule: the proposer posts a written proposal to the organizing team channel; it proceeds unless a member of the organizing team raises a valid objection within a **48-hour** objection window. A valid objection is reasoned, names a concrete harm to the group's aims, values ([§3.4](03-community-identity.md#34-values-37-max)), or Code of Conduct ([§4.6](04-community-experience.md#46-rules-the-explicit-ones)), and comes with a workable path forward. "I'd do it differently" or personal preference is not a valid objection and does not block. Silence past the window counts as consent. Record the outcome in the decision log ([§7.1](07-logs.md#71-pre-launch-decision-log)).

---

**Tier 3 - Strategic (legal form, incorporation, bylaws, dissolution, spending over the escalation threshold).**

Rule: until incorporated, these require full organizing team consensus, meaning every member of the organizing team actively agrees, not merely declines to object. Once incorporated, they require a board vote with quorum per ONCA. These are the decisions that are hard or impossible to reverse, so they carry the highest bar.

---

**Escalation (a decision moves up a tier if ANY of these apply).**

If something is hard to reverse, move the decision a tier up. Examples include: a decision that commits money, makes an external-facing commitment (a partnership, a sponsor arrangement, a public statement in the group's name), or it touches legal standing, the values, or the Code of Conduct. When it is unclear which tier a decision belongs to, treat it as the higher tier.

---

**The commons.**

A handful of assets are held by the community as a whole, not by whoever happens to be holding them: the RISC-V Ottawa name and brand, the organization itself and its legal standing, member data ([§5.7](#57-data)), and the group's standing relationships and partnerships. Spending or committing any of these is a group decision no matter how small it feels, so it is never a Tier 1 solo call even when the individual act looks small and reversible; treat it as Tier 2, or Tier 3 if it is hard to undo. This does not reach a member's own project code or personal opinions, which stay Tier 1 (default to action); it applies only when someone draws on what the group collectively owns.

---

<!--**Escalation threshold (dollar amount where a decision moves up a tier):**
- Tier 1 -> Tier 2: **$100 (proposed)** per item.
- Tier 2 -> Tier 3: **$1,000 (proposed)** per item or commitment.-->

**What is expected of the organizing team (binding):** holding a governing seat carries obligations, not just authority. Every member of the organizing team MUST:

- Review and respond to Tier 2 and Tier 3 proposals within the stated window. **Sustained non-response is not a silent veto; a member who cannot keep up is expected to say so and step aside so the seat can be filled**.
- Block only with a valid objection as defined above, and always propose an alternative rather than merely refusing.
- Disclose conflicts of interest and recuse from the decision, especially members affiliated with a vendor or sponsor. This upholds the vendor-neutral value ([§3.4](03-community-identity.md#34-values-37-max)) and the conflict-of-interest rule in [§4.6](04-community-experience.md#46-rules-the-explicit-ones).
- Default to open: decisions about public matters are made in the open and recorded, per the decision log ([§7.1](07-logs.md#71-pre-launch-decision-log)) and the transparency commitments in [§5.8](#58-transparency). Private handling is reserved for personal data and incidents.
- Uphold the values ([§3.4](03-community-identity.md#34-values-37-max)) and the Code of Conduct ([§4.6](04-community-experience.md#46-rules-the-explicit-ones)) in how decisions are made, not only in what is decided.
- Share the load and honor succession and term limits so no single person carries the group. This is a governing duty because the biggest structural risk to RVO is sole-founder dependence (see the Lead stage in [§4.1](04-community-experience.md#41-member-journey) and the risks register in [§6.4](06-operational-plan.md#64-risks-register)).

## ⏩ 5.3 Steering group

The formal steering group (an elected board) is constituted at incorporation (see [§5.1](#51-legal-structure-decision)); until then the organizing team serves this function. Seats below are placeholders for that point. All seats carry a 2-year term.

**Chair**

- Currently held by: TBD (steering group for now)
- Term ends: TBD

**Treasurer**

- Currently held by: ⏩ (not needed until we incorporate)
- Term ends: TBD

**Secretary**

- Currently held by: ⏩ (not needed until we incorporate)
- Term ends: TBD

**Director-at-large**

- Focus area: Programs & Community (meetups, workshops, study cohorts, the community project, member engagement and retention)
- Currently held by: TBD
- Term ends: TBD

**Director-at-large**

- Focus area: Partnerships & Ecosystem (industry, academia, RISC-V International / OpenHW, sponsorship and independence)
- Currently held by: TBD
- Term ends: TBD

**Staggered terms?** `[x] Yes - half elected each year`

**Maximum consecutive terms:** 2 (proposed)

**Minimum directors per ONCA:** 3

**Public Benefit Corporation threshold ($10K/yr in donations \+ funding) - once we cross it, at least 1/3 of directors must not be employees:** noted `[ ]`

## ⏩ 5.4 Working groups / SIGs (deferred until 50+ members)

**Hardware**

- Trigger to launch: 50+ active members + a willing chair
- Chair candidate: TBD

**Software & Firmware**

- Trigger to launch: 50+ active members + a willing chair
- Chair candidate: TBD

**Education**

- Trigger to launch: 50+ active members + a willing chair
- Chair candidate: TBD

**Professional / Industry**

- Trigger to launch: 50+ active members + a willing chair
- Chair candidate: TBD

## 5.5 Financing (the layered model)

**Funding philosophy chosen (this is structural and hard to reverse):**

- [ ] **Dues-only** (max independence, slower growth. Examples: VHS, Protospace model)
- [ ] **Mixed: dues + grants + sponsorship** (faster scale, more compliance. Exmaples: Kwartzlab, OpenHW model)
- [ ] **Sponsor-led** (NOT recommended due to capture risk)
- [x] **No dues, ever** - a pure open community sustained by volunteers, grants, sponsorship, and donations. Membership is always free; participation is never gated behind payment.

**Year 1 funding mix (target % of total revenue):**

**Membership dues** - N/A (no dues, ever)

**Workshop fees (earned revenue)** - TBD (training and workshops are free for now)

**Corporate sponsorship**

- Target %: primary source
- Year 1 $: TBD
- Owner: TBD (sponsor / partnership lead)
- Status: idle

**Foundation grants**

- Target %: primary source
- Year 1 $: TBD
- Owner: TBD
- Status: idle

**Individual donations**

- Target %: minor / opportunistic
- Year 1 $: TBD
- Owner: TBD
- Status: not yet set up

**Product sales (dev boards, kits)** - TBD (no plan for this yet)

**Membership tiers:** Membership is free. There are no personal dues tiers; anyone can join and participate at no cost.

**Corporate sponsorship tiers** (sponsorship is support, not membership, and never buys editorial control - see [§3.4](03-community-identity.md#34-values-37-max)). Dollar amounts below are placeholders to refine:

**Corporate Bronze** ($1,000/year)

- What it includes: logo on website + recurring event mentions

**Corporate Silver** ($5,000/year)

- What it includes: Bronze + logo on event slides + a demo/speaking slot on a RISC-V topic

**Corporate Gold** ($15,000/year)

- What it includes: Silver + option to be provided with help for RISC-V related work from members + prominent placement

## 5.6 Spaces & tools

**🟢 Event discovery**

- Tool / platform: Luma
- Owner: Fatimata + Yusef
- Cost: $0 (free tier)
- Backup if it disappears: Meetup.com or Eventbrite

**🟢 Real-time chat**

- Tool / platform: Discord
- Owner: Yusef
- Cost: $0
- Backup if it disappears: Matrix or Zulip

**🟢 Code / project hosting**

- Tool / platform: GitHub org ([riscv-ottawa](https://github.com/riscv-ottawa))
- Owner: Yusef
- Cost: $0
- Backup if it disappears: GitLab or self-hosted Forgejo

**🟢 Website**

- Tool / platform: self-hosted interactive site ([riscvottawa.ca](https://riscvottawa.ca))
- Owner: Yusef
- Cost: ~$20/yr (domain)
- Backup if it disappears: one of the many cloud providers

**🟡 Newsletter**

- Tool / platform: Buttondown or Luma email (TBD)
- Owner: TBD
- Cost: $0 (free tier)
- Backup if it disappears: Mailchimp free tier

**🟢 Document storage**

- Tool / platform: GitHub repos + Google docs (for temporal things)
- Owner: everyone
- Cost: $0
- Backup if it disappears: local + git history

**🟢 Video calls**

- Tool / platform: Zoom or Discord (or Google Meet)
- Owner: Alfredo (Zoom account), Yusef (Discord)
- Cost: $0
- Backup if it disappears: Jitsi (self-hostable)

**🟢 Physical space**

- Tool / platform: in-kind university / Eclipse rooms
- Owner: TBD
- Cost: $0 (in-kind)
- Backup if it disappears: alternate partner venue

## 5.7 Data

**Member data we collect:** name, email, RSVP details (via Luma), Discord handle, newsletter email

**Where it's stored:** Luma, Discord, and the newsletter platform (each on their own infrastructure); survey results in a restricted shared sheet.

**Who has access:** organizers / comms lead only; demographic survey data kept aggregated and anonymized.

**Retention policy:** keep while a member is active; delete on request; purge stale contacts periodically.

**Compliance: PIPEDA (federal) and applicable Ontario privacy law reviewed?** `[ ]` (to review)

## 5.8 Transparency

**What we publish publicly:**

- [x] Organizers meeting notes
- [x] Strategic plan / roadmap (this worksheet)
- [x] Bylaws (if incorporated)
- [x] Annual financial summary (once applicable)
- [x] Code of conduct + enforcement log (anonymized)
- [x] Decisions log (see [§7](07-logs.md))

**What we keep private:**

- [x] Member personal data
- [x] Incident details (CoC)
- [x] Sensitive HR / contractor info

## ⏩ 5.9 Financial controls & accounting

_Distinct from 5.5 (where the money comes from). This is how we handle it responsibly._

**Bookkeeping tool & cadence (e.g. Wave, QuickBooks)** (owner: Treasurer)

- Decision: TBD

**Signing authority (two-signature rule for amounts over $TBD)** (owner: Treasurer)

- Decision: adopt a two-signature rule at incorporation; threshold TBD

**Annual budget approved before fiscal year** (owner: Board)

- Decision: TBD

**Financial report at every board meeting + AGM** (owner: Treasurer)

- Decision: TBD

**Reimbursement / expense process** (owner: Treasurer)

- Decision: TBD

**Nonprofit tax & filing obligations to confirm** (the CRA business number is part of the incorporation checklist in [§5.1](#51-legal-structure-decision)):

- [ ] Ontario corporate annual return (post-ONCA)
- [ ] GST/HST registration threshold understood ($50K small-supplier line)
- [ ] T1044 / NPO information return obligation checked
- [ ] T3010 charity return (only if we register as a charity)

## 5.10 Contributions, licensing, and IP

**Free to contribute.**

Before you contribute code, hardware designs, documentation, or any other material, confirm that you are legally free to do so. Your employment rules, contracts, NDAs, and IP obligations are your responsibility to confirm. We want what you bring to be yours to freely share. If you are unsure, check with your employer before getting involved. This is a self-attestation: participating means you are making it, there is nothing to sign. This follows from "the commons" in [§5.2](#52-governance-model), which keeps a member's own project code with the member. The group takes no assignment of your IP, so only bring what is actually yours to bring!

**Recommended licenses.**

RVO publishes our work openly ([§3.4](03-community-identity.md#34-values-37-max)). Here are suggested default licenses, given by the type of work:

- **Code and software:** Apache-2.0 or MIT
- **Hardware, RTL, gateware, and board designs:** Solderpad Hardware License 2.1
- **Documentation, curriculum, slides, and other written content:** CC BY-SA 4.0

A repository or workshop can pick a different license when there is a reason to, but these are the suggested defaults. License of course belong in the repos themselves (e.g., a `LICENSE` file), rather than only here.

**AI usage.**

You may use AI tools to help produce any type of contribution, but **you own the result**. You are responsible for it being license-compatible, properly attributed, accurate, and something you actually have the right to contribute under the license you've selected (ideally from those suggested above). It is recommended to disclose **substantial** AI-generated content, this ensures reviewers know what they are looking at and can gauge accordingly. It is also suggested that you **understand** the AI-generated code you are using, especially if you are committing it for code review by others.
