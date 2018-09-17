## how to use
 1. download chatito
```
npm install -g chatito
```

 2. create a definition file (e.g.: trainClimateBot.chatito) with your code

 3. run the npm generator
```
npx chatito <pathToFileOrDirectory> --format=<format> --formatOptions=<formatOptions> --outputPath=<outputPath>
```

 - <pathToFileOrDirectory> path to a .chatito file or a directory that contains chatito files. If it is a directory, will search recursively for all *.chatito files inside and use them to generate the dataset. e.g.: lightsChange.chatito or ./chatitoFilesFolder
 - <format> Optional. default, rasa or snips
 - <formatOptions> Optional. Path to a .json file that each adapter optionally can use
 - <outputPath> Optional. The directory where to save the generated dataset. Uses the current directory as default.

 4. document
https://rodrigopivi.github.io/Chatito/
