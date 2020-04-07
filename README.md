WinMTR (PUBG)
==============
**WinMTR (PUBG)** in an extended fork of [WinMTR Redux](https://github.com/White-Tiger/WinMTR)

### Reasons to fork
We want to customize WinMTR for PUBG(Player Unknown's Battlegrounds).
PUBG uses VC2017 as default compiler, so we need to upgrade original WinMTR Redux project to VC2017.
We also change somethings for PUBG.

### Changes

Change visual studio version to VS2017.

Add 'send report' button. 
This can post Json report to HTTP server.

Add '-auto_report' param.
This make 'send report' automatically in specified seconds.
