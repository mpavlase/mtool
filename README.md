mtool (MoM tool)
================

CLI tool for storing constants and interoperate with MoM (Memory Overcommit Manager).

MoM is tool for shaping various resources such as allocated memory per virtual machine (VM) or CPU utilization.
These actions are driven by rules. It usually contains constans (thresholds etc.). It is not necessary to be
part of hardcoded rules. It can be read from XMl definition VM via libvirt API.

'mtool' have under control this constants. It stores and organize them into plans. These plans can be assigned
with VM and set proper values of constans.
