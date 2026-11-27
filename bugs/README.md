# Bugs

A bug in the page is reported by pull request, adding its run to this
folder. A report needs:

1. **A one-line description** of what went wrong -- the invariant broken, if
   one was. It is the pull request's title.
2. **The approximate time** it happened: t on the run's clock, in ms. It goes
   in the pull request's description.
3. **The run**, written out with Export run, in the Run section on the right
   of the page. Add the file here as it was saved:
   `raft-run-seed-<seed>-<ms>ms.json`.

A run names the build that wrote it, so it can be replayed against that build
and against the ones after it.
