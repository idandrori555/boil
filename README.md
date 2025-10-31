# 🔥 Boil

**Boil** is a lightweight CLI tool for managing file templates (boilerplates) and quickly generating files or project structures. Perfect for developers who want to save time and avoid repeating the same setup over and over.

---

## Features

* ⚡ Copy predefined templates into the current directory
* 📂 List all available templates
* ➕ Add new templates easily
* 📝 Simple and minimal — works with files or directories

---

## Installation

1. Clone or download this repository
2. Run the installer:

```bash
./install
```

---

## Usage

### 1. Show help

```bash
boil --help
```

### 2. List templates

```bash
boil --ls
```

### 3. Add a new template

```bash
boil --new <folder_or_file>
```

Example:

```bash
boil --new ./mymake
```

### 4. Generate files from a template

```bash
boil <template-name>
```

Example:

```bash
boil mymake
```

This will copy the contents of `~/.boil/mymake` into your current directory.

---

## Template Structure

Templates can be a **single file** or a **folder** with multiple files.
Example structure:

```
~/.boil/
 ├── mymake/
 │    └── Makefile
 ├── cpp-basic/
 │    ├── main.cpp
 │    └── Makefile
 └── web/
      ├── index.html
      └── style.css
```

---

## Contributing

Contributions are welcome!

* Add new features, templates, or improve the CLI
* Open an issue or pull request on GitHub

---

**Boil** – save time, stop repeating yourself! 🔥
