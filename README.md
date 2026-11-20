# t3cm-merge-sandbox-direct

Throwaway sandbox for the live merge tests in OttoOps/t3-codemode (issue #56).
Pull requests here are opened, queued and merged by that test. Nothing here is
used by anything else.

`ci/result` sets the `check` job's outcome (`pass`, `fail`, or
`fail-in-queue`, which fails only in the merge queue), and `ci/delay` how many
seconds it waits first.
