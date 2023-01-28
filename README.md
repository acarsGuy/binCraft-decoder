# binCraft-decoder
- A decoder library for readsb *.binCraft files for python
- Supporting decompressing of ZSTD compressed files (aircraft.binCraft.zst)
- Decoder returns aircraft.json like dict

## Example useage
`
import binCraft_decoder

data = binCraft_decoder.binCraftReader('aircraft.binCraft.zstd',zstd_compressed=True)

print(data)
`
