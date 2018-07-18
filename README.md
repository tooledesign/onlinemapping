# Online Mapping How-To

1) Set up new repository on github with your project name (https://github.com/organizations/tooledesign/repositories/new)
2) Create a file named index.html in this repository. 
3) Copy the index.html text from the onlinemapping repository (https://raw.githubusercontent.com/tooledesign/onlinemapping/master/index.html) into your index.html file and Commit Changes at the bottom.
Under the Settings tab, scroll to GitHub Pages and under Source, change "none" to "master" and press "Save". The web address for your hosted map is at the end of the "Your site is ready to be published at" sentence above the "Save" button. 
2) Create mapbox basemap style (https://www.mapbox.com/studio/). If you would like to represent existing facilities on this basemap, upload them as a tileset and style them. If you are unsure how to use mapbox, consult with Rohan, Kyle, or other Toole Design experts. 
3) After publishing the style, replace the style URL in the index.html here (https://github.com/tooledesign/onlinemapping/blob/970000f174dbcc11b012d2ddb099b364e0d8fcf4/index.html#L195) with your own(e.g. mapbox://styles/tooledesign1/cji99oiov6yah2rpreel7y8my). On subsequent lines, adjust the center of the map (lat/long) and the initial map zoom level. 
4) At this point, commit the changes in ou
3) Develop surveygizmo survey with hidden id question. You can copy the surveygizmo survey here to start (https://app.surveygizmo.com/builder/build/id/4409855)
4) Finalize proposed facility geojson file. Include the surveygizmo url with the segment's id as one of the attributes
5) Upload the geojson to your github repository.
6) Customize the index.html code to fit your formatting/title/color coding,etc.
  6.1) Update the map location to your mapbox style and lat/lon/zoom level (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L193)
  6.2) Replace the proposed facility geojson link in the index.html with the one you uploaded in Step 5 (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L205). 
  6.3) Change facility names/hex codes to reflect your project, both where (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L228)
7) Upload appropriate logo and legend to the github repository and change the index.html code to reflect these additions.
