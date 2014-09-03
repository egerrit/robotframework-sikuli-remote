# Sikuli Remote Server

Sikuli Remote Server is a Java-based [Remote Server](https://code.google.com/p/robotframework/wiki/RemoteLibrary) for [Robot Framework](http://robotframework.org/).

Sikuli Remote Server provides keywords for GUI Testing.  

Sikuli Remote Server is based on [Sikuli Script Java library](http://www.sikuli.org/).

## Prerequisites

1. Install [Sikuli Script](https://launchpad.net/sikuli/+download)
2. Download [javalib-core-1.2.jar](http://search.maven.org/remotecontent?filepath=org/robotframework/javalib-core/1.2/javalib-core-1.2.jar)
3. Download [xmlrpc-1.1.1.jar](http://sourceforge.net/projects/xmlrpc/files/%28New%29%20Redstone/1.1.1/redstone-xmlrpc-1.1.1.zip/download)
4. Download [simple-4.0.1.jar,simple-xmlrpc-1.0.jar](http://sourceforge.net/projects/xmlrpc/files/Simple%20%2B%20XML-RPC/1.0/redstone-simple-xmlrpc-1.0.zip/download)

## Usage

1. Set SIKULIX_HOME 
  *SET SIKULIX_HOME=C:\SikuliX\

2. Add %SIKULIX_HOME%\libs\ to the PATH 
  *SET PATH=C:\SikuliX\libs\;%PATH%

3. Add all of the pre-built JAR to the CLASSPATH 
  *SET CLASSPATH=C:\MyClasses\SikuliRemoteServer.jar;C:\MyClasses\sikuli-script.jar;C:\MyClasses\simple-4.0.1.jar;C:\MyClasses\xmlrpc-1.1.1.jar;C:\MyClasses\simple-xmlrpc-1.0.jar;C:\MyClasses\javalib-core-1.2.jar;%CLASSPATH%

4. Start Sikuli Remote Server
  *java -classpath C:\MyClasses\*.jar SikuliRemoteServer