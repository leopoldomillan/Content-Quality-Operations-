# Data Dictionary

This document defines the fields used in the simulated Content Quality Operations dataset.

| Column | Description | Example |
|---|---|---|
| Case_ID | Unique identifier for each reviewed case | C00001 |
| Review_Date | Date the content was reviewed | 2026-01-15 |
| Reviewer_ID | Anonymous reviewer identifier | R014 |
| Team | Operational team responsible for the review | Team A |
| Market | Market or language group | UK |
| Content_Category | Type of content reviewed | Harassment |
| Initial_Decision | Original moderation decision | Remove |
| Quality_Decision | Decision reached during quality review | Approve |
| Accuracy_Result | Whether the original decision was correct | Correct |
| Error_Type | Classification of the review error | Over-enforcement |
| Review_Time_Minutes | Time taken to review the case | 4.8 |
| SLA_Target_Minutes | Maximum target review time | 5 |
| SLA_Met | Whether the SLA was achieved | Yes |
| Escalated | Whether the case required escalation | No |
| Policy_Version | Policy version applied | V3.2 |
| Calibration_Attended | Whether the reviewer attended calibration | Yes |
| Repeat_Error | Whether the same error had occurred previously | No |
