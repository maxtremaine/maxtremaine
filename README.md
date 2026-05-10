Max Tremaine's Github Profile
=============================

CEO @ [sherpa°](https://www.joinsherpa.com)

Coding is mostly for fun.

Public Repositories
-------------------

- [ai-playbook](https://github.com/maxtremaine/ai-playbook): Workflows that I use with AI assistants, and a simple build system for shared constants.
- [sudoku-solvers](https://github.com/maxtremaine/sudoku-solvers): A project to help me learn new programming languages.
- [maxtremaine.github.io](https://github.com/maxtremaine/maxtremaine.github.io): My personal website. Not as exciting as me IRL.
- [sankey-template](https://github.com/maxtremaine/sankey-template): A flexible and portible Sankey Diagram generator in vanilla JavaScript.
- [mermaid-template](https://github.com/maxtremaine/mermaid-template): A straightforward way to use the most recent Mermaid.js features.
- [REPEATRANGE](https://github.com/maxtremaine/REPEATRANGE): Custom formula for Google Sheets. Repeats a range.
- [python-style-range](https://github.com/maxtremaine/python-style-range/): A very basic implementation of the Python 'range' generator in ES6.
- [SVG Clock](https://github.com/maxtremaine/svg-clock): I like clocks, so I made one in SVG. It ticks.

[Sudoku Solvers](https://github.com/maxtremaine/sudoku-solvers)
--------------

"Why have you written so many Sudoku solvers?" — "For fun, and to compare new programming languages as they gain prominence."

Most implementations follow a similar design but stay true to each language's idioms. Here's the current collection:

| Language          | Time (ms) | Status          | Repository |
|:----------------- | ---------:|:--------------- |:---------- |
| Rust              | 11        | ✅ Complete     | [sudoku-solver-rust](https://github.com/maxtremaine/sudoku-solver-rust) |
| Go                | 15        | ✅ Complete     | [sudoku-solver-go](https://github.com/maxtremaine/sudoku-solver-go) |
| Swift             | 60        | ✅ Complete     | [sudoku-solver-swift](https://github.com/maxtremaine/sudoku-solver-swift) |
| TypeScript (Deno) | 66        | ✅ Complete     | [sudoku-solver-typescript](https://github.com/maxtremaine/sudoku-solver-typescript) |
| JavaScript (Node) | 74        | ✅ Complete     | [sudoku-solver-javascript](https://github.com/maxtremaine/sudoku-solver-javascript) |
| Python            | 77        | ✅ Complete     | [sudoku-solver-python](https://github.com/maxtremaine/sudoku-solver-python) |
| Pandas            | 1,553     | ✅ Complete     | [solve_with_pandas.py](https://github.com/maxtremaine/sudoku-solver-python/blob/master/solve_with_pandas.py) |
| Elixir            | TBD       | 🚧 In Progress  | [sudoku-solver-elixir](https://github.com/maxtremaine/sudoku-solver-elixir) |
| Zig               | TBD       | 🚧 In Progress  | [sudoku-solver-zig](https://github.com/maxtremaine/sudoku-solver-zig) |

**Note:** All solvers use the same human-readable `.sudoku` file format and CLI workflow for easy comparison. A full central guide with benchmarks, format specification, and more details is coming soon.

### Future Languages
- Scala
- Elm
