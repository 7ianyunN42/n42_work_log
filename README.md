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
- Fix 7 bugs (NEUR 153, 152, 151, 157, 130, 159, 160)
- Add "noise test" functionality to service module
- Create a temperature monitor class that automatically terminates any ongoing scans when the thermalmeter's reading exceeds limit.

## Week 6
- Fix bug(NEUR 154)
- Rebuilt wheel for UI message box pop-up that allows for future-proof notification
- Complete temperature monitor module that sends count-down notifications to users on overheat
- Feature: atlas logger now communicates with the main process properly, which warns the user on log failure
- Feature: Service manual now contains a "desktop" button that grants service engineer desktop access
- Feature: all system and media shortcuts are now automatically removed on program start, meaning users can't ctrl+alt out of the program(unless in service mode)
- Help with documentation(drafting UML diagram) 

## Week 7
- Fix Progress bar(progressbar actually progresses during scan)
- Implement PLC's logic to constantly listen for temperature inputs(disabling PLC when temperature overheats)
- Build 0.0.6 version of Neuro42 custom ISO with new libraries and custom environments.
- Writing documentation for wireless internet adapter for the FDA approval

## Week 8
- Fix bugs NEUR-194
- Create tool for automatic versioning of resources onto google cloud services; integrated tool into jenkins
- Feature: display user manual and release notes on about software page
- Feature: disable tab switches during scanning
- Integrate software GUI as a system service, software now starts along with the system and creates an illusion that the GUI is the entirety of the system.

## Week 9
- Stress testing the software and fixing bugs coming out of it
- Documenting product versioning
