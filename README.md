purgekernel
===========

purge older, unused kernels from your ubuntu installation

* copy purgekernel to /usr/sbin/
* copy 88pergekernels to /etc/apt/apt.conf.d/

On each invokation of apt purgekernels will check if there are kernels to be
removed. The newest, current running, and previous kernel are kept.
