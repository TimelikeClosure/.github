---
name: Technical Debt report
about: The source code needs non-functional improvement.
title: "[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY] Pick one, then
  insert title here"
labels: technical-debt, needs-more-info
assignees: TimelikeClosure

---

### Technical Debt Report
> _Add the `technical-debt` and `needs-more-info` labels._

#### **Is your technical debt fix request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]

#### **Describe the solution you'd like**
A clear and concise description of what you want to change.

#### **Describe alternatives you've considered**
A clear and concise description of any alternative solutions or features you've considered.

#### **Additional context**
Add any other context or screenshots about the technical debt here.

> _After all the above sections are filled out, remove the `needs-more-info` label._

---

### Pre-Implementation Checklist

#### **Validation**
- [ ] This request is not a duplicate of another request.
  - If it is, reference duplicate issue, add `duplicate` label, and close issue.
- [ ] This request does not run counter to intended architecture.
  - If it does, add `by-design` label and close issue.

#### **Budgetting**
- [ ] The fix will provide enough benefit to justify the cost.
  - If not, add the `wont-fix` label and close issue.
- [ ] The fix can be budgetted for active development at this time.
  - If not, add the `postponed` label.

> _After all the above checks pass, add the `ready-to-implement` label._

---

### Implementation

#### **Steps**
If the technical debt fix can be broken down into sub-tasks/-issues, add checklist for completion. Reference any sub-issues directly. Steps are checked off as they are added to a pull request.
- [ ] Add checklist of sub-tasks, referencing sub-issues directly
- [ ] Check off sub-issues as they are given the `Verified` label
- [ ] Check off sub-tasks as they are implemented and added to a pull request

#### **Opening Pull Requests**
After a technical debt fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/TimelikeClosure/<REPO>/compare/dev...<COMPARE BRANCH>?assignees=TimelikeClosure&&expand=1&&template=technical_debt_paydown.md&&labels=technical-debt+needs-more-info&&title=[DOCUMENTATION/CLEANUP/PERFORMANCE/MAINTAINABILITY/DEPENDENCY]%20Insert%20Title%20Here
```

#### **After Merging Pull Requests**
After a pull request referencing this issue has been merged, check off any completed steps in the Implementation section above.

> _After all the above steps have been completed and integrated into the main development branch, add the `ready-to-test` label, and remove the `ready-to-implement` label._

---

### Verification

Commit tested on main development branch: [commit #]
- [ ] Application runs without crashing.
- [ ] Application functionality has not changed.

> _After the main development branch is verified to meet the spec, add the `verified` label, remove the `ready-to-test` label, then close the issue._
