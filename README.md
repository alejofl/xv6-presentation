# xv6 Presentation

Visual support for explanation of xv6 operating system. Optimized for 80x20 UTF-8 terminals.

## Slides

Each slide is a text file in diapositivas/ directory.
`make` generates the file 'presentacion.txt' which is ought to be presented.
`make presentacion.html` generates an HTML version. 'aha' must be compiled first with `make aha.c`.

The slides are made of plain text with UTF-8 characters.
See:

  * <https://en.wikipedia.org/wiki/ANSI_escape_code>
  * <https://www.lihaoyi.com/post/BuildyourownCommandLinewithANSIescapecodes.html>

Other useful links:
 * <https://en.wikipedia.org/wiki/Box-drawing_character>
 * <https://www.asciiart.eu/computers/computers>
 * <https://manytools.org/hacker-tools/ascii-banner/>
 * <https://asciiart.club/>

## Presentation

It is recommended to use the following command:

```
less -R <archivo.txt>
```

Press `f` to go the next slide and `b` to go back

## Acknowledgements

* <https://github.com/jcodagnone/itba-ieee-computer-curso-git-adv>
* <https://github.com/theZiz/aha/blob/0754098662e0221326e7cdb7bb5f65a98cc0f698/aha.c>
 
## Template

```
╭──────────────────────────────────────────────────────────────────────────────╮
│ 🡆 ABCDEFGHIJK                                                                │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
│                                                                              │
╰──────────────────────────────────────────────────────────────────────[ XX ]──╯
```