# JSUNFuck
The goal of this project is to deobfuscate JavaScript files that were proccessed with JSFuck (http://www.jsfuck.com)

# Test files
You can run the program with the provided test files or create your own using the jsfuck.js located @ https://github.com/aemkei/jsfuck/blob/master/jsfuck.js

_(NOTE: the jsfuck.js served by www.jsfuck.com is slightly different and I noticed this after I finished writing this tool, I will update it later to work with both versions)_ 

Here's the sample output you should expect from the provided test files ...
```
PS ..\JSUNFucker\JSUNFucker> .\bin\Release\JSUNFuck.exe '.\Test Files\AlertOne.ascii' testRes
PS ..\JSUNFucker\JSUNFucker> type .\testRes
return eval)()(alert("IT WORKS !!!");)
PS ..\JSUNFucker\JSUNFucker> .\bin\Release\JSUNFuck.exe '.\Test Files\SimpleText.ascii' testRes2
PS ..\JSUNFucker\JSUNFucker> type .\testRes2
THIS IS JUST SOME TEXT WITHOUT eval()
PS ..\JSUNFucker\JSUNFucker>
```
# License
Everything in this repository is licensed under MIT Open Source License and is free to use (without any warranty) and modify with proper attribution.


*TODO: Complete README.md, add LICENSE file, test the project with more JS files*
