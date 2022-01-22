# ideal-git-client
Notes (and maybe future repo?) for my ideal git client

---

### Goal

Currently I mostly use command-line `git` directly.

I just want a simple client that can more easily and quickly do the things I do every hour:

1. View all staged changes.
2. View all unstaged changes.
3. Stage or unstage whole files.
4. Stage or unstage line(s) within a file.
5. Commit with possibly multi-line message.
6. View recent commits of all branches in a tree.
7. View all changes within a commit.
8. Reword some commit (with multi-line support).
9. Add staged changes to last commit (with or without new multi-line message).

Importantly, I want automatic *visual confirmation* that each of these things worked right after I do them.

My idea app would *just* do these things, and leave the rest to `git` or another app.

### Notes on apps I've tried

1. **GitX**: Latest versions from all forks are each kinda broken. Otherwise it's fine except that I'd make a few UI/UX changes.

2. **SourceTree**: Slow, difficult UI, not easy to view whole commits. Honestly using git directly is easier. Sorry Atlassian.

3. **GitHub Desktop**: This has a weird git-like layer on top of git. Also it lacks some features I need (forgot which).

4. **Lazygit**: Kind of unintuitive for me, and destructive commands don't have careful warning dialogs.

5. **tig**: In some cases, barely any more convenient than using git directly. In some cases harder.

6. **Magit**: Requires Emacs, no thanks. Also its UX is a bit unnecessarily complex. Lazygit does a better job with staging area.

7. **All the paid apps**: Honestly they have way too many features, and the ones I need are still kind of hard to use.
