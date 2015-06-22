##MaptimePDX 2015-05-14

#Cartographic Design
##By Alexa Todd

Google Drive link: [http://bit.ly/1H65bAQ][1]

###Before you start
 1. What is the purpose of your map?
 2. Who is your audience?
 3. Know your data.
    1. What is the source? Content?
    2. What attributes are included? How are they defined?

###Classification – data is usually put into some categories or groups before 
it can be displayed
 1. Categorical: types of the feature based on attributes
 2. Numerical: measured values (ex., low to high)

###Color
 1. Characteristics
    1. Hue – the color or shade
    2. Saturation – Saturation describes the vividness of color. Variations in 
       saturation appear as a change from gray to a rich color where each step 
       has the same lightness. There are generally fewer distinct steps in a 
       saturation ramp.
    3. Lightness - Variation in lightness is often used on maps to convey 
       order, where light colors imply less of something and dark colors, more.
 2. Color schemes
    1. Sequential – are suited to ordered data that progress from low to high. 
       Lightness steps dominate the look of these schemes, with light colors 
       for low data values to dark colors for high data values.
    2. Diverging – put equal emphasis on mid-range critical values and extremes
       at both ends of the data range. The critical class or break in the 
       middle of the legend is emphasized with light colors and low and high 
       extremes are emphasized with dark colors that have contrasting hues.
    3. Qualitative – do not imply magnitude differences between legend classes,
       and hues are used to create the primary visual differences between 
       classes. Qualitative schemes are best suited to representing nominal or
       categorical data.

###Labels
 1. Font
    1. Serif – includes a stroke added as a stop to the beginning and end of 
       the main strokes of a character
       1. Used for natural features (ex. rivers, lakes) 
       2. Examples: Times Roman, Courier, Palatino
    2. Sans serif – a typeface without (‘sans’) serifs
       1. Used for human features (ex. city, highway, place names) 
       2. Examples: Helvetica, Arial, Geneva
 2. Character spacing
    1. One way to suggest the spatial extent of those features is to use 
       character spacing (ex. county, valley, mountain range).
 3. Leading
    1. The space between lines of type. It is generally measured from baseline 
       (the line the text sits on) to baseline and expressed in [points][2].
    2. Leading variation is used in the same way as character spacing. By 
       choosing a large leading, you imply that a feature is not localized to a
       small area. Alternatively, a small (negative) leading value can pull 
       multiple lines of text closer together.
 4. Placement
    1. As a cartographic convention, labels are usually as horizontal as 
       possible with no upside-down labels.
    2. Area features – curve and extend the spaces to properly fill in the 
       areas enough that the audience can discern different areas
    3. Line features – sometimes it is useful to allow the label to conform to 
       the line pattern, for example, rivers. Labels can flow around the edges 
       along the line being careful not to have the letters too extended. 
 5.	Additional options for visibility
    1. Shadow – one way of creating contrast between the foreground (labels) 
       and the background (area colors)
    2. Halo – good way to make map text distinct from nearby or underlying 
       features
    3. Callouts – a line or other visual connector from the label to the 
       feature that can help make maps that are more clearly understood
       1. Ideally, callouts are used in conjunction with thoughtful feature 
          label placement. 
       2. Callouts should be used only when needed to clearly identify a 
          feature.

###Map composition
 1. Title – be in a large font, easily identifiable as the title of the map and
    include descriptive text as to the location and purpose of the map.
 2. Legend – generally appear near the bottom of a map or around the outer 
    edges. They may be placed outside or within the map. Make it easy to find 
    and read but not distracting from the map content.
 3. Scale bar - A map element used to graphically represent the scale of a map.
    A scale bar is typically a line marked like a ruler in units proportional 
    to the map's scale.
 4. Balance – has to do with how big, how many, and where the objects are in a 
    composition. 
    1. Weight of the objects is affected by color and size
    2. Direction of vision relates to the placement of objects in the 
       composition
 5. Visual hierarchy – refers to the arrangement or presentation of elements in
    a way that implies importance. In other words, visual hierarchy influences 
    the order in which the human eye perceives what it sees. This order is 
    created by the visual contrast between forms in a field of perception.
 
###Other Resources
 - [Esri’s Cartography Resources][3] – a list of resources compiled by Esri 
   including blogs & forums, tools, course material, map collections, and more

####Open Source Software:
 - [Quantum GIS][4] – Create, edit, visualize, analyze and publish geospatial 
   information on Windows, Mac, Linux.
 - [Inkscape][5] – a professional vector graphics editor for Windows, Mac OS X 
   and Linux.
 - [Mapbox][6] – Pick from a dozen beautifully designed maps and add it to your 
   application in just a few seconds. Mobile iOS and Android SDKs and 
   JavaScript API for the web make it easy. Or design your own map using 
   [Mapbox Studio][7].

####Tutorials/Reference:
 - [QGIS Training Manual: Symbology][8]
 - [QGIS Training Manual: Using Map Composer][9]
 - [QGIS Tutorial: Making a Map][10] – tutorial that walks you through creating
   a map in QGIS with Natural Earth data
 - [Quantum GIS Cartography][11] – how to make a US weather map in QGIS that 
   includes icons designed in Inkscape and refinement in GIMP
 - [Ten Things to Consider When Making a Map][12] – ten common considerations 
   that all cartographers should incorporate as part of their map making 
   process
 - [Elements of Cartographic Style][13] – guide to effective cartography by 
   Paul Cote, Harvard University GIS Specialist
 - [Cartographic Design in GIS][14] – Matt Sayler’s notes from GIS in Action 
   workshop he took

####Color:
 - [Color Brewer][15] – color advice for cartography; includes color-blind and 
   print-friendly options
 - [Color Scheme Designer][16] - application that generates color schemes based
   on one (base) color, which is supplemented with additional colors using one 
   of several algorithms.
 - [Colordot][17] – fun and easy web-based color picker

####Symbols:
 - [Maki][18] – simple point of interest symbol set made for web cartography. 
   It is an open source project by MapBox. 
 - [The Noun Project][19] – huge library of icons that may be useful for 
   mapping. Free membership includes free downloads that you must give credit 
   to the creator and royalty free icons to purchase for $1.99.

####Community:
 - [CartoTalk][20] – includes map gallery where you can get input on your map 
   or learn from the critique of others’ maps
 - [NACIS][21] – North American Cartographic Information Society
 - [Cartographer’s Guild][22] – forum created for map makers and aficionados 
   who specialize in maps of fictional realms, as commonly used in both novels 
   and games (both tabletop and role-playing), many Guild members are also 
   proficient in historical and contemporary maps.
 - CUGOS
 - FOSS4G

####Map Examples:
 - [Racial Dot Map][23] - interactive web visualization of geographic 
   distribution, population density, and racial diversity of the American 
   people in every neighborhood in the entire country.
 - [Beautiful Maps][24] – a collection of beautiful maps for inspiration
 - [Stamen Maps][25] – cartography by Stamen provided with JavaScript so that 
   you can use them for your own web-map projects
 - [Berlin Atlas of Crime][26] – interactive visualization of criminal activity
   in the German capital.
 - [What makes a map beautiful?][27] – maps and descriptions in response to the
   question on StackExchange

####Data Sources: 
 - [Civic Apps for Greater Portland][28] – spatial data for the City of 
   Portland.
 - [Map Zen Metro Extracts][29] – city-sized portions of Open Street Map 
   available for download in multiple formats; updated weekly.
 - [Oregon Geospatial Enterprise Office Spatial Data Library][30] - A 
   collection of Oregon geospatial data in a common coordinate system.  The SDL
   is served in an export format as well as through an Internet map service 
   (IMS).

[1]: http://bit.ly/1H65bAQ
[2]: http://desktoppub.about.com/od/glossary/g/Point.htm
[3]: http://blogs.esri.com/esri/arcgis/2013/06/04/favorites-cartographers/?utm_source=feedly
[4]: https://www.qgis.org/en/site/forusers/download.html
[5]: https://inkscape.org/en/
[6]: https://www.mapbox.com/
[7]: https://www.mapbox.com/mapbox-studio/#darwin
[8]: http://docs.qgis.org/2.0/en/docs/training_manual/basic_map/symbology.html
[9]: http://docs.qgis.org/2.0/en/docs/training_manual/map_composer/map_composer.html
[10]: http://www.qgistutorials.com/en/docs/making_a_map.html
[11]: http://vcgi.vermont.gov/sites/vcgi/files/event_archive/sinnott_QGIS_Cartography.pdf
[12]: http://www.gislounge.com/ten-things-to-consider-when-making-a-map/
[13]: http://www.gsd.harvard.edu/gis/manual/style/
[14]: https://github.com/mattsayler/CartographicDesign/blob/master/CartographicDesignNotes.md
[15]: http://colorbrewer2.org/
[16]: http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF
[17]: http://color.hailpixel.com/
[18]: https://www.mapbox.com/maki/
[19]: https://thenounproject.com/
[20]: http://www.cartotalk.com/
[21]: http://nacis.org/
[22]: http://www.cartographersguild.com/content.php
[23]: http://demographics.coopercenter.org/DotMap/index.html
[24]: http://mapsdesign.tumblr.com/
[25]: http://maps.stamen.com/#terrain/12/37.7706/-122.3782
[26]: http://www.economicworldmap.net/berlincrime.html
[27]: http://gis.stackexchange.com/questions/3083/what-makes-a-map-beautiful
[28]: http://www.civicapps.org/datasets
[29]: https://mapzen.com/metro-extracts/
[30]: http://www.oregon.gov/DAS/CIO/GEO/pages/alphalist.aspx

