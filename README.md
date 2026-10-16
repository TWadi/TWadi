# Hi, I'm Wadi 👋

Associate Embedded System Software Testing at **Expleo Germany**, working on the quality of automotive software. I write C and C++ for embedded systems and control, and I contribute to open-source projects in that space.

- 📄 First author of a paper on architecture conformance in automotive software, accepted at **TAV-53**
- 🛰️ Open-source contributor to **NASA JPL's F´** flight software framework
- 🧩 Contributor to the **Embedded Template Library** (ETL), a C++ library for microcontrollers
- 🎛️ Author of **[tinyctrl](https://github.com/TWadi/tinyctrl)**, a tested C99 control library for microcontrollers
- 📍 Berlin · 📫 [LinkedIn](https://www.linkedin.com/in/wadi-touil-117472319/)

## Publication

**From Static Analysis Findings to a Quality Score: An Architecture Conformance Index for Automotive Software**<br>
W. Touil, P. Gohil, M. Schmidt, J. Wegener. Accepted at TAV-53, the 53rd workshop of the GI special interest group *Test, Analysis and Verification of Software* (Fachgruppe TAV), 2026.

## Open-source contributions

| Project | Contribution | Status |
|---|---|---|
| [**nasa/fprime**](https://github.com/nasa/fprime) ![stars](https://img.shields.io/github/stars/nasa/fprime?style=flat&label=%E2%98%85&color=555)<br>NASA's flight software framework, C++ | [#6149](https://github.com/nasa/fprime/pull/6149): two `Svc/Health` unit tests returned early, so their checks never ran. Restored them. | ✅ Merged |
| [**ETLCPP/etl**](https://github.com/ETLCPP/etl) ![stars](https://img.shields.io/github/stars/ETLCPP/etl?style=flat&label=%E2%98%85&color=555)<br>Embedded Template Library, C++ | [#1620](https://github.com/ETLCPP/etl/pull/1620): fixed a code-size regression in `etl::variant` reported on AVR. Found the cause with `git bisect`; copy assignment shrank from 174 to 122 bytes. | ✅ Merged |
| [**unoplatform/uno**](https://github.com/unoplatform/uno) ![stars](https://img.shields.io/github/stars/unoplatform/uno?style=flat&label=%E2%98%85&color=555)<br>Cross-platform .NET UI, C# | [#25056](https://github.com/unoplatform/uno/pull/25056): `ScrollViewer` reset the zoom when `ZoomMode` was disabled. Now behaves like WinUI. | 🔍 In review |
| [**nasa/fprime**](https://github.com/nasa/fprime) | [#6152](https://github.com/nasa/fprime/pull/6152), [#6153](https://github.com/nasa/fprime/pull/6153): CFDP file transfer sized its data from an uninitialised packet header. Fixed that and gave the header safe defaults. | 🔍 In review |

## Projects

**[tinyctrl](https://github.com/TWadi/tinyctrl)** · C99<br>
Control toolbox for microcontrollers: PID with anti-windup, Tustin discretisation, biquad filters and lead/lag compensators. No dynamic memory, unit tests against SciPy reference data, and CI that builds for GCC, Clang and MSVC and links firmware for Cortex-M0, Cortex-M4F and AVR.

**[AI Engineering Arena](https://github.com/TWadi/ai-engineering-arena)** · TypeScript · [live](https://twadi.github.io/ai-engineering-arena/)<br>
Built with a friend while we learn AI engineering: XP, quiz duels, code races and an in-browser AI lab.

## Tools I work with

- **Languages:** C, C++, C#, TypeScript, Python, VHDL
- **Embedded:** ARM Cortex-M, AVR, FPGA
- **Build and test:** CMake, GitHub Actions, GoogleTest, Unity, Linux
- **Software quality:** static analysis, architecture conformance, automotive software testing
