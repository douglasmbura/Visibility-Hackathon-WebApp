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
5. Scroll down to GitHub Pages section again, and copy the link to your published web site, which will appear in this format: ```https://USERNAME.github.io/visibility-hackathon-team-shiners```
6. Scroll up to the top, and click on your repo name to go back to its main page.
7. At the top level of your repo main page, click on README.md, and click the pencil icon to edit this file.
8. Delete the link to the our live site, as shown in Figure below, and paste in the link to your published site. Scroll down to Commit your changes.

B. File > Make a Copy of Google Sheet template, Share, and Publish.

C. Paste your Google Sheet browser address in two places in your GitHub repo.

D. Update your Google Sheet Options tab info and refresh your live map.

E. Add text, media, markers, and geocode locations in the Google Sheet Chapters tab.

F. Optional: Add georeferenced historical map image or GeoJSON overlays.

G. Save each Google Sheets tab as a CSV file and upload to GitHub.

See more in the tutorial https://handsondataviz.org/leaflet-storymaps-with-google-sheets.html

## 2. Creating the Map

A. Copy the [GitHub template](https://github.com/douglasmbura/Visibility-Hackathon-WebApp) and publish your version with GitHub Pages.

B. File > Make a Copy of Google Sheet template, Share, and Publish.

C. Paste your Google Sheet browser address in two places in your GitHub repo.

D. Update your Google Sheet Options tab info and refresh your live map.

E. Geocode locations and customize new markers in the Points tab.

F. Remove or display point, polygon, or polylines data and legends.

G. Save each Google Sheets tab as a CSV file and upload to GitHub.

See more in the tutorial https://handsondataviz.org/leaflet-maps-with-google-sheets.html

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
