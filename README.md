# agent_partial_compact_common

Shared partial-compaction prompt fragments.

This repository is the source of truth for verbatim prompt text shared by
OpenCode partial compaction and `pcodx`. Projects should consume it as a Git
submodule and should not maintain private copies of these prompt fragments.

Public publishing step: publish this repository as
`agent_partial_compact_common`, then update consumer `.gitmodules` URLs from the
current sibling-relative development path to the public remote.
