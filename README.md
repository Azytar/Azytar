# Azytar / Lab

**Independent software experiments**  
Linux systems · Graphics · Low-level interfaces

## Project index

| ID | Repository | Focus |
| :--- | :--- | :--- |
| 001 | [Maverick](https://github.com/Azytar/Maverick) | Window management / Rust, X11 |
| 002 | [Aura](https://github.com/Azytar/Aura) | Terminal rendering / Rust, Vulkan |
| 003 | [maverickctl](https://github.com/Azytar/maverickctl) | Control plane / Rust, Unix IPC |

## Engineering notes

- **Maverick:** logical views, scroll geometry and X11 reconciliation are separate concerns.
- **Aura:** terminal state, text processing and GPU rendering have distinct responsibilities.
- **maverickctl:** the client builds independently of the window manager.

## Research interests

Operating systems, computer graphics, formal verification and numerical simulation.

## Method

Read the specifications. Build a small model. Test the boundaries. Measure the result. Remove what the system does not need.

The individual repositories contain the implementation, documentation and tests.
