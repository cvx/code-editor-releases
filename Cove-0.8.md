- The branch pill in Source Control opens a full branch panel: local and remote branches as one folding
  tree, with checkout, create, compare, fetch/pull/push and group delete, all keyboard-drivable.
- Source Control gets a **Changes | History** switch (⇧⌘Y): the commit history of the current branch, paged
  as you scroll, scopable to another branch.
- **File ▸ Discard Changes (⇧⌘⌫)** discards the sidebar selection's uncommitted work, and ⌫ on a Source
  Control row does the same — always asking first.
- Rename a changed file in place, on its own row, from the Source Control list.
- The file tree refreshes after a branch checkout.
- Trashing a file that has unsaved edits or uncommitted changes stops to ask.
- Find in Workspace searches your unsaved buffers, not just what's on disk, and reports a pattern ripgrep
  can't compile instead of showing "No results".
- Find in Workspace is markedly faster on large workspaces: narrowing a query no longer re-runs the search,
  and a file change re-reads only the directories it touched.
- A search hit is anchored on its line text, so a file that shifted since the run still opens on the right
  line; results show their directory beside the filename, and a filter naming a directory scopes to it.
- JavaScript and TypeScript work with no install — a language server ships with the app, driving your
  project's own TypeScript.
- One TypeScript server per project instead of three, with idle servers retired after five minutes and one
  process budget shared across every window.
- Drop a pane beside a whole column or row: at a divider's crossing with the editor's outer edge, the new
  pane runs the divider's full length. Drops that would change nothing are no longer offered.
- Dragging an archived chat, or a terminal task, out of the sidebar onto a pane opens or runs it there.
- Hold a drag over the sidebar's section selector and it springs open, so a file, tab or hit can be taken
  to a section that isn't showing.
- ⎋ in a sidebar list hands focus back to the editor and leaves the navigator where it is; the Tasks and
  Source Control lists now answer to the same keyboard vocabulary as the file tree.
- ⌃R opens the recent-workspaces dropdown in a window with no folder open, and a folder in the file tree
  has an **Open as Workspace** item.
- A workspace never opens in a second window — picking one that's already open focuses that window.
- **Reveal in Sidebar** on the tab and pane-title context menus; an Assistant tab's menu carries the chat's
  own verbs, with an ⌥ variant of Bookmark that closes the chat too.
- Click a queued message to edit it before it sends, and the assistant is told the state of the checkout
  each turn.
- Switching tabs scrolls the tab bar before the content swaps, instead of jumping after it; a pane title
  cross-fades to the incoming name.
- The transcript is faster to mount and to scroll: measured row heights survive a tab switch, backfill is
  sized in time rather than rows, and a scrolled-up reader is no longer slid down.
- Three text lines per mouse-wheel notch, matched across the editor, diff, terminal and every list; an
  inactive pane's dim is softer.
- A new terminal inherits the app's environment.
- The previous diff stays on screen while the next one loads.
- Sparkle installs an update on quit when you ask it to.
