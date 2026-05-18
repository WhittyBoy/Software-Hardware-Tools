# Software-Hardware-Tools
Location of hardware tools developed to aid in hardware design, analysis, and/or testing.

1. GitHub link in header
- Topic: Public proof of technical work.
- Why it matters: OpenAI will want evidence that you can build real tools, not just use hardware tools.
- Add to header:
github.com/<username> | alexanderwhitman.dev

2. Hardware tooling project
- Topic: A named software tool for RTL validation, simulation, or synthesis-report analysis.
- Resume bullet to add:
Built a Python-based RTL regression and report-analysis tool that runs simulation/lint workflows, parses synthesis artifacts, and emits reproducible JSON/CSV summaries for hardware validation.
- Professional calibration:
Use “independent project” or “project-level exposure” so it is clear this is not production OpenAI-scale EDA work.

3. Verilog/SystemVerilog exposure
- Topic: OpenAI’s role is more likely to expect Verilog/SystemVerilog than only VHDL.
- Resume bullet or skill addition:
Project-level exposure: Verilog/SystemVerilog, RTL simulation, linting, synthesis-report interpretation.
- Do not put this in the same category as VHDL if your VHDL is much stronger. A clean skills row would be:
Hardware/RTL: FPGA/SoC, KR260, VHDL, project-level Verilog/SystemVerilog, RTL simulation/debug, SPI, ADCs, PGAs

4. CI/regression workflow
- Topic: Reproducible hardware validation.
- Resume bullet to add: Implemented GitHub Actions regression checks for RTL examples, validating simulation results and generating repeatable build/test artifacts.
- This directly supports the Hardware Tools Engineer theme of build/test infrastructure.

5. Compiler / IR concepts
- Topic: Hardware tools role likely involves compiler-style transformations.

- Resume bullet to add after building a project: Created a small IR-to-RTL code-generation demo with simple optimization passes, lowering arithmetic/dataflow operations into synthesizable Verilog.

- Professional phrasing: Working familiarity with IR, lowering, code generation, and compiler-style hardware transforms through independent project work.

6. PPA analysis
- Topic: Power, performance, and area tradeoff analysis.

- **Resume bullet to add: Parsed synthesis/resource reports to compare parameterized RTL designs across area, timing, and functional-correctness tradeoffs.

- This is important because OpenAI hardware teams care about optimization loops, not only whether a design works.

7. Metrics for your senior design project
- Topic: Turn the KR260/AI/RF project into measurable engineering evidence.
Add any true metrics:

- Trained lightweight neural-network model on [N] custom samples and deployed control logic on KR260 FPGA/SoC for real-time beam-steering demonstration.

- or: Demonstrated batteryless RF power transfer over [distance] using Yagi antennas, impedance matching, RF-to-DC conversion, and FPGA/SoC control.

- Add distance, frequency, dataset size, model type, latency, power delivered, number of test runs, or demo success rate if you have them.

8. Hardware validation automation
- Topic: Convert SEL validation work into tooling language.

- Possible bullet if true: Developed Python/C-based validation scripts or structured test procedures to improve repeatability of board-level hardware debug and component qualification.

- If you used procedures but not scripts, phrase it honestly: Standardized validation procedures and measurement workflows to improve repeatability of board-level debug and component qualification.

