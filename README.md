# scripts

The following scripts originated from https://github.com/ocochard/BSDRP/blob/master/BSDRP/Files/usr/local/etc/rc.d/ix_affinity,
but have been modified to affine interrupt threads one per core, and only on cores on the CPU to which the NIC is attached.
