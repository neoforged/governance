## PR Review process
This document formalizes the process related to PR Review processes

### Scope
- This document applies to all repositories within the NeoForged organization.
- This document applies to all pull requests within the repositories that this document applies to.
- This document does **not** apply to the governance repository

#### Exclusions
As of now, there are no excluded repositories.
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
2. All pull requests should have a review of a "code-owner". A code owner is defined in the `CODEOWNERS` file by default. 
   If such a file is missing, a code owner can be defined on a pull-request-by-pull-request basis, depending on the available expertise. 
   However, if a temporary owner is used, the pull request can only be merged 48 hours after the last approval and with all reviewer's approval.
   If a `CODEOWNERS` file is present, there are two ways to get around the needed approval in case the owner is not available:
     1. A "HotFix" label can be used. Applying a hotfix requires three independent project maintainers to approve it. Justification for why a given pull request is a hotfix has to be given in writing within the pull request description
     2. Temporary ownership of the code can be taken as if no `CODEOWNERS` file existed, overriding the official code-owner specification. In that case, four independent project maintainers need to approve the pull request, and justification by the temporary code-owner as to why he takes ownership needs to be provided in a pull request comment.
3. The content changes of the PR should be validated
4. It is impossible to dismiss a negative review of any maintainer; we are all equals.
     1. If the maintainer indicates that his review is only a remark, it can be dismissed. This indication can be provided directly with the review or outside of it. If the indication was provided outside of GitHub, a link to the publicly accessible proof of dismissal allowance needs to be provided by the dismisser.
