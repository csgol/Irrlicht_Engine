# Running Irrlicht

---

### In this ReadMe we will go over how to run Irrlicht in Visual Studio.

### Start the following playlist: https://www.youtube.com/watch?v=KTNloEvRsfw

### Pour yourself a fine brew, get comfy, and lets get started! 

---

### First thing is first, you will need to download Irrlicht from the following SDK 1.8.5 and unzip it, or clone the repository to your machine: https://irrlicht.sourceforge.io/?page_id=10

### Next, we will install Visual Studio 2022, this IDE is best for large projects in C++: https://visualstudio.microsoft.com/vs/features/cplusplus/ 

### Once installed you can open the Irrlicht folder in Visual Studio.

### You can ignore CMakeList.txt popup when first opening the project by selecting "Do not enable".

<br/>
<img src="/img/CMake.png" alt="irrlicht">
<br/>

### This is the complete Irrlicht source project.

<br/>
<img src="/img/irrlicht.png" alt="irrlicht">
<br/>

---

### Now Create a new project by navigating to the Irrlicht folder on your machine: 
*C:\Users\<username>\Documents\GameDev\irrlicht-1.8.5\irrlicht-1.8.5\examples\01.HelloWorld\HelloWorld_vc12.vcxproj*

### Right click on "HelloWorld_vc12.vcxproj" and open it in Visual Studio 2022. This is the Hello World example file we will run to make sure that irrlicht is working on your machine. 

<br/>
<img src="/img/new-project.png" alt="irrlicht">
<br/>

### Once the file is open in Visual Studio it should look like this:

<img src="/img/helloworld.png" alt="irrlicht">

---

### For running the project select "Build" and then "Build 01.HelloWorld" from the top options.

<br/>
<img src="/img/build.png" alt="irrlicht">
<br/>

### After the project successfully builds, then go to the "Debug" option and select "Start Without Debugging"

<br/>
<img src="/img/start.png" alt="irrlicht">
<br/>

### If you encounter an error in the Debug mentioning Windows 7 follow these steps:
- Right click the root directory go to properties and change the Platform Toolset to *Visual Studio 2022 (v143)*

<br/>
<img src="/img/platform.png" alt="irrlicht">
<br/>

### After the changes restart Visual Studio and build and start the project and you should see the following arcane sprite!

<br/>
<img src="/img/first-compile.png" alt="irrlicht">
<br/>

---

# Pour yourself another and lets begin this journey into the dungeons!!!! 
  
 ---                                     # Irrlicht_Engine
