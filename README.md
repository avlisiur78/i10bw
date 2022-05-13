
This Repository is meant to install chromeos flex on /dev/mmcblk2 on a device

To work after flash your usb or sdcard with the recovery image you have to make the following change on the file: "chromeos-installer-0.0.3-r3589.ebuild" or equivalent on "STATE/var_overlay/db/pkg/chromeos-base/chromeos-installer-0.0.3-r3589/"

And Replace link info on "HOMEPAGE=" to "https://github.com/avlisiur78/i10bw/tree/main/i10bw/"

So it should look like "HOMEPAGE="https://github.com/avlisiur78/i10bw/tree/main/i10bw/"


Tested and working on cube i10-bw
