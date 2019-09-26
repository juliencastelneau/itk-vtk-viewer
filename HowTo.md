# The main goal of this fork is to display 2 itk images in web viewer
---

## Build: 

1. Clone the repo (remote`:git@github.com:juliencastelneau/itk-vtk-viewer.git`)
2. open terminal and :  

> `npm run-script build:debug` 

## Run:

1. ./bin/itk-vtk-viewer-cli.js -s path/to/your/{{MUSIC_db}}
2. Open your browser and :

> `http://localhost:3000/?fileToLoad=/data/{{MUSIC_db}}/path_to_your_1st_image/image1.mha&maskToLoad=/data/MUSIC/path_to_your_2nd_image/image2.mha`  

