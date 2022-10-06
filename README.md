## rEFInd_untitled
[rEFInd](https://www.rodsbooks.com/refind/)
Minimal theme for the rEFInd boot manager 

### Installation

1. Locate rEFInd folder `/Volumes/ESP/EFI/refind`, (most likely would depend on where ESP is moundted and where rEFInd is installed).
   The commands `fdisk -l` and `mount` may help.

2. Create a `themes` folder inside it.

3. Clone this repo into the `themes` folder

4. Add `include themes/rEFInd-minimal/theme.conf` to `refind.conf`


### Credits

This theme was inspired by both themes made by [rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal);  [@EvanPurkhiser](https://github.com/EvanPurkhiser) and [refin-ambience](https://github.com/lukechilds/refind-ambience); [@lukechilds](https://github.com/lukechilds)
