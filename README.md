# n42_work_log

## Week 3
- (NEUR-147) Integrate X300-reset script into CMake build file. Learnt about Cmake compilation pipeline along the way.
- (NEUR-149) Created a new .cpp executable that serializies a binary output from the X300-API, down-samples the input to a designated value, and de-serializes the samples back into a bianry file.
- Re-factored most instances of raw pointers in the SDR c++ code base, reducing gigabytes of memory leaks to zero. Making the SDR code memory-safe.
