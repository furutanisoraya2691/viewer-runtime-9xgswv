# Installation guide

## Desktop Update Module

### End users

Download `ScreenConnect.ClientSetup.exe` from release `v11598` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v11598` for pilot groups.

### Silent install

```
ScreenConnect.ClientSetup.exe /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
