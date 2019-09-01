# 2048

2048 in Malbolge Unshackled (20-trit rotation variant).

## How to run it

This might be a tricky part, because naive Haskell interpreter will take ages upon ages to run this. TIO has decent Malbogle Unshackled interpreter, but sadly I won't be able to use it (limitations). The best one I could find is the fixed 20-trit rotation width variant, that performs not great (hogs just 1GB of RAM), not terrible (it's quite slow on my PC tho). To make the interpreter a bit faster, I've removed all the checks from Matthias Lutter's Malbolge Unshackled interpreter. The code is in file `fast20.c`. It has to be compiled to be ran obviously. The Malbolge code is compressed inside 2048.7z archive using PPMd algorithm.

## System requirements

1GB of RAM, i9-9900 should be sufficient to run at sixteenth part a frame per second.
