# vpsGoogleColab
vpsImageforGOOGLECOLAB USAGE
to split
split -d -b 64M containerLinux.vmdk vdpIMG
with og file name containerLinux.vmdk
to restore
cat vdpIMG* > containerLinux.vmdk
