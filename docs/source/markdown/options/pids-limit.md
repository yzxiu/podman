####> This option file is used in:
####>   podman create, run
####> If you edit this file, make sure your changes
####> are applicable to all of those.
#### **--pids-limit**=*limit*

Tune the container's pids limit. Set to **-1** to have unlimited pids for the container. The default is **4096** on systems that support "pids" cgroup controller.
