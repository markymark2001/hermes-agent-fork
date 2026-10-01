# System prompt

Keep native Hermes identity/SOUL, memory scope, operational guidance,
project/environment context, provider instructions and cache lifecycle.
The main prompt has five deliberate differences:

- Native Hermes help wording points to the shipped guide through `read_file`.
- A short connection pointer routes to `guides/connections/guide.md` and requires
  reading and maintaining service manuals.
- A file-keeping pointer names profile-local documents/repos and the filing guide.
- The existing full responsibility renderer occupies the native skills-index
  position. Ownership, state, correction rules, roster and warnings are unchanged.
- Shared memory remains in system context; global USER.md is omitted. Personal
  memory follows the current user message before recall.

Do not add the source product's Memory section or a separate background-memory
paragraph. Hindsight's tool description provides its usage guidance. The memory
tool uses the source product's mechanics-only description, with personal and
shared organization targets; native store operations and flags remain.

Adapt references to excluded capabilities in their native prompt owners:
- Memory guidance routes task knowledge to responsibility packages and connection
  manuals instead of disabled skills; storage, budgets and factual scope stay native.
- CLI/TUI scheduling hints use responsibility schedules and `report` targets
  instead of the removed `cronjob` tool and its `deliver` arguments.
- Delegation guidance routes durable work to responsibility schedules.
- Shipped guides omit skill installation/loading instructions and distinguish
  native administration from the fixed model-tool surface.

These wording changes apply when a prompt is built; warm conversations keep their
existing prompt bytes. Other platforms retain their native delivery hints.

`agent/system_prompt.py` owns assembly. `agent/employee_prompt.py` supplies the
connection pointer and responsibility roster. These are frozen with the native
conversation prompt, including across warm turns. Documents, repositories, responsibilities and connections live directly under
the active Hermes home.
