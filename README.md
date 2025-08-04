# EmergencyDept_PowerQuery_Intermediate_EDA

### What it does

* Loads and merges emergency department tables: admissions, discharges, and vital signs
* Flags visits by fever (≥ 100.4 °F), after-hours, and computes Early Warning System scores
* Implements **M Language** custom logic (e.g. `convertesiscore = (esi) => sqrt(4/esi)`)
* Dynamically filters data using parameters (e.g. `Start Date`, minimum EWS score)

---

### Key Techniques Used

* **Appending and merging** datasets
* **Conditional custom columns** (e.g. fever, after-hours, hrscore, sbpscore, rrscore, ewsscore)
* **Grouping, sorting and indexing** within sub-tables using `Table.Group > Table.Sort > Table.AddIndexColumn`
* **Reusable M functions and query parameters** for flexibility and performance

---

### Conclusion

This project demonstrates a real-world application of Power Query, showing how to:

* integrate multiple data sources into a cohesive analytical pipeline,
* apply dynamic filtering via parameters,
* and transform raw data into actionable insights ready for further analysis or visualization.

