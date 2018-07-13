# Library-Biomass-Cohort

Changes to this extension are governed by the [**Repository Rules**](https://sites.google.com/site/landismodel/developers) from the Technical Advisory Committee (TAC).  The TAC is the Maintainer of this repository.<br>

<br>

## About
**Project:** LANDIS-II Landscape Change Model<br> 
**Author:**	LANDIS-II Foundation<br>
**Assembly Name:** Landis.Library.BiomassCohorts-v3.dll<br>
**Assembly Version:** 3.0<br>
**Assembly URL:** <https://github.com/LANDIS-II-Foundation/Support-Library-Dlls-v7><br>
**Assembly Release Date:** July 2018<br>
**LANDIS-II Core Version:** 7.0

### Notes:
* .NET Standard 2.0 update
* Replacing _Edu.Wisc.Forest.Flel.Util_ with _Landis.Utilities_
* LANDIS-II Core libraries are available on [MyGet landis-ii-v7 feed](https://www.myget.org/feed/Packages/landis-ii-v7). The *__NuGet.Config__* file should configure necessary LANDIS-II Core libraries as long as the file is stored in the same level as `.csproj_ file`.
* A new pre-build file *__support_libs_download.ps1__* (PowerShell script) is added in `/src/lib` folder. Runing the file will download dependencies from [LANDIS-II support library dlls](https://github.com/LANDIS-II-Foundation/Support-Library-Dlls-v7) repository. Some libraries don't have LANDIS-II support library dependencies.  In that case, there is no _/src/lib_ folder in the project file.
* Use of [**Gdal.Core** NuGet package](https://www.nuget.org/packages/Gdal.Core).

<br>

## LANDI-II-v7 Release Notes
* .NET Core 2.0
* Gdal.Core works on Windows 10. Older Windows OS users can't use LANDIS-II-v7 instead use LANDIS-II version 6.2.

### LANDIS-II-v7 OS Support
* Windows 10 (x64)
* Linux (x64) and Mac OS 10.12+ (x64) - We didn't compiled for Linux and Mac OS. However, it should be possible to compile LANDIS-II-v7 application. It may require some workaround.


<br>

## Getting Started on Windows 10
_Instruction link may be here?_

