+++
date = 2026-11-07
draft = true
title = 'Find & replace across files'
+++

```cfdo %s/stringOne/stringTwo/g | update | bd```

## In short

1. Telescope grep

```
    <leader>sg _stuff_
```

2. Add to Quickfix list

```
    CTRL+Q
```

3. `cfdo %s/stuff/newstuff/g | update | bd`

## Glossary
- cfdo: Change File Do
- cdo: Change Do (slower)
- grep: global regular expression print ("find")

## Credit
[Ben Frain](https://benfrain.com/neovim-how-to-do-project-wide-find-and-replace/)
