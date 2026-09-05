# CalmSwitch — third-party software notices

CalmSwitch application code was created specifically for this project by
Janno Kurss with development assistance from OpenAI Codex. No source code was
copied from RØDE software or the Ponytail project. Public protocol behavior,
controlled packet captures and the Bitfocus Companion RØDECaster Video module
were used as interoperability references. Ponytail was used only as inspiration for
keeping the codebase focused and maintainable.

CalmSwitch uses the following open-source projects:

| Project | Purpose | Source | Licence |
| --- | --- | --- | --- |
| React and React DOM | User interface | https://github.com/facebook/react | MIT |
| Lucide | Interface icons | https://github.com/lucide-icons/lucide | ISC |
| Tauri and Tauri CLI | Desktop runtime and packaging | https://github.com/tauri-apps/tauri | Apache-2.0 OR MIT |
| Tauri process and updater plugins | Application restart and optional updates | https://github.com/tauri-apps/plugins-workspace | Apache-2.0 OR MIT |
| jsPDF | Local PDF report generation | https://github.com/parallax/jsPDF | MIT |
| Tokio | Asynchronous Rust runtime | https://github.com/tokio-rs/tokio | MIT |
| Serde and serde_json | Rust data serialization | https://github.com/serde-rs/serde | Apache-2.0 OR MIT |
| thiserror | Rust error types | https://github.com/dtolnay/thiserror | Apache-2.0 OR MIT |
| async-trait | Async Rust traits | https://github.com/dtolnay/async-trait | Apache-2.0 OR MIT |
| tracing and tracing-subscriber | Rust diagnostics | https://github.com/tokio-rs/tracing | MIT |
| if-addrs | Network interface discovery | https://github.com/messense/if-addrs | MIT OR BSD-3-Clause |
| libc | Operating-system interface bindings | https://github.com/rust-lang/libc | Apache-2.0 OR MIT |
| Bitfocus Companion RØDECaster Video module | Protocol reference; not bundled | https://github.com/bitfocus/companion-module-rode-rcv | MIT |
| Vite | Frontend build tooling | https://github.com/vitejs/vite | MIT |
| TypeScript | Typed frontend development | https://github.com/microsoft/TypeScript | Apache-2.0 |

This table identifies direct dependency families and interoperability references;
it is not an exhaustive transitive-dependency licence inventory.
Exact direct and transitive dependency versions are recorded in
`package-lock.json` and `src-tauri/Cargo.lock`. Each third-party component
remains subject to its own copyright notices and licence terms.

CalmSwitch is an independent project. It is not affiliated with, sponsored by
or endorsed by RØDE. RØDE and RØDECaster are trademarks of their respective
owner.
