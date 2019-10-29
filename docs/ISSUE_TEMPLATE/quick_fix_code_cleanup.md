---
name: Quick-Fix - Code Cleanup
about: Code formatting, commented code deletion, debugging artifact removal, or other <30-minute non-functionality-modifying source code fix
title: "[CLEANUP] QUICK-FIX: insert title here"
labels: technical-debt, needs-more-info
assignees: TimelikeClosure

---

### Quick-Fix - Documentation
> _Add the `technical-debt` and `needs-more-info` labels._

#### **Short Description**
In two sentences or less, describe the code mess.

#### **Additional context**
Add any other links, screenshots, or context about the issue here.

> _After all the above sections are filled out, replace the `needs-more-info` label with `ready-to-implement`, then move on to the implementation._

---

### Implementation
> _To be carried out by implementer._

#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/Learning-Fuze/<REPO>/compare/dev...<COMPARE BRANCH>?assignees=TimelikeClosure&&expand=1&&template=quick_fix_code_cleanup.md&&labels=Technical%20Debt&&title=[CLEANUP]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
