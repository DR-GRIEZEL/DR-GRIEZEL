# Repository instructions

<!-- work-smart:progress:begin -->

## Progress and documentation

- Read the existing roadmap, docs/BUGS.json and NEXT.md before selecting work. Keep those sources authoritative; do not duplicate their task status in a diary or blog.
- Initialize missing progress files with Work Smart tools/project_initializer.py --init-progress --apply. Preserve existing roadmaps, bug records and unmanaged NEXT.md files.
- After meaningful work and verification, record one brief outcome with sibling work_smart/tools/progress_sites.py record --repo REPO --changed TEXT --benefit TEXT --verification TEXT --next TEXT --apply. Use plain English, explain technical terms, and state failures honestly. Never claim a check passed without running it.
- Keep credentials, personal data, source excerpts and private runtime details out of progress text. Runtime records, drafts, generated sites, reports and backups belong under MAIN/_meta/, never in tracked blog content.
- Update the canonical roadmap/bug status only when evidence supports it. The documentation site reads these sources; progress bars count completed tracked items and must not imply total project completion.
- Use the shared Universal UI documentation layout for About/README, roadmap, bugs and recent changes where applicable. Preserve application routes, features, data and handwritten documentation. Audit and verify parity before replacing an existing surface.
- Preview documentation exports with Work Smart tools/progress_sites.py build; use --apply only for intended updates. Private deployment uses Fetcher authentication and Tailscale Serve; never enable Pages, Funnel, public hosting or change repository visibility as a side effect.

## Work Smart tooling and agent behaviour

- Mandatory task-start routing: for MAIN maintenance, deployment, distributions, launchers or browser work, automatically use the owner's Agents Portal remote CLI, canonical _MAIN_maint workflows and ai-browser control CLI where relevant. Do not wait for the owner to repeat this instruction. Prefer these interfaces over external computer-use automation or ad-hoc commands.
- Delegate through MAIN/agents-portal-remote.bat --prompt "REQUEST" on Windows or sh MAIN/agents-portal-remote.sh --prompt "REQUEST" on POSIX; use --prompt-file for exact multiline requests and --workspace to bound access. Send prompts, not direct planner/provider calls. Verify coherent tool evidence independently; a model's success claim is not proof.
- _MAIN_maint is the maintenance repository; main-maint is the Portal semantic tool key, never a directory. Use ai-browser/tools/browser_control_client.py for its documented native remote-control actions. Inspect supported actions before use, preserve active tabs/downloads, and never disable guards.
- If a required remote-control interface fails, report the exact failure, repair and retest that path where authorized, and do not silently replace it with another control system. Keep explicit user constraints and repository boundaries in force.
- If the sibling work_smart checkout is present, use it first: its tool catalog (config/work_smart_console_tools.json), its AI prompt helper skills (ai_prompt_helper/skills) and its shared tools. Do not write a parallel script, copy a tool into this repository or re-derive a workflow that work_smart already provides.
- For interactive work prefer a visible GUI or visible terminal window so the owner can follow each interaction; use hidden or background runs only for unattended scheduled jobs (see work_smart tools/scheduler.py).
- Guideline, not a hard limit: keep prompts to agents (Agents Portal remote CLI, sub-agents, delegated sessions) short, about 300 characters by default: one goal, the target path, the expected output and the safety limit. Go longer when the task needs it (exact multiline text, many named files, specs) or split it into ordered steps; clarity wins over the count. Keep voice read-aloud (Speak replies) on in interactive Portal sessions when the language service is available.
- Keep the machine responsive. Run at most about 10 concurrent conversations or agent tasks, never start unbounded parallel test, build or model processes, and cap each heavy task's CPU/GPU use with the work_smart resource-limit policy (tools/task_resource_limits.py). Leave headroom: deliberately run slightly under full speed rather than saturating the machine.
- GUIs and servers must not block the UI thread: do slow work in workers, throttle redraws and event polling, and bound queues, log output and file watchers. Heavy unattended jobs belong in the schedule manifest with idle, CPU and load gates (work_smart config/schedules.json).
<!-- work-smart:progress:end -->
