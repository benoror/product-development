# Semantic Commits

We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history. But also, we use the git commit messages to generate the **Change Log**.

**Example:**
```
Fix[consultation]: Add hat wobble
^--^^------------^ ^------------^
|   |               |
|   |               +--> Description in present tense and Capitalised.
|   |
|   +---------------> Scope (Optional, lowercase)
|
+-------------------> Type: Feat, Fix, Chore, Docs, Revert, Refactor, Style, or Test. (Capitalised)
```

## Type
* **Feat:** A new feature
* **Fix:** A bug fix
* **Chore:** Other changes that don't modify src or test files
* **Docs:** Documentation only changes
* **Refactor:** A code change that neither fixes a bug nor adds a feature
* **Style:** Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* **Test:** Adding missing tests or correcting existing tests

## Revert
If the commit reverts a previous commit, it should begin with ``revert:``, followed by the header of the reverted commit. In the body it should say: ``This reverts commit <hash>``., where the hash is the SHA of the commit being reverted.

## Scope
The scope could be anything specifying place of the commit change. For example: consultations, person/medical-history, etc.

## Description
The commit summary contains succinct description of the change:
* Use the imperative, present tense: "Change" not "Changed" nor "Changes".
* Capitalize first letter
* no dot (.) at the end

--

# Message Body

> Commit messages are important means of communication between team members and for the lifecycle of the team: its past and its future.

[What makes a good commit message?](https://hackernoon.com/what-makes-a-good-commit-message-995d23687ad#.w6cv0f8f6)

> The seven rules of a great Git commit message:
> 
> 1. Separate subject from body with a blank line
> 2. Limit the subject line to 50 characters
> 3. Capitalize the subject line
> 4. Do not end the subject line with a period
> 5. Use the imperative mood in the subject line
> 6. Wrap the body at 72 characters
> 7. Use the body to explain what and why vs. how


[How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)

