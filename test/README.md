This is just a small collection of very quick tests to run on a
RapidDisk attached RAM disk raw block device. To compile: make

To execute in place:

```console
# ./rxio
# ./rxioctl
# ./rxflush
```

Note that they will only test the node named /dev/rd0. You can change
this in the code if necessary and recompile.
