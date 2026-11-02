# Session bookmark

- **Doing:** Corrected the NPC kick mod status: it is not done; its source files must be added to this repository.
- **State:** The first intended mod enables kicking NPCs. The user clarified that it must be treated as incomplete because its files are absent from the repository. The latest repository inspection found only identical AGENTS.md and CLAUDE.md, NOW.md, and myfile (one newline) on the only branch, main. No README, source code, tests, CI configuration, HANDOVER.md, or nested instructions were present. The original commit was "Create myfile" (2026-10-22); session instructions and bookmark updates were subsequently published. No open PRs existed during the initial review. Main was unprotected, with no rulesets or documented contribution workflow. No executable checks are available. Any implementation outside the repository, its toolchain, target game version, and runtime behavior remain unverified.
- **Next step:** Add the NPC kick mod's source files to the repository, together with any required assets and setup/build instructions. Then inspect the added files and verify the build and in-game behavior before marking the mod done.
- **Blocked by:** Source files have not been supplied or located. Await their location or addition before implementation review and validation can proceed.
- **Updated (YYYY-MM-DD):** 2026-11-02
