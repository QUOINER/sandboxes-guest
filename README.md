# sandboxes-guest

## Import path migration

The canonical Go module path is now `github.com/rheic/sandboxes-guest` (previously `github.com/quoiner/sandboxes-guest`). Update imports and `go.mod` requirements when moving to a release that includes this change. The old module path is not kept as a compatibility alias.

Status: pre-alpha.

In-VM guest init and agent. Handles process execution, PTY, file operations, and
guest-side bootstrap. No host keychain or cloud dependencies.
