# Julian Richter

![GitHub followers](https://img.shields.io/github/followers/Julian-richter?style=social)
![Sponsor of Svelte](https://img.shields.io/badge/Sponsor%20of%20Svelte-ff3e00?style=flat&logo=svelte&logoColor=white)

Systems engineer. I live at the bottom of the stack — where the debugger says "unknown" and the documentation says "see source". I work on kernel modules, firmware, bare-metal runtimes, and custom operating systems. I also write higher-level software when the problem genuinely requires it, and not a moment sooner.

Currently building low-level systems software across AArch64 and x86. Running an independent development practice on the side.

---

## The Stack

The real one.

| Layer | What I actually use |
| --- | --- |
| Systems / Kernel | C, C++, Rust, Zig, AArch64 ASM, x86 ASM |
| OS Development | FreeBSD, custom bare-metal runtimes |
| Targets | AArch64, x86\_64 |
| Backend | languages that were never meant for this, and yet here we are |
| Frontend | SvelteKit, Vue, Vite |
| Mobile | Kotlin (Android), Swift (iOS) |
| Game / Real-time | C++ / Unreal Engine 5 |

No garbage collectors were harmed in the making of this stack. Or present. At all. In userland, a GC is just a way to make your allocator someone else's problem — and a slower, less predictable someone else at that.

---

## What I'm Working On

**Lumara OS** — A custom OS targeting AArch64, based on FreeBSD. Not a reskin. A real systems engineering effort with custom kernel configuration, tailored userland, and native builds on a Hetzner AArch64 machine (FreeBSD 15, 8-core Neoverse-N1). The kind of project where `dmesg` is your closest friend and your second closest friend is patience.

**OSDev from scratch** — Because reading about memory management is not the same as writing a page fault handler at 2 AM and questioning every decision that led you here. Bootloaders, memory managers, schedulers — built from the ground up as a discipline.

**Pebble** — An infrastructure service written in Rust. Multi-crate workspace, typed errors, zero `anyhow`, minimal dependencies. The way it should be.

---

## Philosophy

Write software that does one thing. Do not write software that runs everywhere — software that runs everywhere runs equally badly everywhere. Native applications exist for a reason. The reason is that they are good.

If your application ships a runtime, a VM, or a managed heap as a feature, we have different definitions of the word "feature".

I read constantly. Every rabbit hole is a research opportunity. Currently: FreeBSD internals, AArch64 exception levels, Vulkan on non-desktop hardware, and whatever I stumbled into at midnight last Tuesday.

---

## Workflow

I maintain work across both [GitHub](https://github.com/julian-richter) and [GitLab](https://gitlab.com/julian-richter) — open source and personal work on GitHub, DashSoft and infrastructure work on GitLab. GPG-signed commits everywhere, because unsigned commits are a cry for help.

Editor: [Neovim](https://gitlab.com/julian-richter/nvim) — configured from scratch, no magic, no plugins I can't explain. If you use an IDE and it works for you, good. If you need an IDE to read code, that's a different conversation.

---

## Badges

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat&logo=zig&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-525252?style=flat&logoColor=white)
![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=flat&logo=freebsd&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-ff3e00?style=flat&logo=svelte&logoColor=white)

---
## OS Opinions
 
M3 MacBook Air as the daily driver. Occasionally I boot the desktop, which runs headless FreeBSD 15 — because a GUI would just get in the way.
 
Not Windows. Never Windows. A case-insensitive filesystem that silently lies to you until your code hits a real server and falls apart. A POSIX layer that's less of a layer and more of a suggestion. A package manager situation that requires three competing tools, a prayer, and a Microsoft account. A terminal that spent fifteen years being genuinely embarrassing before someone decided to fix it — and then called it a feature. Task Manager open by default because something is always eating your CPU and nobody knows what. Reboots for updates you didn't ask for, at times you didn't choose, during work you can't afford to lose.
 
The fact that this is the world's most popular developer platform is not an endorsement. It's a warning.
 
