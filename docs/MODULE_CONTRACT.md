# Optional module contract

Every module must expose a stable ID and semantic version, minimum compatible core version, permission declarations and rationale, explicit activation/deactivation, initialise/start/stop/release lifecycle hooks, health status, and data/network disclosure.

Modules must fail closed when a permission is absent. The core app owns permission prompts and must never grant access on a module's behalf.
