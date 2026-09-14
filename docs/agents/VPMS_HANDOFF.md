# VPMS Handoff — Narrated Video Toolkit

VPMS_WORKSTREAM_ID: `VPMS-C3-NARRATED`  
PROJECT_NAME: Narrated Video Toolkit  
REPOSITORY: `Joeplouis/narrated-video-toolkit`  
TARGET_BRANCH: `feat/vpms-integration`  
BASELINE_SHA: `7193afe079cd2f793dee0684deb392eda83cbe80`  
GOVERNING_PHASE: Phase 3C — Narrated Video  
GOVERNING_SPEC: VPMS v2.1 master PRD + cross-repo handoff contract  
PROGRAM_COORDINATOR: VPMS Program Coordinator  
IMPLEMENTATION_AGENT: UNASSIGNED  
EVALUATOR: UNASSIGNED; must differ from implementer  
SESSION_SUPERVISOR: ChatGPT VPMS Active Session Supervisor  
STATUS: READY_FOR_BOUNDED_ASSIGNMENT

## Ownership

Narrated Video remains a deterministic local renderer. VPMS owns lifecycle/evidence; this repo owns its rendering implementation.

OWNERSHIP_WRITE_PATHS: only paths granted by bounded Phase-3C assignment.  
READ_ONLY_DEPENDENCIES: VPMS worker/artifact contracts and approved scene/audio inputs.  
SHARED_FILES_REQUIRING_COORDINATOR_OWNERSHIP: cross-repo contracts and canonical VPMS schemas.

INPUT_CONTRACTS: scene/media/audio plan defined by the VPMS worker contract.  
OUTPUT_CONTRACTS: deterministic local MP4/artifacts + truthful receipt/checksum/lineage.  
UPSTREAM_HANDOFFS: VPMS production plan/media assets.  
DOWNSTREAM_HANDOFFS: VPMS artifact ingestion/output verification/QA.

TEST_REQUIREMENTS: fail-closed render/download behavior, required scene/audio checks, artifact existence/checksum, full regression suite.  
EVIDENCE_REQUIREMENTS: exact SHA/tests plus real local MP4 proof through VPMS lifecycle when lane is authorized.  
FORBIDDEN_REFACTORS: do not turn this renderer into a global orchestrator/provider router.  
FORBIDDEN_ACTIONS: no unrelated deployment or paid-provider behavior.

LAST_COMPLETED_ITEM: handoff/integration branch scaffold.  
CURRENT_TASK: none until bounded Phase-3C assignment.  
IMPLEMENTATION_SHA: none  
EVALUATOR_VERDICT: none  
SUPERVISOR_VERDICT: pending future workstream  
UNRESOLVED_DEFECTS: truth audit identified fail-open scene/download behavior requiring correction before production qualification.  
BLOCKERS: bounded assignment.  
NEXT_DEPENDENCY_VALID_ITEM: Narrated Video fail-closed connector/renderer qualification work.  
LAST_UPDATED_AT: 2026-09-14
