# Quartz

Welcome to the my project for all of my CPU design ideas. This repository will contain all of the circuit designs, tools made during development, and (hopefully) documentation for a CPU designed using basic logic chips. This project is partially because of my studies in computer science and CPU architecture. It’s structured to evolve over three planned iterations, gradually introducing more complexity and advanced features.

## Project Overview

The goal of this project is to design and potentially build a fully functional computer using only basic logic gates, keeping it as simple and understandable as possible. The design is being developed using **[Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution)** for circuit simulation and design, and code for tools written in **C**, **C++**, or **Python** to handle tasks like ROM generation and code compilation.

### Project Iterations

The project is structured in three main iterations, each focusing on increasing complexity and new features:

- **Version 0**: A minimalistic, vertical slice of the project. This version will contain the core CPU functionalities, so that it can be improved in later iterations.
- **Version 1**: Builds upon Version 0, introducing additional instruction types, pipelining, and hopefully improving performance.
- **Version 2**: Building on Version 1, adding support for multiple cores, caching mechanisms, and security features such as virtual addressing and protection rings.

### Areas of Development

1. **Circuit Design**: All circuits are designed in **[Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution)**, with the possibility of later implementing these designs with physical PCBs.
2. **ROM Generation**: Any of the ROM chips used in the control logic of the CPU will be generated.
3. **Code Generation and Compilation**: A custom compiler will be written for a flavour of assembly for each ISA.

## Getting Started

### Prerequisites

Before using this project, ensure you have the following installed:

1. CMake: Version 3.10 or higher is required to build the project.
   - You can download CMake from [cmake.org](cmake.org).
2. A C Compiler: You will need a C compiler (such as GCC, Clang, or MSVC) to build the library.
3. Logisim-evolution: This is used to design/simulate all of the circuits. This runs on Java so requires your operating system to support the JRE.
   - You can download the latest release of Logisim-evolution from [here](https://github.com/logisim-evolution/logisim-evolution/releases/latest).

### Installation

To get started with this project:
1. Clone this repository: `git clone https://github.com/yourusername/your-repo-name`
2. Compilation steps to be determined but will most likely use cmake

### Usage



## Licence

Quartz is licensed under the MIT license. See the [LICENSE](https://github.com/jdf18/Quartz/blob/main/LICENSE) file for more details.