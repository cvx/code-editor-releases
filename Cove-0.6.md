The first beta build.

**Reporting**

- **Help ▸ Report an Issue…** opens a mail draft already carrying the build, commit, macOS version
  and the path of this session's log. **Copy Diagnostics** puts the same block on the clipboard, and
  **Reveal Log in Finder** shows the log itself — please attach it when something goes wrong.

**Fixes**

- Dragging a terminal pane very small and back no longer leaves copies of the shell prompt behind or
  grows its scrollback.
- A language server that isn't installed now tells you how to install it (click the orange badge in
  the editor's bottom-right corner).
- Formatters and the Claude Code CLI are found correctly when your login shell is fish.

**Known rough edges**

- Reopening a terminal restores its working directory, not its scrollback.
- Language servers and formatters are whatever *you* have installed; nothing is bundled except
  ripgrep (search).
