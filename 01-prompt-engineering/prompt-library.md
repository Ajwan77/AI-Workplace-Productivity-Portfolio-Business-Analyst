# Prompt Library — Business Analyst

These prompts are designed to support common Business Analyst tasks using structured prompt engineering.

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Meeting Summary | Summarize meeting notes | C.A.R.E. | Act as a Business Analyst. Review the meeting notes I provide. Summarize the key decisions, requirements, concerns, and next steps. Do not invent missing information. | A clear and structured meeting summary. |
| Action Items | Extract tasks from meeting notes | C.A.R.E. | Act as a Business Analyst. Extract all action items from the provided notes. Include the task, owner, deadline, priority, and status only when mentioned. If information is missing, write [Not Specified]. | An action-item table. |
| Requirements Summary | Organize business requirements | C.A.R.E. | Act as a Business Analyst. Review the provided requirements and organize them into business needs, functional requirements, assumptions, and open questions. Do not add information that is not provided. | A categorized requirements summary. |
| Executive Brief | Create a decision-ready brief | R.C.T.O. | Role: Business Analyst. Context: The information will be shared with a manager. Task: Convert the provided information into a concise brief. Output: Key findings, risks, recommended next steps, and open questions. | A concise management brief. |
| Data Insights | Identify patterns in business data | C.A.R.E. | Act as a Business Analyst. Analyze the business data I provide and identify the main patterns and observations. Clearly separate observations from conclusions and do not make unsupported claims. | Evidence-based business insights. |
| Process Improvement | Identify process improvements | R.C.T.O. | Role: Business Analyst. Context: A business process needs improvement. Task: Review the process description and identify bottlenecks and possible improvements. Output: A prioritized improvement table with reasons. | A prioritized improvement table. |
| Stakeholder Email | Draft a professional email | C.A.R.E. | Act as a Business Analyst. Draft a clear and professional email to a stakeholder based only on the information provided. Keep it concise and appropriate for a workplace setting. | A professional stakeholder email. |
| Decision Support | Compare business options | R.C.T.O. | Role: Business Analyst. Context: A manager needs to compare several options. Task: Compare the provided options using the given criteria. Output: A comparison table, key trade-offs, and questions requiring human decision. | A decision-support comparison. |

## Example Output 1 — Action Items

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Prepare requirements summary | [Not Specified] | [Not Specified] | High | Open |
| Review proposed process | [Not Specified] | [Not Specified] | Medium | [Not Specified] |

## Example Output 2 — Executive Brief

### Key Findings
- The provided information contains several areas that require review.
- Some details require confirmation before a final decision.

### Risks
- Missing information may affect the decision.

### Recommended Next Steps
- Verify the missing information.
- Review the available options with the relevant stakeholders.

### Open Questions
- [Not Specified]

## When I Would Use These Prompts

I would use this prompt library for recurring Business Analyst tasks such as organizing information, summarizing requirements, preparing stakeholder communication, supporting decisions, and identifying process improvements.
