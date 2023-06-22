# n42_work_log
## Week 1
- Set up development environment,
- Understanding software architecture and coding paradigms
- Learning development pipeline
- Create&test 2 builds of custom linux iso for future hardware usage. The latest build runs in 5.15.0-72-generic kernel with preinstalled libhud library.

## Week 2
- (NEUR-113)Fixed a bug in promaxo's virtual keyboard  implementation in its sourcecode(i.e. fixing the touch screen keyboard issue)
- Finish building a preliminary version of neuro42 custom .iso that contains custom libraries like MongoDB that libUHD.
- Learning about software repository building process involving usage of pyInstaller and cMake, getting ready for tackling lower level issues.

## Week 3
- (NEUR-147) Integrate X300-reset script into CMake build file. Learnt about Cmake compilation pipeline along the way.
- (NEUR-149) Created a new .cpp executable that serializies a binary output from the X300-API, down-samples the input to a designated value, and de-serializes the samples back into a bianry file.
- Re-factored most instances of raw pointers in the SDR c++ code base, reducing gigabytes of memory leaks to zero. Making the SDR code memory-safe.


## Week 4
- Fix GUI asterisk bug where when viewing patient into, the asterisk (\*) shows up. Now the asterisk only shows up when adding a new patient.
- Learning QT framework as well as imgui integration into QT framework. Getting ready for GUI development

## Week 5
- Fix 4 bugs (NEUR 153, 152, 151, 157)
- Add "noise test" functionality to service module
- 
