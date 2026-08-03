# Roadmap

This document tracks the short- and medium-term direction of MAGI.

## Status

MAGI is still in the early stage of definition and foundation-building. The focus is on establishing a clean architecture, a public-ready repository, and the first usable vertical slice.

## Phase 1: Foundation

- [x] Define the project vision and scope.
- [x] Align the repository presentation for public GitHub.
- [x] Establish the initial public-facing documentation structure.
- [ ] Freeze the first MVP stack and execution model.
- [ ] Define the first architecture contract between interface, orchestrator, memory, tools, and models.

## Phase 2: First usable loop

- [ ] Implement the first orchestration prototype.
- [ ] Add the first memory backend.
- [ ] Add the first tool integrations.
- [ ] Draft the first usable interface or CLI surface.
- [ ] Validate the request lifecycle from input to response.

## Phase 3: Product hardening

- [ ] Document the MVP architecture and development workflow.
- [ ] Improve memory persistence for profile and sessions.
- [ ] Expand tool safety and sandboxing.
- [ ] Refine model and persona routing.

## Phase 4: Long-term platform work

- [ ] Support richer memory layers.
- [ ] Improve multi-machine workflows.
- [ ] Expand the interface with project and system views.
- [ ] Document release and iteration practices.

## Suggested implementation order

1. Pick the first stack and lock the MVP boundary.
2. Define the request lifecycle from input to response.
3. Build memory persistence for profile and sessions.
4. Add the first safe tool integrations.
5. Ship a minimal interface or CLI surface.
6. Expand into personas, richer memory, and multi-machine support.

## Notes

The roadmap is intentionally narrow at the beginning. The goal is to ship a stable first slice before broadening the scope.
