# nodejs_learning

## My very first NodeJS applications!

This document is about getting a NodeJS application environment ready and probably developing a NodeJS application on a Windows 10 PC.

### Development environment readiness process

I followed the [Microsoft tutorial here](https://learn.microsoft.com/tr-tr/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode).

Then I download the .msi package and installed by simply visiting [NodeJS web site](https://nodejs.org/tr), and select the LTS version.

I openned the file which have a name like node-v18.17.1-x64.msi and setup have started.

NodeJS runtime and npm package manager are selected as default to be installed.

There is a statement like some modules are going to be compiled from C/C++ source, and if I need them I should have Python and Visual Studio Build Tools installed. I do not really know whether I need them or not, because I do not want to add them manually, I decided to set up the Python and VS Build Tools.

I installed Python.

I could not find a C/C++ Build Tools, there are CMake Tools, Makefile tools, C# Build Tools but no other.

Meanwhile I noticed that I do not have a Visual Studio, I downloaded it and looked for C/C++ Build Tools as an option on setup, and selected C++ development for desktop as a Visual Studio setup option under Workloads. After that I had to give up the NodeJS setup and continue with only Visual Studio setup and I selected also NodeJS development option of Visual Studio installation's Workload setup.

I had to reinitiate the NodeJS setup. Also restarted PC and run a repair option of NodeJS setup.

And I managed to see NodeJS Application green button on my boot menu of Windows 10.

### First Application development process

When I redirected to a NodeJS very first tutorial on [here](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial) I realized that I should need Visual Studio Code beside. Thus I installed it.

And then followed and finished the very first NodeJS tutorial.

I write an app.js file ran and also debugged it.

Moreover, I developed an Express app through the tutorial.

Called http://localhost:3000/ using a browser and saw the result welcome page.

Thanks MicroSoft.
