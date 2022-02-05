Setting up macOs Big Sur
#### Open and Use terminal
The Mac Terminal is a command line system that can help you quickly take control of your operating system and make changes. 
After typing in each command, you’ll have to hit the return button for the command to take hold.
1. Spotlight - Search "terminal"
2. Launchpad - Search "terminal"

Few useful commands to know:

  Open an application
  ```
  Open -a APPLICATION / Open -a “APPLICATION NAME”
  Open -a SPOTIFY)
  ```
 Open a file using the default application
  ```
  Open [FILE PATHWAY]
  ```
  Open a file using an application you specify:
  Open -a “APP NAME” [FILE PATHWAY]
  ```
  Open a text-based file using the text editor:
  ```
  Open -a Text Edit [FILE PATHWAY]
  ```
#### Install the JDK on macOS
Check if the java is already installed on the computer.
```
java -version
```

 To install the Java development kit on MacOS, you need to 
 1. download the appropriate archive file, jdk.java.net/archive/
 2. extract it and 
 3. then copy the files to the appropriate location.
 or 
 1. instal homebrew https://phoenixnap.com/kb/install-homebrew-on-mac
 2. Disable the analytic data collection 
 ```
            brew analytics off
 ```
 3. check the analytic data collection status
  ```
           brew analytics
 ```
 Analytics are disabled
 4. install java https://mkyong.com/java/how-to-install-java-on-mac-osx/
    `` 
    brew search java
    brew info java11
    brew instal java11
    ```
    Homebrew installed the JDK files and directories at /usr/local/Cellar/openjdk/, and symbolic link at /usr/local/opt/openjdk@11 points to  Java 11 version.

    also check this 
    https://mkyong.com/java/how-to-set-java_home-environment-variable-on-mac-os-x/