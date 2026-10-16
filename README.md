# Hi, I'm Wadi 👋

Associate Embedded System Software Testing at **Expleo Germany**, working on the quality of automotive software. I write C and C++ for embedded systems and control, contribute to open-source projects in that space, and co-founded [AI Engineering Arena](https://github.com/TWadi/ai-engineering-arena), a free platform for learning AI engineering.

- 📄 First author of a paper on architecture conformance in automotive software, accepted at **TAV-53**
- 🛰️ Open-source contributor to **NASA JPL's F´** flight software framework
- 🧩 Contributor to the **Embedded Template Library** (ETL), a C++ library for microcontrollers
- 🤖 Co-founder of **[AI Engineering Arena](https://github.com/TWadi/ai-engineering-arena)**, a free, open-source platform for learning AI engineering
- 🎛️ Author of **[tinyctrl](https://github.com/TWadi/tinyctrl)**, a tested C99 control library for microcontrollers
- 📍 Berlin · 📫 [LinkedIn](https://www.linkedin.com/in/wadi-touil-117472319/)

## Publication

**From Static Analysis Findings to a Quality Score: An Architecture Conformance Index for Automotive Software**<br>
W. Touil, P. Gohil, M. Schmidt, J. Wegener. Accepted at TAV-53, the 53rd workshop of the GI special interest group *Test, Analysis and Verification of Software* (Fachgruppe TAV), 2026.

Architecture-conformance checkers list the dependencies that break architectural rules, but they don't say how good the architecture is overall. The paper introduces the **Architecture Conformance Index (ACI)**, which turns those findings into one score from 0 (severe erosion) to 100 (no violations), and evaluates it on industrial automotive software.

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

**[AI Engineering Arena](https://github.com/TWadi/ai-engineering-arena)** · co-founder · TypeScript · [live](https://twadi.github.io/ai-engineering-arena/)<br>
A free, open-source (Apache 2.0) platform for learning AI engineering, co-founded with [Ghassen](https://github.com/GhassenJamoussi99). A 40-week roadmap from a RAG course to production LLM apps and agents, with quizzes, live quiz duels, code races and an in-browser AI lab.

## Certificates

All from Udemy; each title links to the certificate.

**Embedded and hardware**
- [Mastering Microcontroller: STM32-LTDC, LCD-TFT, LVGL (MCU3)](https://www.udemy.com/certificate/UC-40928709-fa68-43c8-9adc-05f5e54e742e/) · 2026
- [The Complete Electronics Course: Analog Hardware Design](https://www.udemy.com/certificate/UC-26b0d3db-efca-4a20-9fa1-ad78cf0c2bb8/) · 2026
- [Digital Electronics](https://www.udemy.com/certificate/UC-d2794cd4-489c-43e3-abd8-0b16526be2a4/) · 2026
- [Computer Architecture and Computer Organization Masterclass](https://www.udemy.com/certificate/UC-19d62937-2563-4ef2-82a1-5592e910888b/) · 2025
- [8051 Microcontroller Architecture](https://www.udemy.com/certificate/UC-acc6a3c5-4c2e-45a0-9274-43e32d7e7781/) · 2023

**C and C++**
- [C/C++ Projekte: Make, CMake, Unit Tests und Tooling](https://www.udemy.com/certificate/UC-87eec912-d62f-48bc-bec3-8191897deb91/) · 2026
- [Qt 6 Core with C++](https://www.udemy.com/certificate/UC-dd68aff8-3f01-498a-b51d-e65a41a7b10d/) · 2026
- [Le C par la pratique : plus de 100 exercices corrigés](https://www.udemy.com/certificate/UC-7f38f98a-8b35-4751-83b3-66b04e2447f7/) · 2020

**Web**
- [Formation Complète Développeur Web](https://www.udemy.com/certificate/UC-c60f9f5c-bb6f-4544-9ab2-a56b0310b82e/) · 2020

## Tools I work with

- **Languages:** C, C++, C#, TypeScript, Python, VHDL
- **Embedded:** ARM Cortex-M (STM32), AVR, 8051, FPGA
- **Frameworks:** Qt 6, LVGL
- **Build and test:** CMake, GitHub Actions, GoogleTest, Unity, Linux
- **Software quality:** static analysis, architecture conformance, automotive software testing
- **AI engineering:** RAG (retrieval-augmented generation), LLM applications
