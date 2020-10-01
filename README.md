# multimediaManager

## INFO
Multimedia Manager is a node and electron based complete standalone application for the following functions-
* ### Deleting multiple images from as many folders you want.
      You can select as many folders as you want and then click on start deleting. It will scan 
      images from all the selected folders for images, add them to an array and match each array 
      with each other, for any difference( if not found then it will delete one if the image)
* ### Sorting images and videos
      You can again select as many folders as you want, select or create separate folders for  
      images and videos and then click on start sorting. It will 
      scan images from all the selected folders for images and videos, add them to an array and
      Sort them in separate selected folders.
## Pros
1. Very fast processing
2. Nice GUI(any other suggestion will be appreciated)
3. Easy to use
## Requirements
1. Node.js
note- below should be installed from cmd in the project firectory
2. `npm i electron --save-dev`
3. `nom i electron-builder --only=dev`
## How to Test
After installing dev dependencies mentioned above you can try on you console
`npm start`
Or for building  system installer
Try `npm run buildi`
And then install using the nsis installer so formed in the distance folder. After installing it will run.
