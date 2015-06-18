Put it into `~/.config/geany/filedefs`. Do not forget to modify `filetype_extensions.conf`:

* add file extension into `[Extensions]` group, e.g. `Nim=*.nim`
* append new filetype into `[Groups]`, e.g. `Misc=Spec;SELinux;Nim;`

Selinux extensions:
```
SELinux=*.te;*.if;*.fc;*.te.in;*.fc.in;*.if.in;mls;mcs;constraints;
```
