[![Twitter: @NorowaretaGemu](https://img.shields.io/badge/X-@NorowaretaGemu-blue.svg?style=flat)](https://x.com/NorowaretaGemu)
  
  <br>
<div align="center">
  <a href="https://ko-fi.com/cursedentertainment">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi" style="width: 20%;"/>
  </a>
</div>
  <br>

<div align="center"> 
  <img alt="Unity" src="https://img.shields.io/badge/unity%20-%23323330.svg?&style=for-the-badge&logo=unity&logoColor=white"/>  
</div>
<div align="center">
  <img alt="C#" src="https://img.shields.io/badge/C%23-%23323330.svg?&style=for-the-badge&logo=csharp&logoColor=white"/> 
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-%23323330.svg?&style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
</div>
<div align="center">
  <img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-%23323330.svg?&style=for-the-badge&logo=powershell&logoColor=white"/>
  <img alt="Shell" src="https://img.shields.io/badge/Shell-%23323330.svg?&style=for-the-badge&logo=gnu-bash&logoColor=white"/>
  <img alt="Batch" src="https://img.shields.io/badge/Batch-%23323330.svg?&style=for-the-badge&logo=windows&logoColor=white"/>
  </div>
<br>

# Unity-CPP


https://sourceforge.net/projects/mingw/

### Make an EXE

```bash
g++ main.cpp -o main.exe
```

or Run: exemake.bat

### Make a DLL

```bash
g++ main.cpp -o main.dll
```

or Run: dllmake.bat

Run: runmain.bat

<br>

```bash
g++ -m64 -fpic -Wall -shared backend.cc -o backend.dll
```

<br>
https://www.msys2.org/
<br>

```bash
pacman -Syu
```

```bash
pacman -S mingw-w64-ucrt-x86_64-gcc
pacman -S mingw-w64-x86_64-toolchain
```

```bash
cl /LD backend.cpp /link /out:backend.dll
```

<br>
<div align="center">
© Cursed Entertainment
</div>
<br>
<div align="center">
<a href="https://cursed-entertainment.itch.io/" target="_blank">
    <img src="https://github.com/CursedPrograms/cursedentertainment/raw/main/images/logos/logo-wide-grey.png"
        alt="CursedEntertainment Logo" style="width:250px;">
</a>
</div>
