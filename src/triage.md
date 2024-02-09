# 🔍 Triage meetings

## When, where

Currently are held on Fridays at 16:00 UTC, but see the Rust calendar [rust-lang/calendar] 
for the most up to date information, and watch [#wg-macros] for last minute changes.

[everytimezone]: https://everytimezone.com/s/c3abbec9
[#wg-macros]: https://rust-lang.zulipchat.com/#narrow/stream/404510-wg-macros
[rust-lang/calendar]: https://github.com/rust-lang/calendar

## So you want to fix a bug?

If you're interested in fixing bugs, there is no need to wait for the triage meeting.
Take a look at the mentored macros bugs that have no assignee.
Every mentored bug should have a few comments.
If you see one you like, you can add the `@rustbot claim` comment into the bug and start working on it!
Please only claim issues that you are actively working on.
If you claim an issue and then realize you don't have time to finish it, that's totally fine!
Just remember to release it in that case.

## Project board

We do not have a Project board yet

## Triage process

In our bi-weekly triage meetings, we take new issues assigned with a macros label and categorize them.
The process is:

- Review [uncategorized issues]
  - Mark `P-low`, `P-medium`, or `P-high`
  - Add `P-high` and _assigned_ `E-needs-mentor` issues to the [project board]
  - Mark `triaged`
- If there's still a shortage of **To do** issues, review the list of [`P-medium`] or [`P-low`] issues for candidates

## Mentoring

If an issue is a good candidate for mentoring, mark `E-needs-mentor` and try to find a mentor.

Mentors assigned to issues should write up mentoring instructions.
**Often, this is just a couple lines pointing to the relevant code.**
Mentorship doesn't require intimate knowledge of the compiler, just some familiarity and a willingness to look around for the right code.

After writing instructions, mentors should un-assign themselves, add `E-mentor`, and remove `E-needs-mentor`.
On the project board, if a mentor is assigned to an issue, it should go to the **Claimed** column until mentoring instructions are provided.
After that, it should go to **To do** until someone has volunteered to work on it.

[`P-medium`]: https://github.com/search?q=org%3Arust-lang+is%3Aissue+label%3label%3AP-medium+is%3Aopen&type=Issues
[`P-low`]: https://github.com/search?q=org%3Arust-lang+is%3Aissue+label%3label%3AP-low+is%3Aopen&type=Issues
