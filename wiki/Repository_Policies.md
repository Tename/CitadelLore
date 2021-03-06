---
title: Repository Policies
permalink: wiki/Repository_Policies/
layout: wiki
---

The open source repository we maintain for our server's codebase is
governed under the AGPL3 license, available here:
<https://www.gnu.org/licenses/agpl-3.0.en.html>

All content must be available to be ported to this license, and
therefore must be either a compatible license already, or, your own
creation that you license under AGPL3 by submitting it to our codebase.

There are several other policies that we have created to ensure that the
repository is as functional as possible, as a source for the source code
itself, reporting bugs and other issues, and making contributions.

Follow the License
------------------

All contributions must either be licensed under an AGPL3 compatible
license, or created by you and dedicated to the codebase under the AGPL3
license. Information about what licenses are compatible can be found
here:

<https://en.wikipedia.org/wiki/GNU_General_Public_License#Compatibility_and_multi-licensing>

License compatibility is a fairly complex legal issue, but most other
Space Station 13 codebases are also AGPL3, and porting features from
them can be done without issue.

For reference, because it is a common license, Creative Commons 4.0
BY-SA is the only CC license 'flavor' officially compatible with AGPL
3.0. CC 4.0 just 'BY' and just 'SA' are also both compatible. All CC
licenses that contain 'NC' are definitely not compatible. CC 3.0 BY-SA
'may' be compatible.

Please discuss any other license issues with maintainers, and make them
clear in any pull requests you create.

PR Policies
-----------

### Timelines

We endeavor to review, approve/request changes, and reply to questions
on PRs within a couple of days. This is a low-staff-count project with
only a few active developers who are not paid to contribute their time.

PRs opened and with requested changes by staff, which are not attended
to **for 5 days or longer** will be closed. You can reopen them when you
have time to make the requested changes.

There is no schedule for PRs to the *Release* branch, which is what the
live server runs from. They are done when we have time and feel a
sufficient amount of updates have built up. We are too small a shop to
implement any sort of development lifecycle that we could follow with
regularity.

### Approvals

PRs must be approved, and must **sit for comment for 48 hours without
additional commits** if they contain any gameplay changes. For pure
refactors, bugfixes of reported issues (that are **not**
**suggestions**, but rather obviously restore intended functionality),
and other things that do not have an effect on the actual performance of
the game, this wait can be skipped.

**You are not 'owed' an approval, ever.** Some PRs will be closed
without approvals, unmerged. Just because you created something does not
mean it will be added to the game. They may be closed due to having
issues, not being content or changes the staff wants in the game, or any
other reason the staff sees fit. This is a good reason to check with
development staff and admins before spending a lot of time on a large
project.

### WIP PRs

You can create a WIP PR if you are wanting developer input or comments
on your code. Please do not create them if you just want a place to
shove your code while you continue working on it.

There is **no obligation on the part of the staff to leave 'WIP' PRs
open**. They can clutter the PR list and often sit unattended for an
extended time, especially when the 'owner' of the PR isn't really
seeking comments or help.

Staff helping/giving suggestions on WIP PRs **shouldn't be construed as
any sort of approval** of the content of the PR. Just because staff
helped you with the code does not mean it will eventually be merged.
Your PR could change, or it could be that the person who helped you with
your code does not represent the entire staff.

### \[MIRROR\] PRs (Bot PRs)

These PRs are created by a bot designed to mirror all PRs made on our
upstream codebase(s). Care should be taken when making changes to them
to allow the best merging in the future. Make sure to not CLOSE any, but
if some undesired feature is added, they should be merged, and a
separate PR created to handle the removal, or, if it's possible, the
feature can be commented out in an additional commit in the mirror PR's
branch. Keep in mind what will work best for future merges and code
cleanliness. The more 'ugly' merges performed, the more MIRROR PRs will
require work.

Issue Policies
--------------

### Reporting Bugs

Please make sure to explain fully what the issue is. Assume someone has
never played your department before, and explain the steps to reproduce
it. **Please try to avoid using 'gameplay' steps that assume the reader
knows how to perform them.** For example, saying "Fill the protolathe"
is not a good explanation step in an issue, but "Click with metal sheets
on the protolathe" is, because it explains how to perform that step
without assuming the user knows what a protolathe is, what it would be
"filled" with, etc. Yes, it's a few more words, but it ensures that more
people can look at and resolve your issue.

**If the bug exists on our upstream codebase, please report the issue
there**, not here. In general, most bugs will exist there unless they
are something specific to VOREStation.

### Suggesting Changes

Unfortunately due to the nature of GitHub, there is no way to separate
'suggestions' from bug reports, other than flimsy labels. While you can
suggest changes, **please make it clear that your suggestion is in fact
a suggestion**, and not just 'reporting a bug' that the game doesn't
work how you want it to work.

**The staff has no obligation to actually perform your suggestion**, and
it may be closed, especially if it's poorly worded or makes no sense.
Nobody wants to read through the comments to 'figure out what you
meant'.

Behavior Policies
-----------------

### Toxic Behavior

Comments should be constructive. They should express how you feel about
the contents of the issue or PR, not about the person who made it. If
you think someone is being deceptive or otherwise unfit to be
contributing, please bring it up to staff directly rather than on one of
their issues/PRs.

**As always, issues and PRs, and the comments therein, must follow the
[Rules](/wiki/Rules "wikilink").**

Using issues or PRs as a means of attacking someone won't be tolerated.
They are to make the codebase better, not to push your personal agenda
against another user.

### User Activity

If comments, issues, or PRs are made by any user who hasn't been active
on the server in a very long time (if ever), which seem disruptive or
otherwise unwanted, the user may be subject to being blocked from the
repository, or their comments/issues/PRs removed.

Their views are simply not often as relevant as those who actually
participate, and the staff will not get bogged down pleasing people who
don't actually use the services we provide. They may have comments about
what happened on another server who adopted similar code or changes, but
in many cases they simply leave their opinion about 'what you should
do'.
