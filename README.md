# Visibilidade Web Application
"Visibilidade Quilombola" is a web-based application that emerged first place winner of GEO Indigenous Hack4Covid19 Hackathon that was held in the year 2020 at the height of COVID 19 pandemic. The web-mapping and data visualization tool solved the challenge that was submitted by Claudinete Cole de Souza - a leader of Quilombola community- who was seeking to develop an application that would allow the Quilombola community to tell a story of how COVID19 was affecting their lives. 

Visibilidade is a modified version adopted from the original https://github.com/JackDougherty/leaflet-storymap and has been customized with navigation bar and intuitive interface for a great user experience.

Members of team Visbilidade that built this tool included: Douglas Mbura  (Founder and Chief Technology Officer of Geo-Appsmith from Kenya)  and Rasha Elnimeiry, (Epidemiologist and GIS data specialist from Sudan). Visibilidade Quilombola was created to help the Indigenous Quilombola community in Brazil to become more visible by enabling the community to easily and quickly share their story of how Covid-19 was affecting their lives.

Quilombola are the descendants of Afro-Brazilian slaves who escaped from slave plantations that existed in Brazil until abolition in 1888. Due to geographic isolation, limitations to the access of the area in which they live in, and the lack of quality in the service when it is needed,these communities live in precarious health conditions.

## Web-App Components
## Key Features:
- Scroll-driven navigation, using screen swipe, trackpad, or keyboard down-arrow.

- Easy-to-learn template to create your own storymap. Upload text, point coordinates, zoom levels, and image links to a CSV generic spreadsheet.

- Images can be stored in local subfolder or pulled from an external URL.

- Works in modern browsers: Chrome, Firefox, Safari, Internet Explorer 9+.

This app has the following two parts/components:
## 1. STORYMAP 
- Which is enables the community to create beautiful digital scroll-based map narratives that can effect change, influence opinion, and create awareness.

And 
## 2.  MAP 
- Which provides a platform for the community to map and display important locations, sites, facilities, territories etc. using custom indigenous icons.


## Live links (replace with your own)
- [Follow this link to see Visibilidade Quilombola Live](https://douglasmbura.github.io/Visibility-Hackathon-WebApp)
- [Storymap Google Sheets Template](https://docs.google.com/spreadsheets/d/11VYnIz8YSabM5ZYOTRxm_RcDkle0GM5hScj22YyLnug/edit#gid=0)
- [Map Google Sheets template](https://docs.google.com/spreadsheets/d/1KQb2OiF1JI-UbHZ-EEXWbzAGYWVWe04ShtPjNJKvPxI/edit#gid=0)

## Step-by-Step Guide to Creating Your Own
## Requirements:
Before you begin, you must have the following: 

1. A [Github account](https://github.com/)

2. A [Google Drive account](https://drive.google.com/)

3. Make a Copy in Google Sheets of the [Storymap Template](https://docs.google.com/spreadsheets/d/11VYnIz8YSabM5ZYOTRxm_RcDkle0GM5hScj22YyLnug/edit#gid=0) 

4. Make a Copy in Google Sheets of the [Map Template](https://docs.google.com/spreadsheets/d/1KQb2OiF1JI-UbHZ-EEXWbzAGYWVWe04ShtPjNJKvPxI/edit#gid=0)

## 1. Creating Storymap

### A. Copy the GitHub template and publish your version with GitHub Pages.

Here's are the steps: 

1. Open the [GitHub code template](https://github.com/douglasmbura/Visibility-Hackathon-WebApp) in a new tab.
2. In the upper-right corner of the code template, sign in to your free GitHub account.
3. In the upper-right corner, click the green Use this template button to make a copy of the repository in your GitHub account. 
On the next screen, name your repo to ```visibility-hackathon-team-shiners``` or choose a different meaningful name in all lower-case. Click the Create repository from template button. Your copy of the repo will follow this format:```https://github.com/USERNAME/visibility-hackathon-team-shiners```
4. In your new copy of the code repo, click the upper-right Settings button and scroll way down to the GitHub Pages area. In the drop-down menu, change Source from None to Main, keep the default /(root) setting, and press Save as shown in Figure below. This step tells GitHub to publish a live version of your map on the public web, where anyone can access it in their browser, if they have the web address.
<img width="398" alt="leaflet-github-pages-main" src="https://user-images.githubusercontent.com/4737136/205280569-17167b5d-fd0a-4991-a820-6c43f33f60cd.png">

5. Scroll down to GitHub Pages section again, and copy the link to your published web site, which will appear in this format:```https://USERNAME.github.io/visibility-hackathon-team-shiners```
6. Scroll up to the top, and click on your repo name to go back to its main page.
7. At the top level of your repo main page, click on README.md, and click the pencil icon to edit this file.
8. Delete the link to the our live site, as shown in Figure below, and paste in the link to your published site. Scroll down to Commit your changes.
<img alt="leaflet-github-pages-main" src="https://user-images.githubusercontent.com/4737136/205361742-5a9db03c-4b28-40ba-a7dc-0baf66060e0a.png">

### B. File > Make a Copy of Google Sheet template, Share, and Publish.
Follow this steps:
1. Open the [Google Sheets Template](https://docs.google.com/spreadsheets/d/11VYnIz8YSabM5ZYOTRxm_RcDkle0GM5hScj22YyLnug/edit?pli=1#gid=0) in a new tab.
2. Sign into your Google account, and select File > Make a Copy to save your own version of this Google Sheet on your Google Drive.
3. Click the blue Share button, and click Change to anyone with the link, then click Done. This publicly shares your map data, which is required to make this template work.
4. Go to File > Publish to the Web, and click the green Publish button to publish the entire document, so that the Leaflet code can read it. Then click the upper-right X symbol to close this window.
5. At the top of your browser, copy your Google Sheet address or URL (which usually ends in ```...XYZ/edit#gid=0```), as shown in Figure below. Do NOT copy the Published to the web address (which usually ends in ```...XYZ/pubhtml```) because that link is slightly different and will not work in this template.
<img width="324" alt="sheets-publish-annotated" src="https://user-images.githubusercontent.com/4737136/205367487-9532af01-b451-47cb-a731-523d0b275dba.png">

### C. Paste your Google Sheet browser address in two places in your GitHub repo.
Our next task is to link your published Google Sheet to your Leaflet code in GitHub, so that it can pull your data from the Sheet to display on the map.
1. At the top of your GitHub repo, click to open the file named ```google-doc-url.js```, and click the pencil symbol to edit it.
2. Paste your Google Sheet address or URL (which usually ends in ```...XYZ/edit#gid=0)``` to replace our existing URL, as shown in Figure below. Be careful NOT to erase the single quotation marks or the semicolon at the end. Scroll down to Commit your changes. See separate instructions about the Google API key further below.

<img width="908" alt="google-doc-url" src="https://user-images.githubusercontent.com/4737136/205434304-30acade6-ddf1-4f07-9b10-47cfa21cdfd2.png">
3. Also, let???s paste your Google Sheet URL in second place to help you keep track of it. In your GitHub repo, click the README.md file to open it, click the pencil symbol to edit it, and paste your Google Sheet URL to replace our existing URL, as shown in Figure below. Scroll down to Commit your changes.
<img alt="google-doc-url" src="https://user-images.githubusercontent.com/4737136/205435284-11a77383-7858-4236-93cd-7e315ef44d68.png">

### D. Update your Google Sheet Options tab info and refresh your live map.
Now that your published Google Sheet is linked to your live map, go to the Options tab to update any of these items:
- Storymap Title
- Storymap Subtitle ??? with code for downward arrow: ```<br><small>Scroll down <i class='fa fa-chevron-down'></i></small>```
- Author Name
- Author Email or Website
- Author GitHub Repo Link

Open the browser tab that displays your live map and refresh the page to see your changes.

### E. Add text, media, markers, and geocode locations in the Google Sheet Chapters tab.
Now we can start to add new content to your map. In the Chapters tab of your Google Sheet, you???ll see column headers to organize and display interactive markers on your map. Replace the demonstration data with your own, but do not delete or rename the column headers, since the Leaflet code looks for these specific names.
- Chapter: The title appearing at the top of each section in the scrolling narrative.
- Media Link: You have several options to display either an image, audio, or video in each chapter. For images, you can insert an external link to an online service (such as Flickr), as long as it begins with ```https``` (secure) and ends with either ```.jpg```` or ```.png```. 
 
You can also insert a YouTube video embed link by following directions shown in the YouTube section of the template. Or you can upload an image file into the media subfolder in your GitHub repo, as shown in Figure below, and enter the pathname in the Google Sheet in this format: ```media/your-file-name.jpg``` or ...```png```. Similarly, you can upload an audio file in ```.mp3``` (recommended) or ```.ogg``` or ```.wav``` format.

<img width="648" alt="storymap-media-upload" src="https://user-images.githubusercontent.com/4737136/205437611-105826c4-81eb-4f68-baf9-c8c01d96faa1.png">

- Media Credit: To display text about the origin of the media, such as ???Source:??????.
- Media Credit Link: Add a direct link to the source info in the Media Credit text above.
- Description: Designed to display about a paragraph or less of text for the Chapter. You may insert HTML tags to add line breaks (such as ```<br>```), or to open external links in a new tab, such as ```<a href='https://www.w3schools.com/' target='_blank'>Visit W3Schools</a>```. Learn about HTML syntax at W3Schools.
- Zoom: Leaflet???s default zoom levels are between 0 (world view) to 18 (individual buildings), and most free basemap tiles, such as those provided by Stamen or CartoDB are available for each level in this range. There exist more detailed basemaps that allow you to use higher values. Experiment with zoom levels to get the best view for your story, and remember that given the same zoom level, larger screens will show larger areas compared to smaller screens, such as smartphones.
- Marker: You can insert four options: -```Numbered``` (auto-increment: 1, 2, 3, etc.) - ```Hidden``` (not visible, to avoid stacking markers on top of one another when multiple chapters focus on one location) - ```Plain``` (marker visible, but no label inside) - or customize by inserting any number, letter, or emoji. Works best when auto-increment does not display your desired output.
- Marker Color: Insert any standard web color name such as ```blue``` or ```green```, or insert a web color code such as ```#775307``` or ```rgba(200,100,0,0.5)```. See options at [W3Schools Color Names](https://www.w3schools.com/colors/colors_names.asp).
- Location, Latitude, Longitude: These place your markers at points on the map. Although the code template only requires ```Latitude``` and ```Longitude```, it???s wise to paste an address or place name into the Location column as a reminder to correspond with the numerical coordinates.

### F. Optional: Add georeferenced historical map image or GeoJSON overlays.
The code template allows you to enrich your story by placing two different types of layers on top of the background map: georeferenced map images (such as a historical map) and GeoJSON geodata (such as a pathway, boundary lines, or a color-coded choropleth map). You can add both types of layers to specific chapters or the entire story. Also, you can adjust the transparency level to reveal or hide the present-day background map. 
- Learn more about image and Geojson overlays [here](https://handsondataviz.org/transform.html)
### G. Save each Google Sheets tab as a CSV file and upload to GitHub.
If you have finished entering most of your data into your Google Sheets, downloading them into separate CSV files and uploading those into your GitHub repo is the best long-term preservation strategy. This approach keeps your map and data together in the same GitHub repo, and removes the risk that your map will break due to an interruption to Google services. Plus, you can still edit your map data. If this approach makes sense, follow these steps:
1. In your Google Sheets, go to each tab and select File > Download into CSV format, as shown in Figure below, to create a separate file for each tab.
<img width="491" alt="storymap-download-csv" src="https://user-images.githubusercontent.com/4737136/205439180-f6789fbd-570d-4a7b-9b21-faafa8ab0c05.png">
2. Shorten each file name as shown. The names must be exact. The first two files below are required, and others are optional.
- Chapters.csv
- Options.csv
- Notes.csv (or .txt) Recommended to keep any notes with your data, but not required.
4. In your GitHub repo, click the ```csv``` subfolder to open it, select Add file > Upload files, and upload all of the CSV files above into this subfolder, as shown in Figure below. The Leaflet template code checks here first for data, and if it finds CSV files with the names above, it will pull the map data directly from them, instead of your Google Sheets. Remember that from this point forward, any edits in your Google Sheet will no longer appear automatically in your map.
<img width="674" alt="storymap-upload-csv" src="https://user-images.githubusercontent.com/4737136/205439297-a5fa0328-a613-4f4b-868e-311ede2aacdb.png">
4. If you wish to edit your map after uploading your CSV files, you have two options. You can make small edits directly to your CSV files by opening them in the GitHub web interface. Or you can make larger edits in the Google Sheet, and repeating the steps above to download them in CSV format and upload them to replace your existing files on GitHub.

## 2. Creating the Map
Please note that the files supporting the Map are located inside the ```map``` folder of your GitHub repo. See figure below.
<img alt="storymap-download-csv" src="https://user-images.githubusercontent.com/4737136/205481544-79fdf78b-4064-42a1-b42c-06b3619cc018.png">


### A. File > Make a Copy of Google Sheet template, Share, and Publish.
- Follow the exact same steps as the Google Sheet Storymap template.
### B. Paste your Google Sheet browser address in two places in your GitHub repo.
Our next task is to link your published Google Sheet to your Leaflet code in GitHub, so that it can pull your data from the Sheet to display on the map.
1. At the top of your GitHub repo, click to open the ```map``` folder and then open file named ```google-doc-url.js```, and click the pencil symbol to edit it.
2. Paste your Google Sheet address or URL (which usually ends in ````...XYZ/edit#gid=0````) to replace our existing URL, as shown in Figure below. Be careful NOT to erase the single quotation marks or the semicolon at the end. Scroll down to Commit your changes.
<img width="908" alt="google-doc-url (1)" src="https://user-images.githubusercontent.com/4737136/205481132-9144428e-c0a7-43dd-bd62-73ba7a9ac681.png">

3. Also, let???s paste your Google Sheet URL in second place to help you keep track of it. In your GitHub repo, click the README.md file to open it, click the pencil symbol to edit it, and paste your Google Sheet URL to replace our existing URL, as shown in Figure below. Scroll down to Commit your changes.

<img alt="storymap-download-csv" src="https://user-images.githubusercontent.com/4737136/205482257-40a59278-c015-4d27-aa45-9b53b1c4b62c.png">

### C. Update your Google Sheet Options tab info and refresh your live map.
Now that your published Google Sheet is linked to your live map, go to the Options tab to update any of these items:

- Map Title
- Map Subtitle
- Author Name
- Author Email or Website
- Author Code Repo
Open the browser tab that displays your live map and refresh the page to see your changes.

### D. Geocode locations and customize new markers in the Points tab.
Now we can start to add new content to your map. In the Points tab of your Google Sheet, you???ll see column headers to organize and display interactive markers on your map. Replace the demonstration data with your own, but do not delete or rename the column headers, since the Leaflet code looks for these specific names.

- Group: Create any labels to categorize groups of markers in your legend.
- Marker Icon: Insert a Font Awesome free and solid icon name such as ```fa-ice-cream``` or ```fa-coffee```, or any Material Design icon name such as ```rowing``` or ```where_to_vote```. You can also use custom indigenous icons such ```fc_bird```, ```fc_canoe```, ```fc_spear_fishing``` etc. or create and use your own custom icons. 

The next set of columns include items that appear when users click on point markers: 
- Name: Add a title to display in the marker pop-up window.
- Description: Add text to appear in the marker pop-up window. You may insert HTML tags to add line breaks (such as ```<br>```), or to open external links in a new tab, such as ```<a href='https://www.w3schools.com/' target='_blank'>Visit W3Schools</a>```. Learn about HTML syntax at [W3Schools](https://www.w3schools.com/html/html_links.asp).
- Image: You have two options to display images. You can insert an external link to an image hosted by an online service (such as Flickr), as long as it begins with ```https``` (secure) and ends with either ```.jpg``` or ```.png```. Or you can upload an image into the ```media``` subfolder inside your ```map``` folder in GitHub repo, and enter the pathname in the Google Sheet in this format: ```media/image.jpg``` or ```...png```.
- Location, Latitude, Longitude: These place your markers at points on the map. Although the code template only requires Latitude and Longitude, it???s wise to paste an address or place name into the Location column as a reminder to correspond with the numerical coordinates. 

### E. Remove or display point, polygon, or polylines data and legends.
By default, the demo map displays three types of data???points, polygons, and polylines???and their legends. You can remove any of these from your map by modifying your linked Google Sheet:
To remove points:
- In the Options tab, set Point Legend Position (cell B27) to Off to hide it.
- In the Points tab, delete all rows of point data.
To remove polylines:
- In the Options tab, set Polyline Legend Position (cell B36) to Off to hide it.
- In the Polylines tab, delete all rows of polyline data.

To remove polygons:
- In the Polygons tab, set Polygon Legend Position (cell B4) to Off to hide it.
- Also in the Polygons tab, set Polygon GeoJSON URL (cell B6) to remove that data from your map.
- In the next tab Polygons1, use the tab drop-down menu to select Delete to remove the entire sheet.

After you???ve prepared your GeoJSON data, name the files using all lower-case characters and no spaces, and upload them into the ```geojson``` subfolder inside the ```map``` folder of your GitHub repo. Then update these settings in your linked Google Sheet:
To display polylines:
- In the Options tab, make sure Polyline Legend Position (cell B36) is visible by selecting topleft or a similar position.
- In the Polylines tab, enter the GeoJSON URL pathname to the file you uploaded to your GitHub repo, such as ```geodata/polylines.geojson```. Then insert a Display Name, Description, and Color.

To display polygons:
- In the Polygons tab, make sure Polygon Legend Position (cell B4) is visible by selecting topleft or a similar position.
- In Polygon GeoJSON URL (cell B6) enter the pathname to the file you uploaded to your GitHub repo, such as ```geodata/polygons.geojson```.
- You can change the Polygon Legend Title (cell B3) and add an optional Polygon Legend Icon (cell B5).
- Edit the Polygon Data and Color Settings sections to modify the labels and ranges to align with the properties of your GeoJSON file. In the Property Range Color Palette, you can automatically select a color scheme from the ColorBrewer tool, or manually insert colors of your choice in the cell below.
- Read the Hints column in the Polygons sheet for tips on how to enter data.
- If you wish to display multiple polygon layers, use the Polygons tab drop-down menu to Duplicate the sheet, and name additional sheets in this format: Polygons1, Polygons2, etc.
#### F. Save each Google Sheets tab as a CSV file and upload to GitHub.
If you have finished entering most of your data into your Google Sheets, downloading them into separate CSV files and uploading those into your GitHub repo is the best long-term preservation strategy. This approach keeps your map and data together in the same GitHub repo, and removes the risk that your map will break due to an interruption to Google services. Plus, you can still edit your map data. If this approach makes sense, follow these steps:
1. In your Google Sheets, go to each tab and select File > Download into CSV format, as shown in Figure below, to create a separate file for each tab.
<img width="455" alt="sheets-download-csv" src="https://user-images.githubusercontent.com/4737136/205484637-0b93ebfa-e0fb-4a5d-8648-89073b50218b.png">
2. Shorten each file name as shown. The names must be exact. Only the first file below (Options.csv) is required, and others are optional, depending on your data.
- Options.csv
- Points.csv
- Polylines.csv
- Polygons.csv (If additional files, name them: Polygons1.csv, Polygons2.csv, etc.)
- Notes.csv (or .txt) Recommended to keep any notes with your data, but not required.

3. In your GitHub repo, click the ```map```` > then ```csv``` subfolder to open it, select Add file > Upload files, and upload all of the CSV files above into this subfolder as shown in Figure below. 
The Leaflet template code checks here first for data, and if it finds CSV files with the names above, it will pull the map data directly from them, instead of your Google Sheets. Remember that from this point forward, any edits in your Google Sheet will no longer appear automatically in your map.

<img width="656" alt="leaflet-upload-csv" src="https://user-images.githubusercontent.com/4737136/205484812-88dc1977-0349-41c0-b839-a6d4e3d44b12.png">
4. If you wish to edit your map after uploading your CSV files, you have two options. You can make small edits directly to your CSV files by opening them in the GitHub web interface. Or you can make larger edits in the Google Sheet, and repeating the steps above to download them in CSV format and upload them to replace your existing files on GitHub.


## Credits (and licenses)
Adopted from code developed by [Ilya Ilyankou](https://github.com/ilyankou) and [Jack Dougherty](https://github.com/jackdougherty) with support from Connecticut Humanities and Trinity College, CT. Inspired by Code for Atlanta mapsfor.us (2016) https://github.com/codeforatlanta/mapsforus (BSD-3-Clause). Adapted from MUX Lab, Map Effects 100: https://github.com/muxlab/map-effects-100, see http://muxlab.github.io/map-effects-100/Leaflet/11_scroll-driven-map-navigation.html.

We use [Google Sheets API version 4](https://developers.google.com/sheets/api), with these open-source components:

- Leaflet v1.7.1 https://leafletjs.com (BSD-2-Clause)
- jQuery v3.5.1 https://code.jquery.com (MIT)
- PapaParse v5.3.0 to parse CSV with JavaScript (MIT)
- Font Awesome v5.8.1 https://cdn.fontawesome.com (MIT, SIL OFL 1.1)
- leaflet-providers (v1.10.2) https://github.com/leaflet-extras/leaflet-providers (BSD-2-Clause)
- Leaflet.awesome-markers (v2.0.4), manually updated to svg to allow hex and material icons https://github.com/sigma-geosistemas/Leaflet.awesome-markers (MIT)
- Leaflet.ExtraMarkers (v1.0.5) https://github.com/coryasilva/Leaflet.ExtraMarkers (MIT)
- jQuery-CSV (v1.0.11) https://github.com/evanplaice/jquery-csv (MIT)
- Single Element CSS Spinner (31 May 2016) https://github.com/lukehaas/css-loaders (MIT)
- Lightbox by Lokesh Dhakar (v.2.11.3) https://github.com/lokesh/lightbox2 (MIT)
