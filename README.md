# merge-queue-e2e

Public repository used to prove Preloop's GitHub merge queue (`merge_group`) support:
`checks_requested` runs the `.preloop/workflows/ci.yml` workflow on the queue's temporary
branch and reports `preloop / test` on the merge group head; `destroyed` cancels the group's
in-flight runs.
