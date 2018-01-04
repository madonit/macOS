# macOS

1. Открыть терминал на рабочем столе и выполнить

sudo cd Desktop

wget http://support.apple.com/downloads/DL1944/en_US/macOSUpdCombo10.13.2.dmg

hdiutil convert macOSUpdCombo10.13.2.dmg -format UDTO -o macOS

mv macOS.cdr macOS.iso
