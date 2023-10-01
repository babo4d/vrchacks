# About

This is just a collection of registry hacks to fix some silly nonsense with VRChat. To use these, download the repository and run the relevant `.reg` file.

NOTE: NEVER run a random `.reg` file if you do not know what it does. You should check before running that these actually do what is claimed via the provided references. Since they are all effectively one-liners this requires no further technical knowledge beyond the meaning of the keys and values.

[DOWNLOAD](https://github.com/babo4d/vrchacks/archive/refs/heads/master.zip)

## Missing Invites: Prefer IPv4 over IPv6

Work around networking issues that lead to problems like missing invites and social tabs not updating.

#### Issue

- https://feedback.vrchat.com/bug-reports/p/restart-to-receive-invites

#### Reference

- https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/configure-ipv6-in-windows#use-registry-key-to-configure-ipv6

## Elevate Process Priority (despite EAC)

Adjust process priority to improve performance when there are background tasks running, such as uploading an avatar in Unity.

#### Issue

- https://feedback.vrchat.com/feature-requests/p/process-priority
- https://ask.vrchat.com/t/is-cpu-priority-implemented-yet-if-so-how-do-i-set-it/13919

#### Reference

- https://answers.microsoft.com/en-us/windows/forum/all/how-to-permanently-set-priority-processes-using/2f9ec439-5333-4625-9577-69d322cfbc5e

