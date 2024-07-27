# NES-Emulator
This repository contains all the information OneLoneCoder provided to make a NES Emulator.

---

Developed a fully functional NES (Nintendo Entertainment System) emulator in C++ as part of an in-depth exploration into 8-bit console architecture. This project involved implementing a complete 6502 CPU emulator, integrating graphical and audio processing units, and supporting multiple NES Mappers to run a variety of games. The emulator supports all essential features, including video rendering, audio playback, and user input handling, providing a comprehensive gaming experience.

**Key Responsibilities:**

- **6502 CPU Emulation:** Developed a cycle-accurate emulation of the 6502 CPU, focusing on complex instructions like ADC and SBC to ensure compatibility with NES software. 
- **System Integration:** Integrated CPU, PPU (Picture Processing Unit), and APU (Audio Processing Unit) using a modular approach that leverages Mappers to handle cartridge loading and memory management efficiently.
- **Graphics Rendering:** Implemented PPU features such as pixel rendering, color palettes, nametables, patterns, scanlines, and scrolling. Managed video memory addressing to accurately reproduce NES graphics.
- **Audio Processing:** Integrated the olcPixelGameEngine's audio framework to simulate NES audio, addressing challenges in timing control and synchronization to produce authentic sound.
- **Input Handling:** Added support for controller input to enable gameplay, ensuring responsive and accurate user interactions.
- **Mapper Implementation:** Implemented support for NES Mappers 0, 1, 2, 3, 4, and 66, allowing for compatibility with a wide range of NES game cartridges.

**Technologies Used:**

- **Programming Languages:** C++
- **Frameworks and Libraries:** olcPixelGameEngine
- **Development Tools:** Visual Studio, Git
- **Concepts:** Emulation, Systems Programming, Low-Level Programming, Memory Management, Real-Time Processing