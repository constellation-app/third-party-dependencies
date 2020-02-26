# Third Party Dependencies
A temporary repository of 3rd party dependencies until they are available in Maven.

## unfolding-master-20171010.jar
Unfolding was taken from [tillnagel/unfolding](https://github.com/tillnagel/unfolding) 
and this specific version is required to support JOGL 2.3.2.

## JOGL 2.4.0
Contains Gluegen, JOCL, JOGL, Nativewindow and Newt libraries taken from the current master build on [jogamp.](https://jogamp.org/deployment/archive/rc/v2.4.0-rc-20200202/) This specific version is required to handle JDK11 and NB11 migration.

## Processing 4.0
Contains `Core.jar` from the current release on [github.](https://github.com/processing/processing4/tree/processing-1270-4.0a1/core/library)

For more information see the [attribution list](https://github.com/constellation-app/constellation/blob/master/ATTRIBUTION.md).

## NetBeans Java Help Module
Since NetBeans's migration to Apache, support for some very old libraries have been dropped. Unfortunatley, we still require `org-netbeans-modules-javahelp.jar` .

## More Information
This repository should follow everything mentioned in the Constellation 
[README](https://github.com/constellation-app/constellation/blob/master/README.md).
