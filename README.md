---

WindOS
WindOS is an open‑source, iOS‑inspired operating environment designed to run on Windows using a custom VM built on top of a modified DOSBox core.  
WindOS is not a clone of iOS — it is a free, open, moddable alternative that recreates the feel of a mobile OS without Apple’s restrictions.

WindOS aims to provide:

- An iOS‑style UI (home screen, icons, animations, touch‑like input)  
- A custom app runtime (WindOS apps, not IPAs)  
- A sandboxed environment for apps  
- A lightweight VM powered by a rewritten DOSBox core  
- Full freedom: no Apple ID, no DRM, no forced payment methods  

WindOS is built for Windows, but the long‑term goal is cross‑platform support.

---

✨ Features (Current & Planned)

Current
- Basic VM structure using modified DOSBox  
- Initial boot environment  
- Early UI experiments  
- Project structure for OS components  

In Development
- WindOS UI framework (SpringBoard‑style launcher)  
- Custom app format + runtime  
- Touch‑style input mapping  
- App sandboxing system  
- WebView‑based apps (YouTube‑style clients, browsers, etc.)  

Planned
- WindOS App Store (open, no restrictions)  
- Native WindOS apps using a simple API  
- Theming system  
- Cross‑platform builds (Linux, ChromeOS, etc.)  

---

🧱 Project Structure

`
WindOS/
 ├── src/               # Core VM and OS source code
 ├── include/           # Header files
 ├── docs/              # Documentation
 ├── visualc_net/       # Visual Studio project files
 ├── README.md          # You are here
 ├── AUTHORS
 ├── COPYING
 ├── INSTALL
 ├── Makefile.*
 └── etc...
`

---

🛠️ How It Works

WindOS uses DOSBox as a VM shell, but replaces major components:

- The CPU loop becomes a custom WindOS runtime  
- The display surface becomes the WindOS UI layer  
- Input is remapped to touch‑style events  
- A new filesystem layout simulates a mobile OS  
- Apps run inside a controlled sandbox  

This creates a hybrid system:  
part emulator, part OS, fully open‑source.

---

🚀 Goals of the Project

WindOS exists because modern mobile OSes (especially iOS) are locked down:

- No sideloading  
- Forced payment methods  
- DRM‑locked apps  
- No filesystem access  
- No modding  

WindOS is the opposite:

- Free  
- Open  
- Moddable  
- Developer‑friendly  
- No accounts or restrictions  

---

🤝 Contributing

WindOS is early in development, and contributors are welcome.

Good places to start:

- UI framework  
- VM runtime  
- Input system  
- App API design  
- Documentation  
- Testing  

If you want to help, check the Issues tab for tasks marked  
good first issue.

---

📄 License

WindOS is open‑source.  
See the COPYING file for license details.

---

📢 Contact / Discussion

Open an issue or discussion on GitHub if you want to:

- Suggest features  
- Ask questions  
- Help with development  
- Report bugs  

---

