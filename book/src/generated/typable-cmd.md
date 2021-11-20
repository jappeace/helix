| Name | Description |
| --- | --- |
| `:quit`, `:q` | Close the current view. |
| `:quit!`, `:q!` | Close the current view forcefully (ignoring unsaved changes). |
| `:open`, `:o` | Open a file from disk into the current view. |
| `:buffer-close`, `:bc`, `:bclose` | Close the current buffer. |
| `:buffer-close!`, `:bc!`, `:bclose!` | Close the current buffer forcefully (ignoring unsaved changes). |
| `:write`, `:w` | Write changes to disk. Accepts an optional path (:write some/path.txt) |
| `:new`, `:n` | Create a new scratch buffer. |
| `:format`, `:fmt` | Format the file using the LSP formatter. |
| `:indent-style` | Set the indentation style for editing. ('t' for tabs or 1-8 for number of spaces.) |
| `:line-ending` | Set the document's default line ending. Options: crlf, lf, cr, ff, nel. |
| `:earlier`, `:ear` | Jump back to an earlier point in edit history. Accepts a number of steps or a time span. |
| `:later`, `:lat` | Jump to a later point in edit history. Accepts a number of steps or a time span. |
| `:write-quit`, `:wq`, `:x` | Write changes to disk and close the current view. Accepts an optional path (:wq some/path.txt) |
| `:write-quit!`, `:wq!`, `:x!` | Write changes to disk and close the current view forcefully. Accepts an optional path (:wq! some/path.txt) |
| `:write-all`, `:wa` | Write changes from all views to disk. |
| `:write-quit-all`, `:wqa`, `:xa` | Write changes from all views to disk and close all views. |
| `:write-quit-all!`, `:wqa!`, `:xa!` | Write changes from all views to disk and close all views forcefully (ignoring unsaved changes). |
| `:quit-all`, `:qa` | Close all views. |
| `:quit-all!`, `:qa!` | Close all views forcefully (ignoring unsaved changes). |
| `:cquit`, `:cq` | Quit with exit code (default 1). Accepts an optional integer exit code (:cq 2). |
| `:cquit!`, `:cq!` | Quit with exit code (default 1) forcefully (ignoring unsaved changes). Accepts an optional integer exit code (:cq! 2). |
| `:theme` | Change the editor theme. |
| `:clipboard-yank` | Yank main selection into system clipboard. |
| `:clipboard-yank-join` | Yank joined selections into system clipboard. A separator can be provided as first argument. Default value is newline. |
| `:primary-clipboard-yank` | Yank main selection into system primary clipboard. |
| `:primary-clipboard-yank-join` | Yank joined selections into system primary clipboard. A separator can be provided as first argument. Default value is newline. |
| `:clipboard-paste-after` | Paste system clipboard after selections. |
| `:clipboard-paste-before` | Paste system clipboard before selections. |
| `:clipboard-paste-replace` | Replace selections with content of system clipboard. |
| `:primary-clipboard-paste-after` | Paste primary clipboard after selections. |
| `:primary-clipboard-paste-before` | Paste primary clipboard before selections. |
| `:primary-clipboard-paste-replace` | Replace selections with content of system primary clipboard. |
| `:show-clipboard-provider` | Show clipboard provider name in status bar. |
| `:change-current-directory`, `:cd` | Change the current working directory. |
| `:show-directory`, `:pwd` | Show the current working directory. |
| `:encoding` | Set encoding based on `https://encoding.spec.whatwg.org` |
| `:reload` | Discard changes and reload from the source file. |
| `:tree-sitter-scopes` | Display tree sitter scopes, primarily for theming and development. |
| `:debug-start`, `:dbg` | Start a debug session from a given template with given parameters. |
| `:debug-remote`, `:dbg-tcp` | Connect to a debug adapter by TCP address and start a debugging session from a given template with given parameters. |
| `:debug-eval` | Evaluate expression in current debug context. |
| `:vsplit`, `:vs` | Open the file in a vertical split. |
| `:hsplit`, `:hs`, `:sp` | Open the file in a horizontal split. |
| `:tutor` | Open the tutorial. |
| `:goto`, `:g` | Go to line number. |
| `:set-option`, `:set` | Set a config option at runtime |
| `:sort` | Sort ranges in selection. |
| `:rsort` | Sort ranges in selection in reverse order. |
| `:tree-sitter-subtree`, `:ts-subtree` | Display tree sitter subtree under cursor, primarily for debugging queries. |