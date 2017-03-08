# Whonix ESXi
Whonix version 13.0.0.1.4 aptation for VMware ESXi

.mf - .ovf sha1 has deleted
.mf - .vmdk1 sha1 has changed

OVFs reformatted for VMware - chaged ovf:size, IDE changed to SAS, DVD removed, etc.

How to:

1. Download Whonix
https://www.whonix.org/wiki/VirtualBox

2. Unzip .ova file (7Zip) or (OVFTool --lax)

3. Replace .mf file

4. Replace .ovf file

5. Import to ESXi/VCenter

6. sudo nano /etc/whonix.d/30_whonixcheck_default.cong Change WHONIXCHECK_NO_EXIT_ON_UNSUPPORTED_VIRTUALIZER="0" to "1"
