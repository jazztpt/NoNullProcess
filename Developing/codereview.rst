Code Reviews
============

Everyone
--------


Guildelines
~~~~~~~~~~~

* Accept that many programming decisions are opinions. Discuss tradeoffs, which you prefer, and reach a resolution quickly. [#thoughtbot]_
* Ask questions; don't make demands. ("What do you think about naming this :user_id?") [#thoughtbot]_
* Ask for clarification. ("I didn't understand. Can you clarify?")
  [#thoughtbot]_
* Avoid selective ownership of code. ("mine", "not mine", "yours")
  [#thoughtbot]_
* Avoid using terms that could be seen as referring to personal traits. ("dumb", "stupid"). Assume everyone is attractive, intelligent, and well-meaning. [#thoughtbot]_
* Be explicit. Remember people don't always understand your intentions online.
  [#thoughtbot]_
* Be humble. ("I'm not sure - let's look it up.") [#thoughtbot]_
* Don't use hyperbole. ("always", "never", "endlessly", "nothing")
  [#thoughtbot]_
* Don't use sarcasm. [#thoughtbot]_
* Keep it real. If emoji, animated gifs, or humor aren't you, don't force them. If they are, use them with aplomb. [#thoughtbot]_
* Talk in person if there are too many "I didn't understand" or "Alternative solution:" comments. Post a follow-up comment summarizing offline discussion. [#thoughtbot]_


As the author
-------------

Guidelines
~~~~~~~~~~

* Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.") [#thoughtbot]_
* Don't take it personally. The review is of the code, not you. [#thoughtbot]_
* Explain why the code exists. ("It's like that because of these reasons. Would it be more clear if I rename this class/file/method/variable?") [#thoughtbot]_
* Extract some changes and refactorings into future tickets/stories.
  [#thoughtbot]_
* Link to the code review from the ticket/story. ("Ready for review: https://github.com/organization/project/pull/1") [#thoughtbot]_
* Push commits based on earlier rounds of feedback as isolated commits to the branch. Do not squash until the branch is ready to merge. Reviewers should be able to read individual updates based on their earlier feedback. [#thoughtbot]_
* Seek to understand the reviewer's perspective. [#thoughtbot]_
* Try to respond to every comment. [#thoughtbot]_
* Wait to merge the branch until Continuous Integration (TDDium, TravisCI, etc.) tells you the test suite is green in the branch. [#thoughtbot]_
* Merge once you feel confident in the code and its impact on the project. [#thoughtbot]_

Steps
~~~~~

* [ ] Ensure that your branch can be merged cleanly
* [ ] Ensure that all of the tests pass on your branch
* [ ] Ensure that your code is documented [#adroll]_


As the reviewer
---------------

Guildelines
~~~~~~~~~~~

* Communicate which ideas you feel strongly about and those you don't.
* Identify ways to simplify the code while still solving the problem.
* If discussions turn too philosophical or academic, move the discussion offline to a regular Friday afternoon technique discussion. In the meantime, let the author make the final decision on alternative implementations.
* Offer alternative implementations, but assume the author already considered them. ("What do you think about using a custom validator here?")
* Seek to understand the author's perspective.
* Sign off on the pull request with a :thumbsup: or "Ready to merge" comment.

Steps
~~~~~

* [ ] Understand why the code is necessary [#thoughtbot]_
* [ ] Verify the pull request does what it says it does [#adroll]_ 
* [ ] Verify test coverage and documentation [#adroll]_
* [ ] Verify and run database migrations [#adroll]_
* [ ] Verify code conventions, PEP8, PyChecker [#adroll]_
* [ ] Run the application and validate front-end components [#adroll]_


References
----------


`GitHub Help: Using pull requests <https://help.github.com/articles/using-pull-requests/>`_

`GitHub Guides: Understanding the GitHub Flow <https://guides.github.com/introduction/flow/>`_

.. [#thoughtbot] `Thoughtbot Guides: Code Review <https://github.com/thoughtbot/guides/tree/master/code-review>`_

.. [#adroll] Paraphrased from the AdRoll Developer Process Overview

