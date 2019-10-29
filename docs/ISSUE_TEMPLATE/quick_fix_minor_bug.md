---
name: Quick-Fix - Minor Bug
about: A localized <30-minute bug fix with no downstream dependencies
title: "[BUG] QUICK-FIX: insert title here"
labels: bug, needs-more-info
assignees: TimelikeClosure

---

### Quick-Fix - Minor Bug
> _To be filled out by author. Add the `bug` and `needs-more-info` labels. Assign issue to self on creation._

#### **Short Description**
In two sentences or less, describe the bug and its fix.

#### **Additional context**
Add any other links, screenshots, or context about the issue here.

> _After all the above sections are filled out, replace the `needs-more-info` label with `Ready for Implementation`, then move on to the implementation._

---

### Implementation
> _To be carried out by implementer._

#### **Opening a Pull Request**
After the fix has been pushed to GitHub, open a pull request using the following URL template (filling in the compare branch name):
```
https://github.com/TimelikeClosure/<REPO>/compare/dev...<COMPARE BRANCH>?assignees=TimelikeClosure&&expand=1&&template=quick_fix_minor_bug.md&&labels=Bug&&title=[BUG]%20QUICK-FIX%20-%20Insert%20Title%20Here
```

> _After all steps have been completed and integrated into the main development branch, this issue should automatically close._
