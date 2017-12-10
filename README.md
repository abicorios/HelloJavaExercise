# HelloJavaExercise
It is my exercise.
# Dependence
**Windows**
1. Install Chocolatey package manager https://chocolatey.org/
2. For install JDK9 and Git, run in the PowerShell
```
choco install jdk9 git
```
**Android**
1. The Android device which can run Termux;
2. The Hacker's Keyboard https://play.google.com/store/apps/details?id=org.pocketworkstation.pckeyboard have the additional keys  (Ctr, Alt, Esc, etc) like on the keyboard for the desktop. But you must set it from 3 to 5 rows. You can want to stop some console programm by the Ctrl+C, so install this full keyboard before using Ping, for example.
3. The Termux from the GooglePlay https://play.google.com/store/apps/details?id=com.termux is the powerfull command line;
4. The TermuxArch https://wiki.termux.com/wiki/Arch is the full extensible operation system with the package manager and now (end of 2017 year) it is one working Linux distributive which can be installed without big errors by PRoot in Termux. Also TermuxArch produce less errors than pure Termux along using like on the usual Linux. And it is better for your to confirm the adding of the startarch script in your path at the end of the installing of the TermuxArch;
5. For install JDK9 and Git, in TermuxArch run
```
pacman -S jdk9-openjdk git
```
# Compiling and run
**Windows**

Make it in the PowerShell
```
git clone https://github.com/abicorios/HelloJavaExercise
cd HelloJavaExercise
javac hello.java
java hello
```
**Android**

For go in the TermuxArch run **startarch** command from Termux terminal.
Make it in the TermuxArch
```
git clone https://github.com/abicorios/HelloJavaExercise
cd HelloJavaExercise
javac hello.java
java hello
```
