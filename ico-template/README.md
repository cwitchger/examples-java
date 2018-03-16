# ICO Template
To run this ICO Template, you must first setup [neo-devpack-java](https://github.com/neo-project/neo-devpack-java) and install the artifact to your local maven .m2 folder as well as your system's dotnet folder.

**NOTE**
There is a pull request in for a modification to neo-devpack-java that is required for running this ICO Template. Please make sure the Runtime class is updated with the following:
```java
@Syscall("Neo.Runtime.GetTime")
public native static long time();
```


## Additional Resources
### Promotion process
**Mac OS**

There is a bash script file called *promote.sh* that simplifies compiling the template but makes some assumptions on the location of the neo-compiler and neo-python projects.
