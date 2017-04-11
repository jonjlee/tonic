---
layout: post
title: "Algorithm to identify ALTEs that can be discharged"
modified: null
categories: blog
excerpt: "A 2012 prospective cohort study at CHOP. Most ALTEs don't need admission. Use this algorithm to determine who can go home."
citation: "Mittal MK, Sun G, Baren JM. A clinical decision rule to identify infants with apparent life-threatening event who can be safely discharged from the emergency department. Pediatr Emerg Care. 2012;28(7):599-605."
tags:
  - Pulmonary
specialties:
  - Emergency
image:
published: true
---

### Summary of Important Points

One of the bigger ALTE studies from CHOP in 2012 showed that:

* **most ALTEs don't result in bad outcomes**. Other smaller studies say the same thing.
* less than 20% of their ALTE admissions are warranted.
* these signs you intuitively worry about don't  actually correlate with bad outcomes: observed activity during the ALTE, CPR, duration of the event, and family history of ALTE or SIDS.
* **you probably shouldn't admit the kid** if they: 1) were born at term and didn't turn blue; 2) were term, did turned blue, but was choking at the time and now looks normal on exam; or 3) were premature but also have URI symptoms.

### Caveats

* This applies to infants < 12 yo.
* **Don't use this algorithm alone** for decision making. A few kids who needed intervention were missed.
* The algorithm **doesn't account for abuse** since there were no cases of it.
* This is a **single-center study** over 2 years. The algorithm isn't ready to be used universally.

### Why is this study important?

This study presents one of the first tools for triaging ALTEs. The results give us some confidence to discharge ALTEs without inpatient observation, especially in cases that we already clinically suspect that this is the case.

CHOP saw an admission rate of 76% for ALTEs during the study, but only 12% resulted in significant intervention warranting admission. This is a huge waste of resources. Rates are similar to many other studies, but this is the biggest study so far with 300 patients.

### What is the actual algorithm?

Here's a summary of the clinical decision rule (CDR) from Figure 1. Gray squares mean the patient probably doesn't need to be admitted. The paper presents this with actual number patients needing significant interventions. So, keep in mind that this is an interpretation and simplification so you can apply it to a new patient.

![ALTE Clinical Decision Rule]({{ site.baseurl }}/assets/img/cdr-for-alte.svg)

### How accurate is it?

Reasonably accurate:

* NPV of 93% - if the CDR said discharge because the patient doesn't need intervention, it was right 93% of the time. The 95% confidence interval is between 88% and 96%.
* Specificity of 69% - if the CDR said the patient needs intervention, it was right 69% of the time. 95% confidence interval is between 63% and 95%.

However, keep in mind that in some of the cases that were missed, something very significant, like an ICU admission, was needed.

### Is it usable in my hospital?

The CDR would have minimal associate cost with reasonably accuracy. However, it is based on a single-center cohort study, so the applicability of the results is limited. It'd be imperative to use it only in light of a clinically sensible pre-test probability. The plus side is that we already rely on that intuitively in pretty much all ALTE cases.

### Comparators

Physician decision to admit a patient versus admitting by using a clinical decision rule based on 5 characteristics of the patient.

### Outcomes

Percent of patients correctly admitted because they required significant intervention.

### Study Design

* Study Type: **Prospective cohort** study
* Population: **300 infants under 12 months** old who presented with an ALTE to the Children's Hospital of Philadelphia from June 2006 to January 2008.
* **Inclusion criteria**: Infants younger than 12 months who met the NIH definition of an ALTE ("frightening to the observer and that is characterized by some combination of apnea (central or occasionally obstructive), color change (usually cyanotic or pallid but occasionally erythematous or plethoric), marked change in muscle tone (usually marked limpness), choking, or gagging. In some cases, the observer fears that the infant has died") that was confirmed by an attending or fellow.
* **Exclusion criteria**: Clear evidence of disease at time of presentation (e.g. seizure, bronchiolitis, etc).
* Do the criteria make sense? Yes, these are the patients that are difficult to make an admission decision about. The authors considered nearly all infants in that time period with ALTEs (only 28 were missed). As far as exclusion criteria, if there was other disease, it makes sense to remove them from the study, since that disease would be the basis for admission rather than the less quantifiable history of ALTE.
* **Methods**: An attending determined whether a case was an ALTE. They reviewed charts on discharge and followd up after 4 weeks. Significant intervention during their stay or any reason for readmission within 72 hours was used as a valid reason for admission. Bivariate analysis found 5 of 7 characteristics considered to be correlated with significant intervention. Recursive partitioning used to develop and validate a CDR based on these characteristics.


### Study Strengths

* Sample size larger than any previous study.
* Done at a high volume center.
* Population and presenting symptoms representative of US population.

### Study Weaknesses
* Limited to 1 center.
* Sample size "may not have been large enough to capture true rate and diversity of the significant intervention" for ALTEs.
* Study did not control for subjective assessments of physicians.
* Limited set of final diagnoses. For example, no patients that were diagnosed with non-accidental injury.
* Resulting CDR was did not have 100% NPV. This can be a substantial issue when misdiagnosis results in missing a need for significant intervention.

### Citation

{{ page.citation }} [[PubMed][PubMed]]

[PubMed]: http://www.ncbi.nlm.nih.gov/pubmed/22743742
