# Simple Injector
A really simple injector which downloads the needed file from a link and injects into the target process name.

# How To Use
1. Create a new project in Visual Studio.
2. Create as a c++ console program.
3. Go to the single .cpp file and paste the main.cpp in.
4. Change the following code to your liking.
```cpp
LPCTSTR url = L"myurl.com";
LPCTSTR dllPath = L"C:\\Temp\\MyDLL.dll";
LPCTSTR targetProcess = L"demo.exe";
```
5. Compile in debug or release.
