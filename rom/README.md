ROM Disassemblies
=================

These are pulled from various locations on the 'net and extracted to
have everything conveniently accessible in one place and to allow
linking directly to extracted files.

- `vic_src`: This appears to be the original Commodore source, both
  from the text itself and comparision with the [C64 KERNAL
  source][cbmsrc]. The comments are poor and the label names are often
  terrible. Includes both `.src` and `.lst` files; the latter are
  handy because it makes it very easy to see both names and addresses
  for any particular line of code. (From [zim-vic20]
  `vic_src.tar.gz`.)
- `vic20_rom_disassembly.txt`: 2005 disassembly by Lee Davison. Well
  commented. Labels are all in `LAB_aaaa` format, where `aaaa` is just
  a hex address, but comments at the call locations generally explain
  what's being called. (From [zim-vic20].)
- `firmware/`: 1981-82 (?) disassembly by Willi Kusche into several
  separate files. Relatively few comments. Some non-address label
  names. (From [zim-vic20] `firmware.zip`.)
- `cini/`: 1995-1999 disassembly by Richard A. Cini, Jr. This is the
  slightly updated 2016 version from the forum.6502.org thread; [cini]
  (at the bottom of the "VIC-20" section) still has an older version.
  See also articles below.

Resources and Documentation:
- [_C=Hacking_] issues #17-#21, "VIC-20 Disassembly Project" series by
  Richard Cini.
- ["Commented VIC 20 ROM disassembly."][lee12] thread on
  forum.6502.org. This includes links to some of the disassemblies
  above.
- [_VIC-20 Programmer's Reference Guide_][progref] from Commodore. pp.
  170-210 have summaries followed by more details on memory locations
  and their meanings and KERNAL routines.



<!-------------------------------------------------------------------->
[_C=Hacking_]: http://ffd2.com/fridge/chacking/
[cbmsrc]: https://github.com/mist64/cbmsrc
[cini]: http://www.classiccmp.org/cini/systems.htm
[lee12]: http://forum.6502.org/viewtopic.php?t=2041
[progref]: https://archive.org/details/VIC-20_Programmers_Reference_Guide_1983_Commodore_fourth_printing/
[zim-vic20]: http://www.zimmers.net/anonftp/pub/cbm/src/vic20/
