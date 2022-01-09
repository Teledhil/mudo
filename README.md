# askpass

Script for muting your microphones while writing your password.

- Copy the `askpass` script to `/SOME/PATH/askpass`
- Edit `/etc/sudo.conf`, enter some `Path askpass /SOME/PATH/askpass`
- Add an alias `alias sudo="sudo -A"`
