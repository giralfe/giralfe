# Ralph Warrand

**Engine, Graphics & AI Programmer**

I build the layer where physics, frame budgets, and byte budgets have to compose engines, renderers, AI systems, emulators, compiler tooling. The work that excites me is anywhere a real-time constraint forces a real engineering decision.

- 🎓 MSc Computer Science & Engineering @ TU/e
- 🎓 BSc Creative Media & Game Technologies @ BUas
- 🌍 Based in The Netherlands
- ✉️ [ralphwarrand@gmail.com](mailto:ralphwarrand@gmail.com)

---

## Projects

### [HexForge](https://github.com/giralfe/HexForge)
Cross-platform C++20 engine framework built from scratch as a research surface. 
* **Tech:** C++20, OpenGL 4.x, CMake, GitHub Actions
* **Features:** PBR (Cook-Torrance) shading, Position-Based Dynamics (cloth/fluid), custom allocator, batched throughput

### [MochaNES](https://github.com/giralfe/MochaNES)
Cycle-accurate NES emulator in pure Java.
* **Tech:** Java (JDK 17+), Maven
* **Features:** 6502 CPU (including illegal opcodes) and Loopy's Logic PPU rendering verified against `nestest.log`, NROM/MMC1 mappers

### SPLICED (Steam Release)
Lead AI Programmer on a UE5 Metroidvania shipped on Steam.
* Built a multi-phase boss encounter with spline-driven attacks, animation-notify hit registration, and data-driven tuning
* Recovered ~15% of AI frame time through profiled fixes

### Engram
Domain-specific language for NPC behaviour with a source-to-source compiler emitting libGDX AI Java.

---

## Tech Stack
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl) ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) 

---

## Philosophy
* **Profile, then cut.** The optimizations I'm proudest of come from measuring first.
* **Cross-platform on day one.** Clean HAL, platform-blind gameplay code.
* **Ship the small thing first.** Concrete artifacts make team decisions faster.
