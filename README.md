# Random-Stuff

just to play, nothing productive


Copy files to USB Stick Nnamed "No Name" on Mac OS
ls -1 /Volumes/ | grep NAME | xargs -I{} -P 10 cp /Volumes/Files/0* "/Volumes/{}/"
