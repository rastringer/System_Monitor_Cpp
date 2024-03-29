# System_Monitor_Cpp

<img src="example1_system_monitor.PNG" width="500" height="500" />

This program monitors Linux system processes and resource usage, similar to htop on Linux.

## To setup and compile on Ubuntu:

1. Clone repository into `/home/workspace/`
```
cd /home/workspace/
git clone https://github.com/rastringer/System_Monitor_Cpp
```
2. Follow along with the lesson and make sure you complete the `ProcessParser` and `Process` classes before attempting to run the project.

3. Install `ncurses` package
```
sudo apt-get install libncurses5-dev libncursesw5-dev
```
4. Compile and run
```
g++ -std="c++17" main.cpp -lncurses
./a.out
```
5. In case of error that looks like the following: 
```
root@77e30fca8a01:/home/workspace/CppND-Object-Oriented# ./a.out
*** %n in writable segment detected ***
                                      Aborted (core dumped)
```
just keep trying `./a.out` and it should work eventually!
