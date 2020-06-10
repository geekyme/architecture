## Business Value

&lt;This should be a short paragraph to describe the key **business** goals you are trying to improve. This should be immediately clear to non-technical staff, answering the question: Why should we care?>

## Problem Statement

&lt;Describe the problem you want to solve. Example: developers spend a lot of time configuring x, y, z>

## Background Context

&lt;What’s the story behind the problems today? What’s the root issue? Why do we have such problems in the first place? If necessary, you may want to [link](https://github.com/npryce/adr-tools) to old ADRs>

## Success Criteria

&lt;How do you know if you have succeeded? How will you measure your success?>

## Proposed solutions

&lt;Try to think of 3 alternatives>

### Solution 1

#### How does it work

&lt;Describe in detail, including links to references and diagrams>

&lt;Invite others to this document to leave their comments>

#### Cost

&lt;Estimate what’s the impact on cost>

#### Risks

- Security issues?
- Possible race conditions?
- Network errors that could happen?
- Breaking contract with other teams, causing deployment failures?
- Performance degradation to other parts of the system?
- Compliance issues?
- How does this work at 3X? 10X? 50X? (you may find your solution doesn’t work at larger scale, but maybe you don’t need larger scale)

Include mitigation details for each of these risks.

#### Migration Path

&lt;How do we get from our current state to the proposed solution. Describe in detail>

&lt;Include snippets of code from our codebase>

&lt;Describe how these would change>

&lt;Describe changes to deployment topology, etc.>

&lt;Add any links / diagrams that could help>

#### Test Plan

&lt;How do you intend to test your solution? Automation test? Load test? Contract test, etc?>

### Solution 2

Same sections as above

### Solution 3

Same sections as above

## Actions

### Decision

&lt;Decided on which solution, and why? What’s the tradeoff you are willing to take?>

&lt;Why do you reject the other solutions?>

&lt;Record this into [ADR](https://github.com/npryce/adr-tools) and link from this doc>

### [EXAMPLE] 10 Jun 2020: Create POC

&lt;details of what did you do. Include links / diagrams / important conclusions>

### [EXAMPLE] 13 Jun 2020: Run load tests and check for errors

&lt;In this example, you probably want to attach snippets of errors you found, monitoring charts, etc.>

### [EXAMPLE] 20 Jun 2020: Try another solution

&lt;details of what did you do>

&lt;In this example, maybe you found that your selected solution does not work because of certain reasons. In this case, you will need to record your new decision, and put it a new [ADR](https://github.com/npryce/adr-tools), supercede the old decision and link from this doc>

&lt;See how to [supercede](https://github.com/npryce/adr-tools)>

### Next Steps

&lt;always keep this section updated, and populate history above>

## References

&lt;You can attach other miscellaneous links, like meeting notes here, or things you read>

- What is [ADR](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)
- Purpose of an [RFC](https://philcalcado.com/2018/11/19/a_structured_rfc_process.html)
- ADR on [thoughtworks radar](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)
