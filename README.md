# Password-Store
Saves your password in two Encrypted files.<br>
Added Support to AES-256 bit Encryption.<br>
``` git clone https://github.com/garvit-joshi/Password-Store.git ```

## Prerequisite (for only building app from source):
1. [Python 3 (>=3.8.5)](https://www.python.org/)
2. [Visual Studio 2019](https://visualstudio.microsoft.com/vs/)

## Building the app from source.

Although Everything is compiled and you can directly run [Main.exe](https://github.com/garvit-joshi/Password-Store/tree/master/bin64). Here are steps for building app from source.

1. Install Python3 with Environment Path. [click here](https://www.python.org/)
2. Install a C++ Compiler (Copiler Used In this project: [Microsoft C++ Compiler-MSVC](https://visualstudio.microsoft.com/downloads/))
3. Open cmd in folder and type <br>
3.1. ```cython Encryption.py --embed```  
3.2. ```cython Decryption.py --embed```
4. The above step will create ```Encryption.c``` and ```Decryption.c```.
5. Build ```Encryption.c``` , ```Decryption.c``` and ```Main.cpp```.
6. Run [Main.exe](https://github.com/garvit-joshi/Password-Store/tree/master/bin64)

### Support (for only building app from source):

1. For Downloading Python, [click here](https://www.python.org/) <br>
Note : Please click on 'Add Python 3.xx to PATH' while installing. <br>
2. Install Required Modules: <br>
2.1. Open command prompt. <br>
2.2. Run ```pip install pyAesCrypt```

### Caution:
The last thing is simply a matter of perception. If you are running any sort of anti-virus, like ZoneAlarm, Norton, McAfee, etc. then they will get a very unpleasant message about your program trying to do something considered dangerous. It may be due to system(); function used in program. Read more about it [here](http://www.cplusplus.com/reference/cstdlib/system/), and [here](http://www.cplusplus.com/articles/j3wTURfi/)
