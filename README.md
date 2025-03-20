# Замени версию на свою и выполни 3 команды поочерёдно:
blocs_ver="v.5.2.8";
sudo mv /Applications/Blocs.app/Contents/Resources/en.lproj/Localizable.strings /Applications/Blocs.app/Contents/Resources/en.lproj/Localizable.strings.bak_$RANDOM;
sudo curl -o /Applications/Blocs.app/Contents/Resources/en.lproj/Localizable.strings "https://raw.githubusercontent.com/MKC-Archive/Blocs-Russain-FAN-Locale/main/v.5.2.8/modded/Localizable.strings"
