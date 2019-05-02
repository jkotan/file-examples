A.R., FS-EC

Test data taken with Dectris Eiger 4M using lz4 Bitshuffle mode.
Data was taken by temporarily moving/holding an Fe55 source in front of the
detector and 10 frames were taken in total (with 5 frames per h5 set).

Notes:
* the detector writes a master file e.g. <basename>master.h5 when initialising data
  acquisition which contains detector specific 'Metadata' and links to the
  h5 data files supposingly being created during the scan
* frames taken when havin started the acquisition are then written into
  seperate individual data file(s) <basename>data_<counter>.h5
  Each "frame data" file is a separate h5 file and can be accessed individually (i.e.
  h5 family split property is NOT applied)

THX to Jan G., P06 for taking and providing the data.

A.R., Mai 2, 2019
