# Language Processors
An undergraduate academic project delving into the fundamentals of language processors from a practical viewpoint.

## Installation
**1. Install `ply`[^1]:**
```bash
pip install ply
```
**2. Clone the repository:**
```bash
git clone https://github.com/SanKiril/acad-Lang_Proc
```

## Usage
### 1<sup>st</sup> Assignment - Lex & Yacc
The first assignment involved designing and implementing a lexical and syntactic analyzer for AJSON (Almost a JavaScript Object Notation), a custom file format based on JSON. The analyzer uses the `lex` and `yacc` modules from the Python PLY (Python Lex-Yacc) library[^1].

**1. Change directory to `1-Lex_Yacc`:**
```bash
cd ./1-Lex_Yacc
```
**2. Run `main.py` file:**
```bash
python3 main.py <path>.ajson [--mode=<mode>]
```
- `<path>`: path to an AJSON file. Examples in [tests](./1-Lex_Yacc/tests)
- `<mode>`: 0 (default) = lexer & parser || 1 = lexer
---
### 2<sup>nd</sup> Assignment - 
**1. Change directory to `2-`:**
```bash
cd ./2-
```
**2. Run `main.py` file:**
```bash
python3 main.py
```
---
### 3<sup>rd</sup> Assignment - 
**1. Change directory to `3-`:**
```bash
cd ./3-
```
**2. Run `main.py` file:**
```bash
python3 main.py
```
---
## Authors
- Santiago Kiril Cenkov Stoyanov ([@SanKiril](https://github.com/SanKiril))
- Adrián Ruiz Albertos ([@solucionesfuerzabruta](https://github.com/solucionesfuerzabruta))

## License
This project is licensed under the terms of the **MIT License**. See the [LICENSE](./LICENSE) file for details.

[^1]: https://github.com/dabeaz/ply
