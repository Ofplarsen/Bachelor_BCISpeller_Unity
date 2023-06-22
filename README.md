# BCI Speller in Unity
This Unity project implements a Brain-Computer Interface (BCI) speller using NeuroPype. The BCI speller allows users to spell words using their brain activity and is a part of William G. Tresselt and Olav F. P. Larsen's bachelor's thesis (Computer Science, NTNU). The BCI Speller combines eye tracking with SSVEP to create an accurate speller, with fewer frequencies used, due to being able to make clusters of frequencies using the eye trackers, contrarty to the
standard SSVEP Spellers.

## Task
The initial task was to synchronize an eye tracker with an EEG. The equipment should have a latency of less than 1 ms. The group was not able to do this, due to the limitations of the eye tracker's sampling rate (120 hz). When the equipment was synchronized as good as possible with the introduced limitation, the group was able to prove the synchronization by creating a BCI Speller in a VR environment utilizing SSVEP and eye tracking. 


