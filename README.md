# fluid-soundfont

This a placeholder project for the two Fluid (R3) SoundFont files.

The file `FluidR3_GM.sf2` is 148Mb which is too large according to the GitHub rules to be
included in this repository.  It could be managed using LFS, but instead, 
`FluidR3_GM.sf2` and `FluidR3_GS.sf2` are posted as release files for this project

This repo is a fork of /github.com/pianobooster/fluid-soundfont .

The files for the project were originally obtianed from the
Ubuntu repo, see https://launchpad.net/ubuntu/+source/fluid-soundfont

The orginal files [README](README) and [COPYING](COPYING)

## Change log

V3.2 - 11/9/2026 Jeff Learman
  Reduced latency due to silence in the beginning of samples in various
  instruments, notably Picked Bass and Fingered Bass.
  Latency for all instruments with sharp attacks should now be under 10 ms,
  and usually under 5 ms.

