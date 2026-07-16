## Knowledge Usage Rules

Retrieved knowledge provides context and implementation guidance.

Do NOT convert every retrieved knowledge item into an Acceptance Criterion.

Only use knowledge that is directly required to implement the current User Story.

Ignore knowledge that:
- Belongs to another feature
- Describes future enhancements
- Provides background information only
- Is unrelated to the current business scope

## Acceptance Criteria Validation

Before returning the User Story, review every Acceptance Criterion individually.

Include an Acceptance Criterion only if ALL conditions are true:

- It belongs exclusively to this User Story.
- It is required to satisfy the business requirement.
- It is directly supported by the requirement or retrieved knowledge.
- It describes observable business behaviour.
- It can be independently tested.
- It is not duplicated by another Acceptance Criterion.

Exclude Acceptance Criteria that:

- Belong to another feature or User Story.
- Represent future enhancements.
- Describe technical implementation details.
- Describe existing behaviour without change.
- Introduce unsupported assumptions.

## Acceptance Criteria Quality

Acceptance Criteria MUST:

- Focus on business behaviour.
- Be clear and concise.
- Be testable.
- Avoid duplication.
- Avoid implementation details.
- Avoid combining unrelated scenarios into one criterion.

## Final Self Check

Before returning the User Story, verify:

- Every Acceptance Criterion belongs to this User Story.
- Every Acceptance Criterion is necessary.
- No Acceptance Criterion is duplicated.
- No Acceptance Criterion describes another feature.
- No unnecessary Acceptance Criterion is included.

If any check fails, revise the Acceptance Criteria before producing the final output.

Only generate Acceptance Criteria that are essential for the current User Story. Do not convert all retrieved knowledge into Acceptance Criteria.

--限制ＵＳ的范围
### Story Scope

Treat the selected Story Plan item as the only implementation scope.

Do not include functionality, behaviours, or Acceptance Criteria assigned to another Story Plan item, even if they belong to the same business process.

Do not anticipate subsequent workflow steps or future system behaviours.