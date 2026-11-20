# Risk Mitigation & Technical Constraints

## Core Technical Risks

*   **Highest Risk Feature:**  Findig the corrects and accurates data about the countriies in order to provide correct information to the user.
*   **The Hazard:** Some country informations may be be outdated or  incomplete  or inaccurate. This could lead to incorrect comparisons  between the countries and reduces the  users trust in the application in general.
* 
    *   ## The Pivot Strategy
If our primary implementation for this feature fails or takes too long, our backup plan is to:
1. Creating an AI agents specialized in country analysis and comparisons only.
2. feeding him only history, geography, cultures, DATA and connect it with our data base application so the information that will be deployed is mostly about countries only. We also consider to take information from verified sources only.
