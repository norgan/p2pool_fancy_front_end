p2pool_fancy_front_end
======================

Front end that can be co-located on a separate web server or hosted on the p2pool node.

you can see it running at http://www.norgzpool.net.au

This code is based on goblins stats code https://github.com/m3ta/p2pool-stats-2 from the extended front end for p2pool https://github.com/hardcpp/P2PoolExtendedFrontEnd

I have attempted to add commenst where i can but please keep in mind much of this is taken from the above projects. Please support the original authors if you can, if you wish to help me out then yo may donate to 1BCspL7f75gcU17M62524KSnfh7tyy3ZnF.

Much of the styling is done in css, specifically the bootstrap-responsive.css, menu styling is done in component.css.

Much of the data is taken from json and leverages jquery. 

How to get it working on your node:

Step 1. copy the code to the root web folder of your hosting platform or to the web-static folder of p2pool.

Step 2. rename anything in "d3.json('http://au.norgzpool.net.au:9332" to your node address. Do this in the index.html graphs.html and stats.html.

Step 3. load your own logo for the header. make it 711x150 pixels or as close to that as you can. it can be jpg, png or gif and you change it in the header div of the index and other pages (the dreamweaver template is included if you want to use that so you only change in the index and template).

Step 4. browse and enjoy p2pool stats in a nice interface and using standard port 80


Sorry in advance if somethign is not clear, I am not a developer, I just know enough to piece things together. Happy to assist if required. 

Note: If i have missed crediting anyone or there is something here you do not wish to be redistributed please accept my appology and contact me to have it removed immediately. 

Known Issues:

1. Version is blank on all pages other than index
2. stats page graphs need to be aligned to the width of main graphs


To Do:
1. update other pages to show p2pool version or remove the entry from footer
2. remove server config to external files to make running multiple nodes easier
3. find a way to make the info pane stay away if user clicks it away then refreshes
4. clean up css
5. add more commenting
6. find a way to fix the external json issue with the node_ststus front and and integrate the highflow charts from that
7. fix graph alignement on the stats page
