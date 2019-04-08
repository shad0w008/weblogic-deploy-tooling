# Developer Guide

## Table of Contents
-[PreRequisite]
-[Project Structure]
-[Alias files]
-[typedefs files]
-[Building WebLogic Deploy Tool]

## Building WebLogic Deploy Tool

If you are making changes to the project, you can build the project by

  `mvn -Dunit-test-wlst-dir=<full path to the wlst.sh(cmd) directory> clean install`
  
This will build the entire project and run the unit test.

If you are not making changes and only interested in building the latest version, then you can 

  `mvn -Denforcer.skip -DskipTests clean install`
 
This will build the entire project without running any unit test.

