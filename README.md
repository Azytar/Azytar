# azytar.rs

```rust
//! Linux systems and graphics.

const INTERESTS: &[&str] = &[
    "Rust", "Linux", "X11", "Vulkan",
];

const PRINCIPLES: &[&str] = &[
    "Understand the system",
    "Make behavior predictable",
    "Measure what matters",
    "Keep interfaces small",
];

fn main() {
    for principle in PRINCIPLES {
        println!("{principle}");
    }
}
```

## Modules

| Project | Responsibility |
| :--- | :--- |
| [Maverick](https://github.com/Azytar/Maverick) | Window management and layout on X11. |
| [Aura](https://github.com/Azytar/Aura) | VT emulation, text and Vulkan rendering. |
| [maverickctl](https://github.com/Azytar/maverickctl) | Unix IPC, commands and session management. |

I enjoy working close to the boundaries between software and the machine.
