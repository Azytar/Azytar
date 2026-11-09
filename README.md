# Axiom

> **"Everybody lies. But the compiler doesn't."**
>
> I borrowed the first half from Dr. House. The second half passed the borrow checker.

## Stage 1: Denial

*"I like keeping things simple."*

I write Rust software for Linux. I like small systems, understandable code, and knowing how things work.

Unfortunately, getting there sometimes involves a suspicious amount of engineering.

## Case history

- **[Maverick](https://github.com/Azytar/Maverick)** — A deliberately minimal X11 window manager in Rust. No desktop environment, no unnecessary extras, no complications. Well, that last part is debatable.
- **[Aura](https://github.com/Azytar/Aura)** — A terminal emulator with its own VT core, Unicode handling, font rendering, and a Vulkan backend. All that to display text. It seemed reasonable at the time.
- **[maverickctl](https://github.com/Azytar/maverickctl)** — An independent control client for Maverick. Apparently, writing a window manager wasn't enough. I also needed a way to talk to it.

## Diagnosis

I don't try to make simple things complicated. I try to understand complicated things well enough to make them simple.

I care about correctness, performance, predictable behavior, and software that does what it's supposed to do.

Not everything needs to be reinvented. But sometimes an innocent question becomes an entire project.

**Simple doesn't mean easy.**

---

**Final diagnosis:** I like simple software. Nobody said building it would be simple.

**Prognosis:** Stable, until someone mentions an interesting optimization.

*Stage 2: "I'll just change one little thing."*

*Note: The compiler checks borrowing. Copyright infringement isn't a Rust error.*
