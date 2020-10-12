# Version Control

## [Version Control](#version-control) - Work In Progress
###### [Rule [H000](#rule-h000)]
- Use [Git](https://git-scm.com/) as version control.

###### [Rule [H001](#rule-h001)]
- Use [GitHub](https://github.com/) for hosting source code.

###### [Rule [H002](#rule-h002)]
- 'Master' branch should contain the production version of the code. It hasn't parent branch.

###### [Rule [H003](#rule-h003)]
- 'Develop' branch should contain the staging version of the code. 'Master' is his parent branch.

###### [Rule [H004](#rule-h004)]
- Avoid pushing to 'master' or 'develop' directly. Always create a new branch and then a pull request.

###### [Rule [H005](#rule-h005)]
- New branch must start from 'develop'. If you need some code from other branch still not merged, this new branch should start from the dependent branch.

###### [Rule [H006](#rule-h006)]
- Each branch should be a single feature or bug fix (as small as possible).

  *Why?*: The less changes you want to merge, the easier it will be to review them.

  **Tips**: Avoid mixing code format with features.

###### [Rule [H007](#rule-h007)]
- Commit early and often following [convetional commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/).

  *Why?*: Your commits should follow the SRP (Single Responsibilty Principle). Your commit should change one thing.

  *Why?*: Makes your commit messages more accurate.

  *Why?*: Verbose git history.

  *Why?*: Make reverting commits useful.

  **Tips**: Whenever you reach to the word “and” in your commit message, you know your commit is too big.

###### [Rule [H008](#rule-h008)]
- Merge branches with their parents branches.

  *Why?*: Avoid conflicts.

###### [Rule [H009](#rule-h009)]
- Merge branches via pull request.

###### [Rule [H010](#rule-h010)]
- Resolve conflicts on your pull requests by yourself.

  *Why?*: It's your responsibility.

  *Why?*: You have more context about your code.

  **Tips**: Always merge parent branch on your branch before creating a pull request.

###### [Rule [H011](#rule-h011)]
- Check that your pull request is doing what you think.

  *Why?*: It's your responsibility.

  *Why?*: You have more context about the feature requirements.

  **Tips**: Add screen recording to the pull request description.

###### [Rule [H012](#rule-h012)]
- Avoid treating reviewers as bots.

  *Why?*: They are people!

  *Why?*: Their time is valuable.

  *Why?*: Your pull request is your responsibility.

###### [Rule [H013](#rule-h013)]
- Avoid merging your own pull request.
