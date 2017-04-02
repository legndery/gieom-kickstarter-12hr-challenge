Gieom - Kickstarter
[Problem Statement]

Develop a pseudo front end application which would let the users help list and browse top Kickstarter projects conveniently.

[Minimum Requirement]

— Use of Web API to fetch project details.

Utilise Response Parameters:

[s.no, amt.pledged, blurb, by, country, currency, end.time, location, percentage.funded, num.backers, state, title, type, url].

Implement functionality to list project details in a web page.

— Visually interactive responsive design listing all the projects.

— Use your imagination and add features which would make things easier for end users.

— Zip all your Source code, Screenshot, & Deployment Instructions and upload.

[Plus Point]

— A feature to Search (via name).

— Implement Sort feature (to filter result through ‘percenatge funded’ in ascending and descending order).

— href url parameter.(Should open in new window | target="_blank")

— Use your imagination and add features which would make things easier for end users.

— Zip all your Source code, Screenshot, & Deployment Instructions and upload.

[Extra Work]

— Implement feature to sort projects based on end time.(Sort based on old-to-new and new-to-old).

— Add autocomplete feature to Search projects conveniently.

— Custom elegant design, fonts and icons to make web app more user-friendly.

— You may add portfolio activity comprising awesome work you have done on web application(s).

— Use your imagination and add features which would make things easier for end users.

[Guide]

— Gieom Kickstarter API: http://starlord.hackerearth.com/kickstarter

— Frontend Stack:

Vanilla Javascript, jQuery, HTML, CSS.

Custom CSS, Good if you can work around Bootstrap or Material Design.

Optional: Typography, Subtle pattern, Custom Icons.

Good to have: Angular2 or React.

— Prepend https://www.kickstarter.com/ before every Url param from API Response.

— PS: Application can be built with use of client-side scripting and need not require any backend.

— HTML5 Local Storage: http://html5demos.com/storage

— For icons and subtle texture:

http://glyphsearch.com/

http://subtlepatterns.com/thumbnail-view/

http://codebeautify.org/jsonviewer

http://www.flaticon.com/categories

[Wireframe MVP / Reference Structure]

Mockup image with instructions

Home

Detail

Note: Mockup design is just a reference made available to kickstart the design process, you are free to come up with your own design, we always admire creativity.

[API Params]

amt.pledged: amount pledged

blurb: project blurb

by: project creator

country: abbreviated country code

currency: currency type of amt.pledged

end.time: campaign end time (string "YYYY-MM-DDThh:mm:ss-TZD")

location: mostly city

pecentage.funded: unit %

num.backers: total number of backers

state: mostly US states (string of length 2) and others

title: project title

type: type of location (string: County/Island/LocalAdmin/Suburb/Town/Zip)

url: project url after domain (string)