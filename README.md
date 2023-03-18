# reveng
REVerse ENGineer html malware

Reveng automatically detects, decodes, deobfuscates, and formats html and javascript.
It crawls through the code and will detect and reverse engineer nested sripts and html.

```
██████╗ ███████╗██╗   ██╗███████╗███╗   ██╗ ██████╗ 
██╔══██╗██╔════╝██║   ██║██╔════╝████╗  ██║██╔════╝ 
██████╔╝█████╗  ██║   ██║█████╗  ██╔██╗ ██║██║  ███╗
██╔══██╗██╔══╝  ╚██╗ ██╔╝██╔══╝  ██║╚██╗██║██║   ██║
██║  ██║███████╗ ╚████╔╝ ███████╗██║ ╚████║╚██████╔╝
╚═╝  ╚═╝╚══════╝  ╚═══╝  ╚══════╝╚═╝  ╚═══╝ ╚═════╝ 
                                                    

Copyright (C) 2023  XenophonSec
This program comes with ABSOLUTELY NO WARRANTY; for details type '-w'.
This is free software, and you are welcome to redistribute it
under certain conditions; type '-c' for details.

=====================================================================

Initiated at: Fri Mar 17 2023 23:42:37 GMT-0400 (Eastern Daylight Time)

Usage:
  reveng [OPTIONS] [ARGS]

Options: 
  -f, --file FILE        The malware to reverse engineer
  -o, --out [DIR]        The output directory (Default is .)
  -w, --warrenty BOOL    Show warrenty
  -c, --conditions BOOL  The output directory
  -v, --version          Display the current version
  -h, --help             Display help and usage details
```

## Install

```
npm i -g @xenophonsec/reveng
```
