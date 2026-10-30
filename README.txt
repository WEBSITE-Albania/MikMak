Open index.html (or host this folder on any static host). No build step, no dependencies.
Add media ONLY in js/config.js: heroVideo, heroPoster, gallery[] (9 slots on the Gallery page, first 3 on Home), homeIntroPhotos[], aboutPhotos[], homeDishPhotos{} (4 horizontal photos for the home page dishes), menuPhotos{}. Put files in video/ and images/.

IMPORTANT: keep the folder structure. Each page loads css/style.css, js/config.js and js/app.js by relative path.
If you open index.html on its own (without the css/ and js/ folders next to it) the page appears unstyled and empty.
