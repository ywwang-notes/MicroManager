# [MicroManager](https://micro-manager.org/)
see also notes about [microscopy](https://github.com/ywwang-notes/notes/blob/master/microscopy.md)

## Beanscripts for MicroManager
* testWheel: test the maximum speed of switching between two filters. Results: about 200 ms.
* multiMDA: execute multiple MDAs (multidimentional acquisitions) with switching filters. Results with test_MDA configuration: about 1 s. 

## To do
* multiple-MDA speedup: try
  * MDA without image window pop-ups
  * change channel ([example code](https://micro-manager.org/w/images/c/ce/ManualAcq.bsh))
  * setProperty and snap
## Tidbits
