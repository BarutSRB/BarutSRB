I’m the creator of **[OmniWM](https://github.com/BarutSRB/OmniWM)**, a macOS tiling window manager. I build tools for window management and terminal workflows, with a focus on responsiveness, reliability, and understanding how macOS works underneath.

My contributions to other open-source projects include:

- **[bobrwm](https://github.com/bobrwm/bobrwm/pull/13)** — Added automatic retiling when monitors connect or disconnect and fixed an event-buffer threading bug. These changes improved multi-monitor handling and addressed a race that could lose or corrupt window events. The maintainer manually integrated the contribution.

- **[Glide](https://github.com/tmandry/glide/pull/129)** — Implemented an experimental Niri-inspired scrolling layout with horizontal columns, spring animations, configurable widths, and interactive resizing. This introduced a substantial new window-management mode alongside traditional tiling.

- **[Ghostty](https://github.com/ghostty-org/ghostty/pull/11999)** — Fixed a macOS build issue where Apple’s library tools could silently discard object files from Zig-generated archives. Normalizing the archives before combining them preserved required symbols and prevented broken library builds.

- **[cmux](https://github.com/manaflow-ai/cmux/pull/12235)** — Contributed the Ghostty-specific diagnosis and precise solution for macOS 27 crashes and missing icons affecting users with comma-decimal locales. The merged upstream patch implements the same targeted locale fix, protecting interface rendering while preserving users’ terminal locale settings. [Original explanation](https://github.com/manaflow-ai/cmux/issues/7880#issuecomment-5561925339) The related cmux investigation was also referenced by OrbStack users who confirmed a working workaround for similar crashes.
