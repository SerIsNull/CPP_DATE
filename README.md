/*! \mainpage This is parser for getting all the necessary types and their tags from pic.XEM
- \subpage How to use it?
- \ref groupExample "Example of using"
*/
/**
\defgroup groupExample This sections shows how to use it.
- First of all you need to put two input files into the project derectory. The first file describes all compoistes and tags in the picture of SCADA, the second file describes the composites that need to be obtained from the picture of the SCADA.
- After that, you need to create the directory for building. In the project root-directory you need to use cmd: mkdir build.
- For generating some files for building you need to run the cmd like cmake .. in the /build directory.
- After that Cmake will check the availability of the necessary programms such as g++, prep and awk and something else.
- After that you'll take all the necessary files for building project.
- For build project, you need run cmd like cmake --build . in the /build directory.
- After that CMake will start building the project.
- It'll generate new filtered files.XEM for faster parsing.
- After building the CMake makes the test running of the parser with new filtered file.XEM and file.txt.txt with composites.
- The result of the buildding and the test running you can see in the output.
- The result file if parsing will be save in /build directory like "result.txt"
*/
