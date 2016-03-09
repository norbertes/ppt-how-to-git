###### git octopus-merge

    git merge <branch0> <branch1>.. <branchN>

<!-- -->
    List:       linux-kernel
    Subject:    Re: [GIT PULL] regulator updates for v3.13-rc1
    From:       Linus Torvalds <torvalds () linux-foundation ! org>
    Date:       2014-01-21 19:16:57


    Christ. When you start doing octopus merges, you don't do it by half
    measures, do you?

    I just pulled the sound updates from Takashi, and as a result got your
    merge commit 2cde51fbd0f3. That one has 66 parents.

    That kind of merge either needs to be split up, or gitk needs to be
    made better about visualizing it, because it ends up being *so* wide
    that the history is hard to read.

    I think you'll find that having that many parents also breaks old
    versions of git.

    Anyway, I'd suggest you try to limit octopus merges to ~15 parents or
    less to make the visualization tools not go crazy.  Maybe aim for just
    10 or so in most cases.

    It's pulled, and it's fine, but there's clearly a balance between
    "octopus merges are fine" and "Christ, that's not an octopus, that's a
    Cthulhu merge".

http://marc.info/?l=linux-kernel&m=139033182525831
https://youtu.be/SPY0LyTU53w
