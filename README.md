## Programs

This is a collection of PDP-6 programs.
Mostly from MIT. Some are binary, some are source.
For more versions see https://github.com/pdp-10/its-vault.

## MACDMP

MACDMP MOBY1: RIM10, moby memory, UT, 340 display

MACDMP 6u256: RIM2, moby memory, UT; configurable

## DDT

early version in @ LISP at 34000

NTSDDT N77H: configured for PDP-10 with moby,
but works on PDP-6

## TECO

@ TECO: 256k dump; binary patched for DSKDMP

## MIDAS

@ MIDAS: 256k dump; symbols

## STINK

@ STINK: not tested yet

## LISP

@ LISP: 16k dump; symbols; probably from 1966

## SYSTEM GEN

Formats DECtape in three stages:
write timing and mark tracks.
write block marks.
write boot loader, MACDMP and directory (MAC format).

assumptions: 551 microtape control.
loader jumps to 16k MACDMP.
MACDMP in memory for 16k config.

C.f. https://www.saildart.org/MARK.FAI[D,SYS] for a similar program from Stanford.

## SPACEWAR

WAR 44 and STARS 1: original code.
MATH 1: taken from somewhere else.
