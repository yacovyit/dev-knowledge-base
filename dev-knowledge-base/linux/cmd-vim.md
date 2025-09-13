# Vim Cheatsheet

## Basic Modes
- **Command mode** – default mode (press `<Esc>` to return here).
- **Command-line mode** – execute commands (`:`).
- **Insert mode** – insert text (`i`, `a`, `o`).
- **Visual mode** – select text (`v`, `V`, `Ctrl+v`).


---

## Navigation
- `h` – left
- `l` – right
- `j` – down
- `k` – up
- `0` – beginning of line
- `^` – first non-whitespace character
- `$` – end of line
- `gg` – top of file
- `G` – bottom of file
- `:n` – go to line *n*

---

## Editing
- `i` – insert before cursor
- `I` – insert at start of line
- `a` – append after cursor
- `A` – append at end of line
- `o` – open new line below
- `O` – open new line above
- `x` – delete character under cursor
- `dd` – delete line
- `yy` – yank (copy) line
- `p` – paste after cursor
- `P` – paste before cursor
- `u` – undo
- `Ctrl+r` – redo

---

## Search & Replace
- `/pattern` – search forward
- `?pattern` – search backward
- `n` – repeat search forward
- `N` – repeat search backward
- `:%s/foo/bar/g` – replace all `foo` with `bar` in file
- `:s/foo/bar/g` – replace all in current line

---

## Windows & Buffers
- `:e file` – open file
- `:w` – save
- `:q` – quit
- `:wq` – save and quit
- `:q!` – quit without saving
- `:w filename` – save as
- `:bn` – next buffer
- `:bp` – previous buffer
- `:ls` – list buffers

---

## Visual Mode Commands
- `v` – character mode
- `V` – line mode
- `Ctrl+v` – block mode
- `y` – yank selection
- `d` – delete selection
- `>` – indent selection
- `<` – unindent selection

---

## Useful `:set` Options
- `:set number` – show line numbers
- `:set nonumber` – hide line numbers
- `:set expandtab` – convert tabs to spaces
- `:set noexpandtab` – keep tabs as tabs
- `:set tabstop=4` – set tab width
- `:set shiftwidth=4` – set indentation width
- `:set autoindent` – auto-indent new lines
- `:set ignorecase` – case-insensitive search
- `:set smartcase` – case-sensitive if pattern has uppercase

---

## Exiting Vim (quick reference)
- `:q` – quit (fails if changes)
- `:q!` – quit without saving
- `:wq` or `ZZ` – save and quit
- `:x` – save and quit (like `:wq`)

---
