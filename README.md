# timetrack.sh

`timetrack` is a bash timetracker. It supports users defined session names, pauses and logs.

## Usage

```bash
  ./timetrack -m -s <session_name>
```

Examples:
```bash
  # simple session
  ./timetrack "work"
  ./timetrack -s "work"
  # multi session
  ./timetrack -m -s "work"
```

Notes:
By pressing `ctrl+c` you can pause the counter. When paused any keys pressed will unpause the script, `e` and `ctrl+c` will exit. When the `-m` flag is activated, unpausing will trigger a `<session name>` prompt. Leaving the prompt empty will unpause as usual.

Logs are collected in the `/timetrack.sh/sessions/` folder as `*.tt` files.

Made in France by SMILE R&D.
