socket.io-computer
==================

a collaborative virtual machine

## External dependencies
  * qemu
  * vnc snapshot


## Creating an image
`qemu-img create -f qcow2 winxp.img 3G`

## Starting it with raw qemu
`qemu- -m 256 -hda winxp.img -cdrom <iso_name> -monitor stdio -boot d`


## Starting the socket.io computer (THE REAL DEAL)
`node app.js & node index.js & node emu.js &`
