# Vim Guide

## List

- [Modes](#modes)
- [Movement](#movement)
- [Search](#search)
- [Editing](#editing)
- [Copy & Paste](#copy--paste)
- [Repitition](#repetition)
- [Undo & Redo](#undo--redo)
- [Save & Quit](#save--quit)
- [Others](#others)

## Modes

There are two modes in vi: **normal** and **insert**.

- from **normal** to **insert**: `i`
- from **insert** to **normal**: `esc`

In **insert** mode, you just type characters as you need.

The following commmands are used in **normal** mode.

## Movement

### Characters

- up: `k`
- down: `j`
- left: `h`
- right: `l`

### Words

- back (to the start of current or previous word): `b`
- end (to the end of current of next word): `e`
- next (to the start of next word): `w`

### Lines

- go to line $n: `$nG`
- go to start of current line: `0`
- go to end of current line: `$`

### Documents

- go to start of current document: `gg`
- go to the end of current document: `G`

## Search

- character $c inline: `f$c` to next, `F$c` to previous
- the other part of current bracket: `%`
- current word: `*` to next, `#` to previous
- regular expression $r: `/$r`, `n` to next, `N` to previous

## Editing

This will switch to **insert** mode.

- insert: `i`
- append: `a`
- new line after current line: `o`
- new line before current line: `O`

## Copy & Paste

- copy: all deletions will copy the content
- copy: todo
- paste: `p`

## Repetition

- do some $ops over $n times: `$n$ops`
- do previous ops: `.`

## Undo & Redo

- undo: `u`
- redo: `ctrl+r`

## Save & Quit

- save: `:w`
- quit: `:q`, `:q!` to force quit
- save and quit: `:wq`, `:wq!` to force save and quit

## Others

- line number: `:set nu` to show, `set nu!` to hide
