# librarian-puppet-snap
Packaging stuff to put librarian-puppet in a snap

Current status:
 - It builds and runs correctly without confinement
 - It doesn't run correctly with confinement because snaps cannot use `chmod` and `chown`. I tried to fix it with `snapcraft-preload`, but that doesn't seem to work either.
