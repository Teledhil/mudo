# mudo

My script for muting my computer microphones while writing passwords with
sudo. Useful to avoid leaking your password while recording your screen.

- Copy the `mudo_askpass` script to `/SOME/PATH/mudo_askpass`.
- Edit `/etc/sudo.conf`, enter some `Path askpass /SOME/PATH/mudo_askpass`.
- Add an alias `alias mudo="sudo -A"` to your shell.

Now you can use mudo instead of sudo.
