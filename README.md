### Description
Adds a dwindle (fibonacci-style) layout to dwl.
Windows are arranged by recursively splitting the remaining space,
alternating between horizontal and vertical splits

With two windows:
```
┌───────────────┬────────────────┐
│               │                │
│               │                │
│               │                │
│               │                │
│               │                │
│               │                │
│               │                │
│               │                │
│               │                │
└───────────────┴────────────────┘
```

With three windows:
```
┌───────────────┬────────────────┐
│               │                │
│               │                │
│               │                │
│               │                │
│               ├────────────────┤
│               │                │
│               │                │
│               │                │
│               │                │
└───────────────┴────────────────┘
```

With four windows:
```
┌───────────────┬────────────────┐
│               │                │
│               │                │
│               │                │
│               │                │
│               ├───────┬────────┤
│               │       │        │
│               │       │        │
│               │       │        │
│               │       │        │
└───────────────┴───────┴────────┘
```
### Download

- [0.8](https://raw.githubusercontent.com/ulilab-dev/dwl-patch/refs/heads/main/dwindle.patch)

### Authors
[cana cronica](https://codeberg.org/cana)
