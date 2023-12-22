## PR Review process
This document formalizes the process related to PR Review processes

### Scope
- This document applies to all repositories within the NeoForged organization.
- This document applies to all pull requests within the repositories that this document applies to.

#### Exclusions
- The governance repository

Labels applied to pull requests can be used to indicate that this document is not applicable.
This document can specify labels where it does not apply or for which a different process is applicable.

### Process description
This document describes the bare minimum process that needs to be followed by all parties involved to get a PR accepted.

1. It should be validated that all pull requests come with a sufficiently descriptive message. This message should include, but should not be limited to:
   1. A short introduction as to why the change was made.
   2. Whether tests were performed;
      1. If they were performed, which ones and what was the outcome?
      2. If not, why not?
   3. What needs to be communicated to the public? Examples include:
      1. Changes in API surface or code behavior
      2. Changes to project deployment
      3. Changes to project consumption (GAV changes etc.)
      
      If nothing needs to be communicated, this must also be stated with reasoning.
2. All pull requests not scoped to fixing an issue or deemed to have a sufficiently large impact by at least one maintainer require a cooling-off period between the last commit and the merge of at least 72 hours. Even if approving reviews are given in the meantime.
3. The dismissal of a review should, at all costs, be avoided. However, if it is foreseeable that a reviewer is not able to review a pull request again due to time constraints on his or her part, then after a sufficiently long waiting period and a discussion between maintainers, the review can be dismissed.
