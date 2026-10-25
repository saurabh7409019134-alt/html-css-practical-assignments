# Task 3 — Terminal navigation practice

| Command | Example | Expected outcome |
|---|---|---|
| `pwd` | `pwd` | Prints the current folder path. |
| `ls` | `ls` | Lists visible files and folders. |
| `ls -la` | `ls -la` | Lists hidden files and details. |
| `cd` | `cd html-css-practical-assignments` | Moves into the named folder. |
| `cd ..` | `cd ..` | Moves to the parent folder. |
| `mkdir` | `mkdir practice` | Creates a folder named `practice`. |
| `touch` | `touch notes.txt` | Creates an empty file (macOS/Linux). |
| `code .` | `code .` | Opens the current folder in VS Code if the shell command is configured. |
| `clear` | `clear` | Clears the terminal display. |

## Exercises

1. Run `pwd` and write down the path.
2. List files, then make a folder named `terminal-practice`.
3. Move into it, create `hello.txt`, and list the folder contents.
4. Return to the project root with `cd ..` and confirm using `pwd`.

**Platform note:** PowerShell uses `Get-Location`, `Get-ChildItem`, and `New-Item`; Git Bash and macOS/Linux terminals support the examples above.
