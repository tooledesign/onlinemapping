# Online Mapping How-To

1) Set up new repository on github with your project name (https://github.com/organizations/tooledesign/repositories/new)
2) Create mapbox basemap style (https://www.mapbox.com/studio/). You may need to upload layers...
3) Develop surveygizmo survey with hidden id question. You can copy the surveygizmo survey here to start (https://app.surveygizmo.com/builder/build/id/4409855)
4) Finalize proposed facility geojson file. Include the surveygizmo url with the segment's id as one of the attributes
5) Upload the geojson to your github repository.
6) Customize the index.html code to fit your formatting/title/color coding,etc.
  6.1) Update the map location to your mapbox style and lat/lon/zoom level (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L193)
  6.2) Replace the proposed facility geojson link in the index.html with the one you uploaded in Step 5 (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L205). 
  6.3) Change facility names/hex codes to reflect your project, both where (https://github.com/tooledesign/onlinemapping/blob/5636ad6f0cfd9d7feb68c5e010d0a400e85470a5/index.html#L228)
7) Upload appropriate logo and legend to the github repository and change the index.html code to reflect these additions.
