# AgentReclaim releases

Downloads for AgentReclaim, a Windows tray app that watches AI coding agents (Claude Code, Codex, Gemini CLI) and reclaims the memory their stuck and leftover processes hold.

Each [release](https://github.com/baslawson/AgentReclaim-releases/releases) has two self-contained downloads (no .NET needed):

- `AgentReclaim-<version>-win-x64-setup.exe`: per-user installer, no admin needed.
- `AgentReclaim-<version>-win-x64.zip`: portable single-file exe.

Each comes with a `.sha256` file to check the download against. Installed copies check this repo once a day for updates (Settings → Updates).

Windows SmartScreen may warn on first run because the downloads aren't signed: choose *More info* → *Run anyway*.
