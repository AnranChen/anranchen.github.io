---
layout: post
title: "Tango's Latest PRMT5 Data"
date: 2026-06-14
categories: [Oncology, Biotech Newsletter]
author: Anran Chen
canonical_url: "https://asianbiotechiesinabar.substack.com/p/conversation-with-eli-lillys-top"
---

> Originally published on Substack by [Asian Biotechies In A Bar](https://asianbiotechiesinabar.substack.com/p/conversation-with-eli-lillys-top) on June 14, 2026.

On Monday, Tango Therapeutics (TNGX) posted one of the highest early response rates metastatic pancreatic ductal adenocarcinoma (PDAC) has produced: a 92% objective response rate for its PRMT5 inhibitor vopimetostat added to Revolution Medicines' daraxonrasib. The cohort is tiny (11 of 12), but it's the best Phase 1 ORR PDAC has shown.

The market took it seriously. TNGX closed up about 53% at an all-time high of $30.93, a roughly $4.6B company, with the year-to-date gain now around 254%. That afternoon Tango launched a $500M equity raise; the next day it priced at roughly $600M gross, $30.00 a share. The market treated it as the first clinical proof of concept for PRMT5 + pan-RAS, with a strong bias on PRMT5: daraxonrasib's owner, Revolution Medicines, barely moved.

Two things are worth holding apart from the start. The result signals a continuing revival of a target the field had nearly written off — and the move ran well ahead of 12 patients. The more durable story isn't the pancreas number; it's what it says about PRMT5.

## 1. The Most Clinically Advanced Synthetic-Lethal Idea Since PARP

PRMT5 was a marquee oncology target a decade ago, and then a graveyard. The first-generation inhibitors — GSK's pemrametostat (GSK3326595), J&J's onametostat (JNJ-64619178), Pfizer's PF-06939999 — all hit the same wall. They blocked PRMT5 in every cell indiscriminately, and because PRMT5 is essential to blood-cell production, dose-limiting anemia and thrombocytopenia capped exposure below the level needed to kill tumors. Responses were modest and scattered, and the enrichment hypotheses that were tried — broad solid-tumor activity, then splicing-factor-mutant myeloid disease — never delivered a consistent signal. GSK ran pemrametostat through nearly 300 patients and had to cut the dose for toxicity; Pfizer terminated its program in 2022. By the early 2020s, PRMT5 looked like a cautionary tale about an essential enzyme with no therapeutic window.

The vulnerability that would eventually matter was already on the table. In 2016 (Kryukov et al., *Science*), cancers that delete MTAP were shown to become selectively dependent on PRMT5 — and the mechanism is unusually clean. MTAP sits on chromosome 9p21.3, immediately next to CDKN2A, one of the most frequently deleted tumor suppressors in cancer; when a tumor drops CDKN2A it usually takes MTAP with it as a passenger. The cell loses an enzyme it never meant to lose, MTA (methylthioadenosine) accumulates, and that MTA partially jams PRMT5 — but only in the cancer cell. However, the MTAP-PRMT5 story did not end well for the first-generation drugs. Being SAM-competitive, they inhibited PRMT5 the same whether or not MTA was elevated. Due to toxicity, the therapeutic window is extremely narrow.

The second generation was built to exploit exactly the MTA gradient. These agents are MTA-cooperative: they are more inhibitory in MTA-high cells. This strategy provides two levels of selectivity: biologically, the high MTA in MTAP-deleted cells already sensitizes them to PRMT5 inhibition; chemically, the MTA-cooperative design makes the inhibitor selectively more potent in those same MTA-high cells. The toxicity that sank the first generation is, in principle, designed out. Vopimetostat is one of these; other examples include Mirati-then-BMS's MRTX1719 (BMS-986504), Amgen's AMG 193, AstraZeneca's AZD3470, and Bayer's BAY3372.

The population is large. Roughly 10–15% of all cancers carry the deletion, concentrated in the hardest tumors: ~40% of PDAC, ~15% of NSCLC, ~45% of glioblastoma. Tango frames it as ~60,000 MTAP-deleted metastatic cases a year in the US, ~20,000 of them pancreatic.

All of which makes MTAP deletion the most advanced synthetic-lethal vulnerability oncology has found since BRCA/PARP — the pairing whose approval, more than a decade ago, defined the idea, and whose lack of successors let the enthusiasm fade. It also sharpens what synthetic lethality actually requires. A genetic dependency on its own rarely delivers a usable therapeutic window: the first-generation inhibitors had the right target and the right patients and still failed, because genetic selectivity doesn't translate into selective drug action. Opening the therapeutic window took a second layer of selectivity, built into the molecule rather than the patient — a chemotype that reads the consequence of the lesion (elevated MTA), not just the lesion itself. Genetic selectivity defines who to treat; molecular selectivity is what actually widens the window.

## 2. Combination Partners

On combination partners, two ideas dominate. In NSCLC and PDAC, KRAS is the natural pairing, given the overlap between MTAP deletion and KRAS mutation — though not in GBM, where KRAS mutation is rare. The other is MAT2A, which sits in the same SAM/MTA pathway and shows synergy in preclinical models.

## 3. What Tango Actually Showed

The 28 May cut is a Phase 1 escalation with two arms in MTAP-deleted, 2/3L disease: vopimetostat plus daraxonrasib (any RAS), and plus zoldonrasib (G12D-only). The headline is the daraxonrasib arm — 92% ORR, 11 of 12, 100% DCR, 90% six-month PFS, median PFS not reached. The larger G12D zoldonrasib arm read 52% in 27. Pooled, 2/3L pancreas is 64% in 39.

Two caveats sit under the 92%. First, n=12: the confidence interval on six-month PFS runs 47–99%, and dropping one responder takes the ORR to 83% (10 of 12). This is a real signal in a disease that concedes nothing — and it's a twelve-patient single-arm cohort. The honest read is the pooled 64% on about six months of follow-up. Second, the headline arm is the smaller, broader one; the G12D-restricted arm, with more than twice the patients, reads 52%.

That 40-point spread is one of the most interesting things in the dataset, and Tango offered both readings without resolving them. The attractive explanation, supported preclinically: PRMT5 inhibition upregulates wild-type RAS activity, which a pan-RAS agent suppresses and a strictly G12D-selective one cannot. The duller one, probably also true: these are non-randomized arms with small numbers, the zoldonrasib patients had worse ECOG, and other baseline differences likely run the same direction. The current data can't apportion the two, and the reasonable guesses remain guesses.

## 4. The Dose Detail

The other eye-catching differentiator is dosing. Daraxonrasib runs here at 100 mg — versus 300 mg in RASolute 302 and 200 mg in Revolution's own gem/nab-paclitaxel combination, on paper the deepest RAS dose cut in development. But it isn't less drug: vopimetostat raises daraxonrasib exposure roughly 3×, so 100 mg here matches the AUC of 300 mg alone — an interaction Tango predicted before the trial. The mechanism is well-grounded. Published PK work shows daraxonrasib is cleared substantially by CYP3A4 and taken into the liver by OATP1B, so inhibiting those routes lifts its exposure two ways at once — higher oral bioavailability and slower clearance. The one unconfirmed link is that vopimetostat is the inhibitor doing it; that is not a disclosed fact.

On closer inspection, this model faces several caveats. The PK story cannot explain the reduced RAS-associated toxicity. Also, building a regimen on a boosting interaction imports a real liability: daraxonrasib exposure now depends on CYP3A4/OATP activity, which varies with genetics, food, and concomitant CYP3A inhibitors/inducers. It is also worth noticing that the match comes off a small PK sample, so the PK statement is at best directional, not settled.

## 5. Who Gets the Pan-RAS Backbone in MTAP-Deleted PDAC

Daraxonrasib is at the center of the stage; the question is who can dance with it. Mechanistic orthogonality is the easy bar — PRMT5, MAT2A, and chemo all clear it. And in PDAC, MTAP deletion mostly co-occurs with KRAS mutation, so the RAS backbone fits the biomarker population.

| Modality | Agents | Fit on a pan-RAS backbone |
|---|---|---|
| **MTA-cooperative PRMT5** | Vopimetostat (Tango); BMS-986504, AMG 193, AZD3470, others | Best fit: nests in the RAS population, and the only partner even claiming to soften RAS toxicity — though that claim is unproven. Weakness: contribution-of-components, small n. |
| **MAT2A** | IDE397 (IDEAYA) | More competitor than collaborator: converges on the same MTAP-deleted node and carries its own monotherapy activity. |
| **Chemotherapy** | Daraxonrasib + GnP (Revolution) | The incumbent the doublet must displace — 58% 1L ORR — and the comparator against which "more active and more tolerable" has to be proven, not asserted. |

So the endgame in MTAP-deleted pancreas most likely resolves into three backbones competing to pair with pan-RAS — PRMT5, MAT2A, chemo — not a comfortable three-drug stack. The contribution-of-components problem haunts every doublet of two active agents: vopimetostat has real monotherapy activity (27% across histologies, 49% histology-selective) and daraxonrasib carries pancreas on its own, so proving the combination beats each component — and, in front line, beats FOLFIRINOX and gem/nab-paclitaxel on survival — is the bar. It sits far above any response rate.

## 6. Beyond Pancreas, the RAS Pairing Falls Away

The RAS backbone is mostly a pancreas story, and pancreas is the smaller half of the prize. The real franchise is the whole MTAP-deletion footprint, where KRAS is not necessarily the most important player. PDAC (~20,000 cases a year) is the easy case precisely because KRAS is near-universal there — an MTAP-deleted pancreatic tumor is almost by definition also a RAS-combination candidate. That co-occurrence doesn't hold elsewhere. In NSCLC — the largest slice, ~22,000 MTAP-deleted cases — only about a quarter of tumors carry a KRAS mutation, and MTAP loss has no statistical co-occurrence with it; most MTAP-deleted lung cancer is simply not a RAS-doublet population. In glioblastoma (~7,000), KRAS mutation is rare to begin with. Strip out the KRAS-driven tumors and the RAS partner carrying this week's narrative falls away, leaving the bulk of the MTAP footprint as a contest fought on the PRMT5 (or MAT2A) molecule itself.

In this field, the therapeutic window is always the key. Cytopenia is the gating property. Anemia and thrombocytopenia are the on-target, dose-limiting toxicity of PRMT5 inhibition — the same toxicity that sank the first generation. For monotherapy or non-RAS combinations, the selectivity window that lets a drug reach efficacy without crashing blood counts is what separates the molecules. The other differentiator is CNS penetrance, since glioblastoma and the brain metastases NSCLC throws off are unreachable by a systemic-only drug. Only Tango's purpose-built TNG456 and Amgen's AMG 193 are reported brain-penetrant; vopimetostat is not — which quietly makes Amgen, already in pancreas with chemo, the one competitor in both halves of the franchise. This is the field where a drug's own properties, far more than the pancreas ORR, start to decide things.

PRMT5 spent a decade as proof that an essential enzyme is hard to drug. The MTA-cooperative generation is the bet that a biomarker fixed that. Tango just delivered the strongest evidence so far that the bet is good — and the first clear view of how many companies are about to be fighting over the same map.
