# mid2012_mbp_arch
description of steps taken to resolve basic functionality on a mid2012 non-retina macbook pro

modprobe wl applesmc coretemp btusb

bluetooth: broadcom-wl-dkms + https://github.com/winterheart/broadcom-bt-firmware and to enable bluetooth.service

wifi: https://github.com/theperspectiv/bcm4331-arch-fixes info in readme

fan control: mbpfan from the aur, config in /etc/mbpfan.conf

power profiles: install tuned-ppd from main repos, replaces power-profiles-daemon but actually works on this piece of shit

entirely possible i've done something superfluous in here, as i was trying a billion things till stuff worked and i'm working backward through terminal logs to try to write this so i don't have to bang my head off of these walls again.

hwprobe https://linux-hardware.org/?probe=67da6fc80d says audio "detected" but can confirm it's working just fine, headphone jack and all so not sure what's up with that, probably some weirdly specific driver needs enabled. likewise for ethernet, as without ethernet i never would have gotten through the install or gotten wifi going.
