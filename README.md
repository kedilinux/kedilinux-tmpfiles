# Kedi GNU/Linux tmpfiles setup service, from chimera-linux/sd-tools

This is a fork of chimera-linux/sd-tools, for tmpfiles service, originally from systemd, built for Kedi GNU/Linux (or other systems for that matter) and GNU libc. As with other tmpfiles services, this reads the configuration file from tmpfiles.d.

The apparent init.d script in /etc/init.d for this package is usually named after the previous tmpfiles setup service on most Kedi systems. This is so that existing Kedi Linux systems do not break and generate a stray service in the sysinit runlevel.
