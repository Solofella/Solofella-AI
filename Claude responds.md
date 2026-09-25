Chat #230 · September 25, 2026

**Not legal advice.** I am not a lawyer. This is general business information to prepare you for a conversation with a New York attorney, who should review both templates before you use them.

**Sources for this answer:** The New York Freelance Isn't Free Act points come from a web search I just ran (✅ HIGH). Everything else, including contract law, IP, FLSA, DTSA and trade secret points, is from training data and is ⚠️ UNVERIFIED: I am not certain it reflects current law. That is why a lawyer should review it.

---

## 1–3. One-way or mutual NDA

**Recommendation: one-way, with SoloFella as the discloser.** ⚠️ MEDIUM

| | One-way (he protects your info) | Mutual (both protect each other's) |
|---|---|---|
| **Advantages** | Matches reality, since you are the one disclosing. No obligations on you. Harder for him to later claim you misused "his" confidential ideas. | Feels balanced and is easier to get signed. Useful if he really will disclose proprietary material. |
| **Disadvantages** | May feel one-sided to him. Usually a non-issue at the exploratory stage. | Creates obligations for you, and a contamination risk (see #4). Being bound by his vague "ideas" can later cloud your ownership of VRYOH features. |

For question 3: one-way protects SoloFella and VRYOH better, because a mutual NDA gives him a legal hook against you that you don't need.

## 4. If he may share his own ideas, templates or methods

That does **not** automatically justify a mutual NDA. It raises your risk. If he shares a "method" and VRYOH later builds something similar, he could claim misuse or co-invention.

Better handling:
- Keep the NDA one-way, and state that you don't want to receive his confidential information unless you agree in writing first.
- Add an **independent development** clause and a **feedback** clause: suggestions about VRYOH become SoloFella's.
- If he really needs to share proprietary tools, cover that in the contractor agreement's **pre-existing materials** clause. He keeps ownership, and SoloFella gets a perpetual license to whatever is incorporated.

## 5. Contractor agreement with IP assignment before productive work

**Yes. This is the most important step.** ⚠️ UNVERIFIED (training data)

Under US copyright law, a contractor generally owns what he creates unless there is a signed written assignment. "Work made for hire" usually does not cover software, prompts or documentation made by contractors, because they fall outside the statute's limited categories.

An NDA covers **secrecy, not ownership**. Without an assignment, he could own the code snippets, prompt rewrites or QA framework he writes for VRYOH. Use present-tense language ("hereby assigns"), not "agrees to assign."

## 6. If he wants to work unpaid for résumé experience

**Don't accept unpaid productive work.** ⚠️ UNVERIFIED (training data)

- For-profit businesses generally cannot take "volunteer" labor under the FLSA and New York labor law. Unpaid work that benefits the business can create wage and misclassification claims later.
- An IP assignment is cleaner when he receives something in exchange (consideration).
- **Recommended:** pay a small fixed fee for a narrowly scoped task. Offer résumé value separately, through written permission to use approved résumé wording and a reference on request. That gives him what he wants without creating free-labor exposure.
- If he refuses payment, limit the relationship to conversation under the one-way NDA: no deliverables, no system access, no code.
- ✅ HIGH (web search): New York law requires a written contract for freelance engagements of $800 or more. That includes multiple smaller jobs with the same client that reach $800 within 120 days. The contract must be provided to the freelance worker and retained by the hiring party for at least six years. Required contents include the names and mailing addresses of the freelance worker and the hiring party, an itemized accounting of the services to be performed, the rate of pay, the payment date, and the date by which he must submit his list of services. If no payment date is specified, payment is due no later than thirty days after services are completed. Template 2 includes these fields even for smaller amounts.
- Check the current IRS 1099-NEC reporting threshold with your accountant. ❌ LOW: I believe it changed recently.

## 7. Language to avoid employment, partnership, equity or cofounder claims

Put these in the contract:
- He is an independent contractor. He controls his own methods, hours and tools, and is responsible for his own taxes.
- There is no employment, partnership, joint venture or agency relationship. He has no authority to bind SoloFella.
- There is no equity, profit share, revenue share, title or future role, whether promised or implied.
- There is no obligation of future work.
- The written agreement is the entire deal and replaces any oral statements. Changes must be in writing and signed.

Behavior matters as much as wording:
- Don't call him "partner," "CTO," "cofounder" or "team member," including in emails, LinkedIn or introductions.
- Don't discuss equity "someday."
- Don't set his hours or supervise him like an employee.

## 8. Ownership of work product

Key elements (all in Template 2):
- A broad definition of "Work Product" that names every item you listed: prompts, code, n8n node logic, workflow changes, documentation, QA frameworks, evaluation tables, agent logic, schemas and feedback.
- "Work made for hire to the extent permitted, **and** hereby assigns" all rights.
- A waiver of moral rights.
- Further assurances, meaning he signs follow-up documents if needed, backed by a limited power of attorney.
- A feedback clause: any suggestion about VRYOH belongs to SoloFella.
- A license to any pre-existing materials he builds into the work.

## 9. Clauses protecting data, workflows and strategy

- **Confidential Information definition:** names client data, review data, screenshots, reports, prompts, n8n workflows (JSON, logic, node structure), NocoDB schemas, business strategy, pricing, clients and roadmap. It also covers information disclosed orally or visually and anything derived from it.
- **Client data restrictions:** use only for the task, no copying or export, no contact with clients, and notice to you within 24 hours of any suspected incident.
- **No AI or third-party tools:** no pasting VRYOH material into personal LLM accounts, code assistants or cloud tools unless you approve them in writing. This matters specifically for prompts and workflows.
- **No security testing without authorization:** because he has cybersecurity skills, no scanning, penetration testing or probing of any system (yours, a client's, n8n or NocoDB) without specific written authorization.
- **Security of access:** least privilege, no sharing credentials, no keeping copies.
- **Return and delete** on request or at termination, with written certification.
- **Other standard protections:** no reverse engineering, injunctive relief, survival of obligations after the agreement ends.
- **DTSA whistleblower notice.** ⚠️ UNVERIFIED: my understanding is that omitting it limits certain federal remedies.
- **Check your client agreements first.** ⚠️ Before any client data reaches him, confirm that your client contracts allow subcontractor access. If they are silent, use anonymized or synthetic data.

## 10. Before the NDA is signed, don't share

- Architecture details
- Prompts
- Workflow JSON or screenshots
- The NocoDB structure
- Client names or client data
- Review data
- Pricing or unit economics
- The roadmap
- The agent list or logic
- Any credentials or URLs

Safe to share: the problem VRYOH solves, a general description ("AI-assisted review response workflows"), and the type of help you're considering.

## 11. After the NDA, but before a contractor agreement, still don't share

- Live system access or credentials
- Live client data
- Full prompts or complete workflow exports
- Any request for him to produce something, such as fixes, rewritten prompts or code

Anything he creates at this stage is his. Keep it to conceptual discussion and, at most, a sanitized walkthrough.

## 12. Biggest risks

1. **IP ownership gap.** He produces useful work before an assignment exists.
2. **Unpaid-work and misclassification claims.**
3. **Contamination or co-invention claims** from his shared "ideas."
4. **Client data exposure.** This risks breaching your client contracts and damaging your reputation.
5. **Prompt and workflow leakage**, including through his AI tools or GitHub. Trade secret protection generally requires that you took "reasonable measures." ⚠️ UNVERIFIED
6. **Unauthorized security testing** by a security-skilled person with access.
7. **Implied promises in conversation** that later support a partnership claim.
8. **Enforcement is practically weak.** Suing an individual is slow and expensive, so limiting access protects you more than the paperwork does.

## 13. Cleanest structure

1. **Before meeting 1:** he signs the one-way NDA (Template 1), sent by e-signature. Prepare a sanitized demo that uses no client data.
2. **Meeting 1:** discuss problems at a general level, show the sanitized walkthrough, and identify one narrow task. No access, no deliverables.
3. **First project:** sign the contractor agreement (Template 2) plus a written Statement of Work before any work starts.
   - Fixed small fee and a time box (for example, 1–2 weeks).
   - Work in a sandbox copy with anonymized or synthetic data, under a separate account you can revoke.
   - Deliverable: written findings and recommendations. You implement any changes yourself.
4. **Close-out:**
   - Revoke his access and rotate every credential he could have seen.
   - Collect his deletion certification.
   - Pay him within the agreed terms.
   - Give him the approved résumé wording and a reference.

---

## Template 1 — Confidentiality Agreement (One-Way)

**Why one-way:** you are the only party who needs to disclose anything, and a one-way agreement avoids contamination claims (#4).

```
ONE-WAY CONFIDENTIALITY AGREEMENT

This Agreement is made on [DATE] between SoloFella LLC, a Wyoming limited
liability company ("Company"), and [NAME], an individual residing at [ADDRESS]
("Recipient").

1. Purpose. Company may disclose information to Recipient solely to evaluate a
possible limited technical engagement relating to Company's VRYOH products and
services (the "Purpose"). This Agreement creates no obligation to engage,
hire, or pay Recipient.

2. Confidential Information. "Confidential Information" means all non-public
information disclosed by Company, in any form (written, oral, visual,
electronic, or by demonstration), including: AI agent logic, prompts, prompt
structures, workflows (including n8n workflows, node logic, and exports),
database structures (including NocoDB schemas), code, evaluation and QA
methods, client identities, client data, restaurant review data, screenshots,
reports, pricing, business strategy, and product roadmaps, and all notes,
summaries, or derivatives of any of the foregoing. Information need not be
marked confidential to be protected.

3. Exclusions. Confidential Information does not include information that
Recipient can show by written records (a) is or becomes public through no
fault of Recipient; (b) was lawfully known to Recipient before disclosure
without a confidentiality obligation; or (c) is lawfully received from a third
party without restriction.

4. Obligations. Recipient will: (a) use Confidential Information only for the
Purpose; (b) not disclose it to anyone; (c) not copy, record, photograph,
screenshot, or export it; (d) not input it into any AI model, chatbot, code
assistant, or third-party tool; (e) not reverse engineer, replicate, or build
anything based on it; and (f) protect it with at least reasonable care.
Recipient may disclose if required by law, after prompt written notice to
Company (where legally permitted) and disclosing only what is required.

5. No Unsolicited Disclosures by Recipient. Recipient will not disclose his
own confidential or proprietary information to Company without Company's prior
written agreement. Company has no confidentiality obligation for anything
Recipient shares. Any comments or suggestions Recipient makes about VRYOH
("Feedback") may be used by Company freely, and Recipient hereby assigns to
Company all rights in Feedback.

6. No Access or Testing. This Agreement grants no access to any Company or
client system. Recipient will not scan, probe, test, or attempt to access any
Company, client, or vendor system.

7. No License; No Relationship. All Confidential Information remains
Company's property. No license, partnership, employment, equity, or other
relationship is created.

8. Return and Deletion. On request, Recipient will promptly return or delete
all Confidential Information and confirm deletion in writing.

9. Term. Recipient's obligations last three (3) years from the last
disclosure, and indefinitely for trade secrets and client data.

10. Remedies. Unauthorized use or disclosure may cause irreparable harm.
Company may seek injunctive relief in addition to any other remedies, without
posting bond where permitted.

11. DTSA Notice. Under 18 U.S.C. § 1833(b), an individual will not be held
liable under any trade secret law for disclosing a trade secret (a) in
confidence to a government official or attorney solely to report or
investigate a suspected violation of law, or (b) in a sealed filing in a
lawsuit or other proceeding.

12. General. Governed by New York law; exclusive jurisdiction in the state or
federal courts located in [COUNTY], New York. This is the entire agreement on
this subject. Amendments must be in writing and signed. Electronic signatures
are valid.

SoloFella LLC                          Recipient
By: ______________________              ______________________
Name: [Miguel ___], Member             Name: [NAME]
Date: ________                         Date: ________
```

## Template 2 — Independent Contractor / Limited Task Agreement with IP Assignment

```
INDEPENDENT CONTRACTOR – LIMITED TASK AGREEMENT

This Agreement is made on [DATE] between SoloFella LLC, a Wyoming limited
liability company, mailing address [ADDRESS] ("Company"), and [NAME], mailing
address [ADDRESS] ("Contractor").

1. Services. Contractor will perform only the services described in Exhibit A
(the "Services"). Work outside Exhibit A requires a signed written amendment.
Company has no obligation to offer further work.

2. Payment. Company will pay Contractor [$AMOUNT], [fixed fee / $__ per hour,
capped at $__], for the Services. Contractor will submit a written list of
services performed by [DATE]. Company will pay by [DATE], or within thirty
(30) days after completion of the Services if no date is set, by [method].
Contractor is responsible for his own expenses unless Company pre-approves
them in writing.

3. Independent Contractor. Contractor is an independent contractor. Contractor
controls the manner, means, and hours of work, and uses his own equipment
unless Company provides specific access. Contractor is responsible for all
taxes, and receives no benefits and no workers' compensation or unemployment
coverage from Company. Nothing in this Agreement creates an employment,
partnership, joint venture, agency, or fiduciary relationship. Contractor has
no authority to bind Company. Contractor will not describe himself as an
employee, partner, cofounder, officer, or member of Company.

4. No Equity. Contractor receives no equity, membership interest, option,
profit share, revenue share, title, or right to future compensation or
position. Contractor acknowledges that no such promise has been made, orally
or in writing.

5. Confidentiality. "Confidential Information" has the meaning in Section 2 of
the Confidentiality Agreement dated [DATE] (the "NDA"), which is incorporated
by reference and remains in effect. Confidential Information also includes
all Work Product. If the NDA and this Agreement conflict, the more protective
term governs.

6. Client Data. "Client Data" means all information about or received from
Company's clients or their guests, including reviews, reviewer names, venue
data, reports, and screenshots. Contractor will: (a) access Client Data only
as necessary for the Services; (b) not copy, download, export, or retain it;
(c) not contact any Company client; (d) not input it into any AI model, tool,
or service not approved in writing by Company; and (e) notify Company within
twenty-four (24) hours of any actual or suspected unauthorized access, loss,
or disclosure.

7. Limited Access. Company may provide access limited to the systems and
environments listed in Exhibit A. Contractor will use only the credentials
issued to him, will not share them, and will not access any system, data, or
function beyond that scope. Contractor will not perform any security testing,
scanning, or probing of any system unless specifically authorized in Exhibit
A. Company may revoke access at any time.

8. Work Product and IP Assignment. "Work Product" means everything Contractor
creates, alone or with others, in performing the Services or using
Confidential Information, including prompts, prompt revisions, code, code
snippets, n8n node logic, workflow changes, schemas, documentation, QA
frameworks, test cases, evaluation tables, agent logic, analyses,
recommendations, and Feedback. All Work Product is a work made for hire to
the extent permitted by law. To the extent it is not, Contractor hereby
irrevocably assigns to Company all right, title, and interest in the Work
Product, including all copyrights, patent rights, trade secret rights, and
other intellectual property rights. Contractor waives any moral rights in the
Work Product. Contractor will sign any documents reasonably needed to confirm
or perfect Company's rights, and appoints Company as his attorney-in-fact
solely for that purpose if he is unavailable or refuses.

9. Pre-Existing Materials. Contractor's materials created before or
independently of this Agreement ("Pre-Existing Materials") remain his.
Contractor will not incorporate Pre-Existing Materials or third-party or
open-source materials into Work Product without Company's prior written
approval. If any are incorporated, Contractor grants Company a perpetual,
irrevocable, worldwide, royalty-free, transferable license to use, modify, and
sublicense them as part of Company's products and services. Contractor
represents that the Work Product is original and does not infringe any third
party's rights.

10. Restricted Use. Contractor will not use any Confidential Information, Work
Product, or VRYOH materials for any purpose outside the Services, including
building, advising on, or contributing to any similar product.

11. No Public Disclosure; No Portfolio Use. Without Company's prior written
permission, Contractor will not publicly disclose or reference the Services,
Company, VRYOH, or any client, including on a résumé, portfolio, website,
social media, GitHub, or in any presentation. Company may, at its discretion,
provide approved résumé wording in writing, and Contractor may use only that
exact wording.

12. Return and Deletion. On completion, termination, or request, Contractor
will return or permanently delete all Confidential Information, Client Data,
and Work Product in his possession, including copies, notes, and AI tool
histories, and will certify this in writing within five (5) business days.

13. Term and Termination. This Agreement ends on completion of the Services
or [END DATE], whichever is earlier. Either party may terminate on [3] days'
written notice. Company may terminate immediately for breach of Sections 5–12.
Company will pay for Services properly performed through termination. Sections
4–6 and 8–15 survive.

14. Remedies. A breach of Sections 5–12 may cause irreparable harm. Company may
seek injunctive relief in addition to any other remedies.

15. DTSA Notice. Under 18 U.S.C. § 1833(b), an individual will not be held
liable under any trade secret law for disclosing a trade secret (a) in
confidence to a government official or attorney solely to report or
investigate a suspected violation of law, or (b) in a sealed filing in a
lawsuit or other proceeding.

16. General. Governed by New York law; exclusive jurisdiction in the state or
federal courts located in [COUNTY], New York. This Agreement, the NDA, and
Exhibit A are the entire agreement and supersede all prior discussions.
Amendments must be in writing and signed. Contractor may not assign or
subcontract. If any provision is unenforceable, the rest remains in effect.
Electronic signatures are valid. Company will retain this Agreement for at
least six (6) years.

SoloFella LLC                          Contractor
By: ______________________              ______________________
Name: [Miguel ___], Member             Name: [NAME]
Date: ________                         Date: ________

EXHIBIT A – STATEMENT OF WORK
- Services: [e.g., written review of prompt structure for one agent;
  findings only, no production changes]
- Deliverables: [e.g., written findings document]
- Environment and access: [e.g., sandbox copy with anonymized data only;
  view-only account]
- Security testing authorized: [None / specific scope]
- Timeline: [start date] – [end date]
- Fee: [$]   Payment date: [ ]   Services list due: [ ]
```

**Points to raise with your attorney:**
- The Wyoming LLC operating from New York: ask whether you need NY foreign qualification. ⚠️ UNVERIFIED
- Whether New York requires anything specific for a valid IP assignment clause.
- Whether your client contracts permit subcontractor access to client data.
- The current 1099 reporting threshold.
