# Vim

## Cursor Movement
| Function            | Shortcut | Usage Notes           |
| ------------------- | -------- | --------------------- |
| Up                  | ``k``        | ``4k`` Go up four lines   | 
| Down                | ``j``        | ``9j`` Go down nine lines | 
| Left                | ``h``        |                       | 
| Right               | ``l``        |                       | 
| Next Word Beginning | ``w``        |                       |
| Next Word End       | `e`
| Previous Word       | `b`        |                       |
| Beginning of Line   | `0`        |                       |
| End of Line         | `$`        |                       |

## Editing
| Function             | Shortcut | Usage Notes |
| -------------------- | -------- | ----------- |
| Insert               | `i       ` | Enter insert mode before current char |
| Insert at line start | `I`        | Enter insert mode at beginning of current line |
| Append               | `a`        | Enter insert mode after current character | 
| Append at line end   | `A`        | Enter insert mode at end of current line |
| Append Line          | `o`        | Enter insert mode at new line _after current line_ |
| Insert Line          | `O`        | Enter insert mode at new line _before current line_ |
| Replace              | `r`        | Enter replace mode at current character |

## Visual Mode / Text Selection
| Function                   | Shortcut  | Usage Notes |
| -------------------------- | --------- | ----------- |
| Visual                     | `v       `  | Enter visual mode, mark selection starting point |
| Block Visual               | `ctrl` + `v`  | Visual mode where blocks are selected by column |
| Linewise Visual            | `shift` + `v` | Visual mode where full lines are selected |

## Commands
``:%s/foo/bar/g``
| Command | Meaning |
| ------- | ------- |
| `:`       | Enter command mode |
| `%`       | Perform the next command on all lines |
| `s`       | Substitute |
| `/foo`    | Regex to find |
| `/bar`    | Regex to replace with |
| `/g`      | Global (More than once per line) |
| `:help` or `:h` | View more commands |
