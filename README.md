
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
- Full modding/jailbreaking support — no restrictions  

WindOS is built for Windows, but the long‑term goal is cross‑platform support.

---

🧩 How to Get the Source Code

Download ZIP (Beginner‑friendly)
- Click the green Code button  
- Select Download ZIP  
- Extract it  
- Open the project in Visual Studio or your preferred IDE  

Great for exploring or making small changes.

Clone the Repository (Recommended for contributors)
`
git clone https://github.com/eligarner23/WindOS-Emulator-Project.git
`

Cloning lets contributors:

- stay up to date with new commits  
- create branches  
- make pull requests  
- sync changes easily  

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
 ├── system/            # OS services, system manager, kernel-like logic
 ├── ui/                # UI framework, launcher, widgets
 ├── vmem/              # Virtual memory and storage layer
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

🔓 Modding & Jailbreaking

WindOS is intentionally open to modification.  
Unlike iOS, WindOS does not restrict system access, app installation, or customization.

Users and developers can:

- Modify system files  
- Create custom themes  
- Replace UI components  
- Build and sideload apps without signatures  
- Extend or rewrite parts of the OS  
- Build “tweaks” that hook into the UI or runtime  

WindOS encourages experimentation, creativity, and community‑driven development.

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

Check the Issues tab for tasks marked  
good first issue.

---

📄 License

WindOS is open‑source.  
See the COPYING file for license details.

---
