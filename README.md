# Description
This repository holds the documentation for the final project of the CIIC 4082 course at the UPRM.

# Overview
- Instructions -> [instructions.txt](instructions.txt)
- Editable Documentation -> [/docs/documentation.adoc](documentation.adoc)
- Submittable Documentation -> [/docs/documentation.pdf](documentation.pdf)
- Test groups and cases ->  [/tests](/tests)
- Main Circuit -> [RISC V CPU](https://circuitverse.org/simulator/edit/ciic4082_native_single_cycle_riscv-493de537-b42c-4f63-b8da-7b97ee345f76)

# Rerendering Submittable PDF
Ensure you have [asciidoctor-pdf](https://docs.asciidoctor.org/pdf-converter/latest/install/) installed. Then run in your terminal:
```bash
cd docs && asciidoctor-pdf documentation.adoc
```
