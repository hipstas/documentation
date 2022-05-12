---
layout: default
title: Exporting for Preservation or Publication
permalink: exporting-for-preservation-or-publication
---
<!-- Add an essay or interpretive material below this line,
using HTML or markdown.  Do not modify this file above this line -->

<html>
  <body>

   <p>Because AudiAnnotate project sites are built using Jekyll, a static site generator, you can export them from GitHub and preserve or publish elsewhere.</p>

   <p>To export from GitHub, go to the repository page and look for the green “Code” button. Select “Download ZIP”.</p>
<img width="431" alt="Screen Shot 2022-05-12 at 12 58 39 PM" src="https://user-images.githubusercontent.com/97705205/168139459-671555fd-4e69-4e0c-97ae-bdddb160836b.png">

    <h3>Using the Export for Preservation</h3>
    <ol>
      <li>Unzip the file from the previous step. In the top level directory run “jekyll build”. This generates the static web pages as html files. Jekyll build does not create the correct filenames for IIIF manifests, so each directory within the generated site will have a manifest.json.html file instead of the correct manifest.json file.</li>
      <li>Rename the files to remove the .html extension, which will allow the A/V player to work (provided that the media is still available).</li>
      <li>Zip up the directory again, and place it in your preservation system.</li>
    </ol>

    <h3>Using the Export for Publication Elsewhere</h3>
<p>You can serve a Jekyll site on a variety of web hosts or your own web server. This list is a good starting point, or contact the IT staff at your institution for other options.</p>
    
  </body>
</html>
