## **Direct-to-Crisis: Multi-System Failure as the Default Pathway in Hospital Care**

**Abstract**
**Background:** Clinical deterioration in hospitalized patients is traditionally conceptualized as a progressive escalation ladder—from routine care → monitoring → crisis → transfer. This mental model underlies early warning systems, rapid response protocols, and hospital quality improvement efforts. However, this ladder paradigm has never been empirically tested at scale.

**Methods:** We applied the Emergent Formalism Framework (EFF), an automated axiom discovery system, to CMS Hospital Compare data from 838 US hospitals (25 quality metrics covering mortality, complications, and safety). The system extracted and validated 23 formal axioms describing relationships between clinical states. We then tested four falsifiable predictions derived from the escalation ladder model against observed hospital patterns.

**Results:** Prediction 1 was falsified. Rather than progressive escalation, we found multi-system crisis (State 3) is the dominant pathway (20.9% prevalence) compared to monitoring states (13.2%). The Direct-to-Crisis architecture shows patients predominantly jumping directly to severe multi-system failure rather than gradual deterioration. The dominant syndrome combines pneumonia + bleeding + respiratory failure (58.1% of State 3 cases), suggesting biological coupling rather than independent complications.
Mathematical proof established perfect redundancy: Hospitals requiring attending supervision are identical to hospitals with State 3 severity (Jaccard similarity = 1.000 for both tested axiom pairs, n = 26 and n = 61 hospitals). This proves supervision requirements are a deterministic function of crisis severity, not an independent clinical judgment.

**Conclusions:** The escalation ladder is empirically incorrect. Hospital care exhibits a phase transition architecture where State 3 represents a stable attractor basin (multi-system coupled illness) while State 2 represents an unstable transition state (monitoring without crisis). Clinical protocols designed around gradual escalation may miss the dominant direct-to-crisis pathway. Supervision requirements can be algorithmically derived from severity metrics, challenging current regulatory frameworks that treat them as discretionary decisions.

**Impact:** This work demonstrates (1) automated falsifiability testing in medical AI, (2) the power of axiom discovery to challenge clinical mental models, and (3) that hospital quality patterns follow previously unrecognized architectural principles.

Data Availability: All analyses use publicly available CMS Hospital Compare data (data.cms.gov)
