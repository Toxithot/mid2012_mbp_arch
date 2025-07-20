# mid2012_mbp_arch
description of steps taken to resolve basic functionality on a mid2012 non-retina macbook pro

bluetooth: you need https://github.com/winterheart/broadcom-bt-firmware and to enable bluetooth.service
wifi: you need https://github.com/theperspectiv/bcm4331-arch-fixes info in readme
fan control: mbpfan from the aur, config in /etc/mbpfan.conf
power profiles: install tuned-ppd from main repos, replaces power-profiles-daemon but actually works on this piece of shit

zips of linked githubs included in this repo for sake of my own backup just in case things go horribly sideways down the line
