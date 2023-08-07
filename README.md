# timetrack.sh

`timetrack` is a bash time tracker. It supports users defined session names, pauses and logs.

## Usage

```bash
./timetrack <session_name>
```

Example:
```bash
./timetrack "work"
```

By pressing `ctrl+c` you can pause the counter. When paused any keys pressed will unpause the script, `e` and `ctrl+c` will exit. 

Logs are collected in the `/timetrack.sh/sessions/` folder as `*.tt` files.
