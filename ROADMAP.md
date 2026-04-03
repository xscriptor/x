# X Scripts Roadmap

## Phase 1 · Core Script Reliability <!-- phase:core-reliability -->

- [ ] Add structured logging mode for x.sh
- [ ] Improve distro detection fallback paths
- [ ] Add dry-run mode for safe preview of changes
- [ ] Add rollback notes for critical system edits

## Phase 2 · Optional Modules in scripts/ <!-- phase:optional-modules -->

- [ ] Define stable module interface for scripts add-ons
- [ ] Add template for new module scripts
- [ ] Document enable/disable flow for optional modules
- [ ] Add module-level validation checks

## Phase 3 · WSL Setup Experience <!-- phase:wsl-experience -->

- [ ] Unify install and setup logging for wsl scripts
- [ ] Add preflight checks for supported WSL distributions
- [ ] Add optional profile presets for shell configuration
- [ ] Improve post-install summary with next-step commands

## Phase 4 · Automation and Quality <!-- phase:automation-quality -->

- [ ] Add shellcheck validation in CI
- [ ] Add smoke test workflow for x.sh basic execution path
- [ ] Add roadmap sync workflow from xgh module
- [ ] Add contribution checklist for script safety and idempotency
