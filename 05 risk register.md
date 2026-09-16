# Risk Register

| # | Risk | Probability | Impact | Mitigation | Owner |
|---|---|---|---|---|---|
| 1 | `Risk_Review_Flag` is imbalanced, weakening model reliability | High | High | DS to assess class balance early; consider resampling/appropriate metrics (precision/recall over accuracy) | Data Science |
| 2 | Data-quality issues (missing values, inconsistent fields) discovered late | Medium | High | DA to complete thorough profiling in Week 1 before any modelling begins | Data Analytics |
| 3 | Cross-track outputs delivered late, delaying downstream work | Medium | High | PM to track deliverable dates closely from Week 2; flag slippage early via status reports | Project Management |
| 4 | GenAI assistant produces hallucinated or unapproved information | Medium | High | Strict grounding to approved knowledge base; evaluation set includes hallucination-test questions | Generative AI |
| 5 | Misalignment between DS's feature/target design and MLE's expected input format | Medium | Medium | Early informal alignment on data schema once outputs are shareable (Week 2) | Data Science / ML Engineering |
| 6 | Scope creep — tracks attempt full production builds instead of Week 1 planning scope | Low | Medium | Reinforce Week 1 deliverable boundaries (e.g. wireframe not full dashboard) | Project Management |
| 7 | Synthetic data doesn't reflect realistic patterns, limiting insight quality | Medium | Low | Document as a known limitation in each track's deliverables rather than trying to "fix" the data | All Tracks |
| 8 | Interns unfamiliar with tools (Power BI, Scikit-learn, Git) slowing progress | Medium | Medium | Use recommended tools pragmatically; seek help early rather than blocking on tooling | All Tracks |
| 9 | Final integration (Week 4) reveals incompatible outputs across tracks | Low | High | PM to run early informal compatibility checks in Week 3, not just at final integration | Project Management |
| 10 | Reporting/communication gaps mean PM lacks visibility into track progress | Medium | Medium | Establish a lightweight recurring reporting cadence from Week 2 | Project Management |
