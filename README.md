# TIFF YCbCr subsample test fixtures

Security-research fixtures. Uniform `0x80` YCbCr 32x32 images with a patched
`YCbCrSubsampling` (tag 530) value. Used to characterise decoder behaviour
across subsample geometries.

`sol_11` / `sol_22` / `sol_44` are the original 1x1 / 2x2 / 4x4 set.
`sub-*` are the same file with tag 530 patched to the named geometry.

No real data. No exploits.
