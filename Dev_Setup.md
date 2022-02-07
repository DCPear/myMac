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
  ```
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
    ```
    brew search java
    brew info java11
    brew instal java11
    ```
    Homebrew installed the JDK files and directories at /usr/local/Cellar/openjdk/, and symbolic link at /usr/local/opt/openjdk@11 points to  Java 11 version.

    also check this 
    https://mkyong.com/java/how-to-set-java_home-environment-variable-on-mac-os-x/ </br>
    https://www.macworld.co.uk/how-to/learn-set-up-java-programming-environment-in-os-x-3636924/

5. Install Intellij idea community edition
  ```
    brew install --cask intellij-idea-ce
  ```
  issues/resolutuion

  test idea
  ```
  terminal > jshell
  exit jshell /exit
  ```

  6. Git 
  if it was already installed 
  ```
  git --version 
  brew install git
  git config --global user.email "yourGitHub@email.com"
  git config --global user.name "yourGitHubusername"
  ```
  7. How to see all drives on my Mac
Activate the Finder app. Go to the Apple menu bar and click on Preferences. Click on the Sidebar tab. Under the Locations section, enable “Hard disks,” “External disks,” “CDs, DVDs, and iOS devices” in order to see all drives on Mac.

If the sidebar does not appear in the left pane, enable it by pressing Option + Command + S keys while Finder is active.

If you prefer to see all drives on the Desktop, enable the above options in Finder -> Preferences -> General tab.

8. visual studio code

```
brew install --cask visual-studio-code
```

https://formulae.brew.sh/cask/visual-studio-code
https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line
https://sourabhbajaj.com/mac-setup/VisualStudioCode/
https://www.codegrepper.com/code-examples/whatever/brew+install+vscode

9. Maven
```
brew install maven
mvn -v
```
https://formulae.brew.sh/formula/maven
https://www.appsdeveloperblog.com/how-to-install-maven-on-mac-os/

