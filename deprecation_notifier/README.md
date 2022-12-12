Overview
========

DeprecationNotifier is a small utility to nag users into upgrading their machine. It's intended as a penultimate
'stick' after the user has ignored the 'carrot'.

It is intended to be launched on login as a LaunchAgent and it will pop-up a full-screen
overlay every hour (configurable) with a countdown before the user can close the
window and return to work. Each time the window appears the countdown gets a little
longer until it reaches a configurable threshold.

Features
--------

  - Works on multiple monitors.
  - Checks that the current OS version is lower than the desired version and exits if it isn't.
  - Configurable using a simple strings file.

Customizing
-----------

All customization should be possible in Localizable.strings. If there's something
you want to customize that isn't possible in that file, let us know.

