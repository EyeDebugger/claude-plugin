# eyedbg plugin for Claude Code

The [eyedbg](https://github.com/EyeDebugger/eyedebugger) agent skill, packaged as a Claude Code
plugin. It needs the `eyedbg` binary on `PATH`; install that first (see the Install section of the
[main repository](https://github.com/EyeDebugger/eyedebugger#install)).

```sh
/plugin marketplace add EyeDebugger/claude-plugin
/plugin install eyedbg@eyedebugger
```

`skills/eyedbg/SKILL.md` is a small loader: it has the agent run `eyedbg skill print`, which prints
the guide embedded in the installed binary, so the guide always matches your eyedbg version and this
plugin rarely needs an update. Report problems with the skill in the main repository. Apache-2.0.
