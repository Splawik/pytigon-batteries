# pytigon-batteries

The runtime package set for **Pytigon as a web server**.

`pytigon` on its own is the base framework — a Django project, the `ptig`
command and the ASGI/WSGI entry points — and is not meant to be a runnable
install. This package adds everything a server needs on top of it: document and
PDF tooling, data handling, and the standard projects.

## Install

```
pip install pytigon-batteries
```

It pulls in:

| Dependency | Why |
|---|---|
| `pytigon` | the base framework |
| `pytigon-standard-prj` | the standard projects and applications |

## How it relates to the other packages

| Package | Role |
|---|---|
| `pytigon-batteries` | **web server** — this package |
| `pytigon-gui` | desktop application; installs this package for you |
| `pytigon` | base framework only, not a runnable install |
| `pytigon-standard-prj` | standard projects/applications, pulled in by this package and by `pytigon-gui` |

See the [main Pytigon README](https://github.com/Splawik/pytigon#installation)
for the full installation matrix.

## License

LGPL-2.1 © Sławomir Chołaj
