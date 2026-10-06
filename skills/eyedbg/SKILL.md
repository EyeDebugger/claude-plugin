---
name: eyedbg
description: Debug a running .NET, Python, C, C++, Rust or Go program from the shell with eyedbg — breakpoints, stepping, locals, eval, exception stops, attaching (also to services in docker containers and compose stacks), and debugging a failing test. Use it when a bug survives one or two fix attempts, when you need a value the program really has at runtime, or to see where an exception or a wrong result comes from. Not for compile errors or questions that reading the code answers.
license: Apache-2.0
---

# eyedbg

The full guide ships inside the `eyedbg` binary, so it always matches the version installed here.
This file only tells you how to get it.

1. Run `eyedbg skill print` once in this conversation and follow the guide it prints for the rest of
   the task. Skip its YAML front matter.
2. `eyedbg: command not found`: eyedbg isn't installed. Tell the user, and point them to
   <https://eyedbg.izzat.dev/#install>. Don't install it without asking.
3. `unknown command "skill"` or `"print"`: this eyedbg is older than 0.2.0. Ask the user to upgrade;
   until then, `eyedbg help --all` prints every command's help in one read.

`eyedbg help <command>` is the source of truth for exact flags and behavior.
