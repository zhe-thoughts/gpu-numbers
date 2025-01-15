# Numbers every programmer should know (GPU edition)
Jeff Dean's "numbers every programmer should know" table has been super useful. We should have an edition with the most important numbers when using GPU environments.

* GPU memory bandwidth: 700 ~ 1000 GB / sec. This refers to when you access GPU memory _from GPU_.
* GPU-GPU transfer bandwidth: 900 GB / sec if there's NVLink (4.0)
* GPU-CPU transfer bandwidth: unfortunately this go through PCIe with 32 ~ 64 GB / sec
