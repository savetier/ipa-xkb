# ipa-xkb
An XKB-layout for the International Phonetic Alphabet (IPA)

# Install (tested on Manjaro and EndeavourOS)

The easiest way to install this layout is to to download the file 'ipa' and rename it to one you would never use (I renamed it to 'be') and replace this file in the /usr/share/X11/xkb/symbols folder. After that you simply need to add the Belgian (or whichever you have chosen) layout to your keyboard layout profile. 

For example:

	wget https://raw.githubusercontent.com/savetier/ipa-xkb/refs/heads/main/ipa

	sudo mv ipa /usr/share/X11/xkb/symbols/be

(Change 'be' in the end to the one you want to replace)
