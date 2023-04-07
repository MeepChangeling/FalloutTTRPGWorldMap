# FalloutTTRPGWorldMap
A simple leaflet map showing the locations of all known Fallout locations, and the borders of post-war nations.

This is a basic leaflet map depicting the locations of all places that have appeared in Fallout games so far (minus 76 as I do not play it and cannot find existing data for it.)

It works just like Google Maps, except no 3d view.

It uses OpenStreetmaps map tiles, and has both street and satalite views. Layers that show US roads and rail lines have been included and are independently toggelable.

<p>
<img style="float: left;" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/675e05e3-ff2c-4cca-938b-d36145e46726/dftr61o-fca86c5d-3847-4619-9e9f-000e45cbe046.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzY3NWUwNWUzLWZmMmMtNGNjYS05MzhiLWQzNjE0NWU0NjcyNlwvZGZ0cjYxby1mY2E4NmM1ZC0zODQ3LTQ2MTktOWU5Zi0wMDBlNDVjYmUwNDYucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.sZHEpLu-fxXP87TY7JOOYXyAbnPVwyb22wsR1nXy5Sk" width="49%" title="hover text">
<img style="float: right;" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/675e05e3-ff2c-4cca-938b-d36145e46726/dftr615-c835e330-ffbe-41f3-be83-b08e7b1c166a.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzY3NWUwNWUzLWZmMmMtNGNjYS05MzhiLWQzNjE0NWU0NjcyNlwvZGZ0cjYxNS1jODM1ZTMzMC1mZmJlLTQxZjMtYmU4My1iMDhlN2IxYzE2NmEucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.2VwdJAIa_TmCZ3jMONxItVCsc36QZj4HJH7LdJnixqY" width="49%" title="hover text">
</p>
<p>
<img style="float: left;" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/675e05e3-ff2c-4cca-938b-d36145e46726/dftr619-b58448b0-c793-4b05-b7ed-b732ebbedd34.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzY3NWUwNWUzLWZmMmMtNGNjYS05MzhiLWQzNjE0NWU0NjcyNlwvZGZ0cjYxOS1iNTg0NDhiMC1jNzkzLTRiMDUtYjdlZC1iNzMyZWJiZWRkMzQucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.3Qn-ytYHBLmRdd5bjE972qKFe45_55lVmWI0yusxN5s" width="49%" title="hover text">
<img style="float: right;" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/675e05e3-ff2c-4cca-938b-d36145e46726/dftr61b-02fb5138-b1b3-44d1-a11a-eb8dd8026a70.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzY3NWUwNWUzLWZmMmMtNGNjYS05MzhiLWQzNjE0NWU0NjcyNlwvZGZ0cjYxYi0wMmZiNTEzOC1iMWIzLTQ0ZDEtYTExYS1lYjhkZDgwMjZhNzAucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.w5NAa_tlOoSgnLavmUimaCDCswH4DvXnoMLd4dvv7bw" width="49%" title="hover text">
</p>

It was created in qgis, a free and open source gis tool. You will want to get the free plugin qgis2web to edit this map and export your edits.

To see it in action, simply download the files from this repo and open index.html in your browser.

Feel free to edit and change this map as you need. Feel free to use the map data to make maps in other systems like OpenLayers or MapBox if you want.

Host it anywhere or send it to your players. It's 5mb, so anyone can send it via discord.
