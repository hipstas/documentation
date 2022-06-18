---
layout: default
title: Creating Annotations
permalink: creating-annotations
---
<!-- Add an essay or interpretive material below this line,
using HTML or markdown.  Do not modify this file above this line -->

<html>
  <body>
    <h1>Creating Annotations</h1>
    
    <p> AudiAnnotate is a tool to compile and present existing annotations. You will not create your annotations in AudiAnnotate, but instead import annotations created elsewhere. Annotations can be imported as a .tsv, .csv, .xlsx, or tab-separated .txt file. There are many different types of software that can facilitate making annotation files in these formats. Below, you'll find instructions for making annotations using <a href="#spreadsheet">a simple spreadsheet</a>, <a href="#audacity">Audacity</a>, and <a href="#adobe">Adobe Premiere</a>.</p>
    
    <hr>
    
    <h2 id="spreadsheet">Creating Annotations Using a Spreadsheet</h2>
    <p>You can use spreadsheet programs like Excel or Google sheets that export .tsv, .csv, or .xlsx files to create and organize annotations for AudiAnnotate. To do so:</p>
      <ol>
        <li>Create a blank spreadsheet or use <a href="https://docs.google.com/spreadsheets/d/1hJV4zSag5I_YFv2N_v00x9qaMqLYU3c_4Fck_okcthk/copy#gid=0">this template</a>. (Upon opening this link, you will be prompted to make a copy of this template for your own use.)</li>
        <br>
        
        <li>AudiAnnotate accepts annotations formatted with four columns:
          <br>
          <br>
          <img width="667" alt="Screen Shot 2022-06-14 at 1 32 59 PM" src="https://user-images.githubusercontent.com/97705205/173663362-e82c1a8c-e4fc-40eb-8ec7-87db11b5e4e7.png" border="2">
          <br>
          <br>
          <ul>
            <li>The first column should contain the beginning time (in total seconds or HR:MIN:SEC format) of the annotations.</li>
            <li>The second column should contain the end time (in total seconds or HR:MIN:SEC format) of the annotation if necessary*.</li>
            <li>The third column should contain the contents of your annotation.</li>
            <li>The fourth column should contain the name of the layer. The layer column is where you can differentiate types of annotations. Write your layer names as you would like them to appear in AudiAnnotate (e.g., "E_Layer," "Notes").</li>
          </ul>
          <br>
          
        <li> Enter your annotation(s) into the sheet as necessary.</li>
        <br>
        <img width="783" alt="Screen Shot 2022-06-14 at 1 35 41 PM" src="https://user-images.githubusercontent.com/97705205/173663821-9734c87b-402d-4540-88bb-1f69485a9230.png" border="2">
        <br>
        <br>
        
        <li> Once you have completed your annotations, download or save the particular tab of your spreadsheet you filled as either a .tsv, .csv, or .xlsx.</li>
        <br>
        <img width="483" alt="Screen Shot 2022-06-14 at 1 36 42 PM" src="https://user-images.githubusercontent.com/97705205/173664033-0d63f3a3-a153-4282-ad9d-0a321c3b913a.png" border="2">
        <br>
        <br>

    <p>*An end time would not be necessary to make a point annotation, only a range annotation.</p>
    <p>A <i>point</i> annotation references one point in the audio. Its beginning and end times are the same. An example point annotation looks like:</p>
    <table>
    <tr>
      <th>time in hr:min:sec (displays in total sec)</th>
      <th>time in hr:min:sec (displays in total sec)</th>
      <th>annotation</th>
      <th>layer</th>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>The audience laughs.</td>
      <td>Environment</td>
    </tr>
    </table>

    <p>Alternatively, you can omit the end time entirely for a point annotation:</p>
      <table>
      <tr>
        <th>time in hr:min:sec (displays in total sec)</th>
        <th>time in hr:min:sec (displays in total sec)</th>
        <th>annotation</th>
        <th>layer</th>
      </tr>
      <tr>
        <td>3</td>
        <td></td>
        <td>The audience laughs.</td>
        <td>Environment</td>
      </tr>
      </table>

    <p>A <i>range</i> annotation has different start and end time values, referencing a range of time in the audio. An example range annotation looks like:</p>
      <table>
      <tr>
        <th>time in hr:min:sec (displays in total sec)</th>
        <th>time in hr:min:sec (displays in total sec)</th>
        <th>annotation</th>
        <th>layer</th>
      </tr>
      <tr>
        <td>3</td>
        <td>5</td>
        <td>The audience laughs.</td>
        <td>Environment</td>
      </tr>
      </table>
  
    <hr>
    <h2 id="audacity">Creating Annotations Using Audacity</h2>
    <p><i><small>Note on Audacity Spyware Controversy:</small></i></p>
    <p><small>Audacity was  accused of being spyware when <a href="https://web.archive.org/web/20210717112058/https://www.audacityteam.org/about/desktop-privacy-notice/">an updated privacy policy</a> mentioned that data may be shared with WSM Group, a company that acquired Audacity and which is headquartered in Russia. Audacity published <a href="https://github.com/audacity/audacity/discussions/1225">a statement on GitHub</a> that shares more context on the policy. The post mentions that Audacity does not sell any third party data and that data collected at the desktop level includes IP address, OS version and CPU type, and error report data.</small></p>
    
    <h3><i>Downloading Audacity</i></h3>
    <p>Navigate to Audacity's download page for either your <a href="https://www.audacityteam.org/download/mac/">Mac</a> or <a href="https://www.audacityteam.org/download/windows/">PC</a>. There, you’ll download the .dmg file and double-click to follow instructions for downloading Audacity to your machine. We recommend downloading the latest version.</p>
    
    <h3><i>Annotating in Audacity - Method 1</i></h3>
        
    <ol>
      <li>Open Audacity, and in the top left, navigate to File→ Open, and then select the audio file you will be adding annotations to.</li>
      <br>
      <li>On the warning screen, make sure the “make a copy” choice is selected, then select ok.</li>
      <br>
      <li>We’ll use the “Label Track” to add annotations. Select “Tracks,” then “Add New,” then select “Label Track.”</li>
      <br>
      <li>To insert a label at a point in time, you’ll pause the poem by selecting the “p” key, or pressing the pause symbol in the upper left, at the place you want to add a label.</li>
      <br>
      <li>Select the time marker line to mark the place in time where you want to add the label. This typically will correspond to the place where you paused the audio.</li>
    <img src="https://user-images.githubusercontent.com/97705205/168941825-bff40044-be8e-455b-b6d4-d9e7329b1704.png" alt="audacity1" style="vertical-align:middle;margin:12px 0px" border="2">
      <br>
      <br>
      
      <li>Then, you’ll select command + b (the shortcut for Edit → Label → Add Label at Selection) to add a label on the label track. A field will pop up, and you can type your annotation. (Example: You may add “Stanza1” to mark the first stanza of a poem.) You could leave the point annotation as it is, or create an annotation as a range with a starting and an ending point.</li>
      <img src="https://user-images.githubusercontent.com/97705205/168941833-897c4f3e-1638-4dc9-a8dc-498486f9389a.png" alt="audacity2" style="vertical-align:middle;margin:12px 0px" border="2">
      <br>
      <br>
      
      <li>To create a range, you’ll select and drag the right edge of the point marker in the label track to the end of the moment you would like to annotate. You’ll have to play the recording to know where to end your range. A completed range will look like this:</li>
      <img src="https://user-images.githubusercontent.com/97705205/168941845-962cfc69-9d30-42ab-9784-085a38eceb38.png" alt="audacity3" style="vertical-align:middle;margin:12px 0px" border="2">
      <br>
      <br>
      
      <li>You can also add multiple label tracks to organize your annotations as you work. To do so, navigate to Tracks → Add New → Label Track.</li>
    </ol>
        
    <h3><i>Annotating in Audacity - Method 2</i></h3>
        
    <ol>
      <li>When you open the app and add audio, navigate to Edit → Labels, then select “Type to create a label.”</li>
      <br>
      <li>This creates a shortcut to add a label when any key is pressed. Now as you’re listening, when you type any key, a label will begin, allowing you to add labels without pausing. (Note: This will only add point-in-time labels, not ranges.) Using this method, to pause the audio, you need to use the pause button on the upper left of the interface (the “p” shortcut will not work).</li>
    </ol>
    
    <h3><i>Exporting labels from Audacity</i></h3>
        
    <ol>
      <li>Go to File → Export → Export Labels.</li>
      <br>
      <li>Name your labels and save as a .txt file. You will need this file when creating your project with the AudiAnnotate application.</li>
    </ol>
    
    <hr>
        
    <h2 id="adobe">Creating Annotations Using Adobe Premiere</h2>
        
    <ol>
      <li>Before creating annotations in Adobe Premiere for your AudiAnnotate video, you will need to create a new project in Adobe Premiere and title the project. Select“New Project…” on the left-hand opening menu of Premiere when prompted.</li>
      <br>
      <li>List a title for your project under “Name” and select “Ok.” </li>
      <br>
      <li>Once you have done so you can import a .mp4 file by selecting “File” then selecting “Import…” and selecting your downloaded .mp4 to import into Adobe Premiere from your files. </li>
      <br>
      <li>Double click the still from the .mp4 video in the bottom left-hand corner of the screen to put the clip into the timeline for annotating. Once the .mp4 is visible in the timeline, Adobe Premiere should look like this:</li>
    <img src="https://user-images.githubusercontent.com/97705205/168941855-29852fe8-f2f9-4ce9-89b7-dae9b76bca98.jpeg" alt="premiere1" style="vertical-align:middle;margin:12px 0px" border="2">
   </ol>
     
    <h3><i>Annotating Videos in Adobe Premiere Using Markers</i></h3>
        
    <ol>
      
      <li>Annotations are added using the “Marker” feature. To add a marker, select the play icon on the timeline to begin the video. Pause the video then select “Marker,”then “Add Marker” where you want to begin annotating. This will drop a marker at that point. </li>
      <br>
      <li>Once you have dropped a marker, select “Edit Marker” from the drop down menu. </li>
      <br>
      <li>The Marker “Name” should be the name of each layer you ultimately want in your AudiAnnotate project. The Marker “Comments” should be the text of annotation itself, such as a transcription. </li>
      <br>
      <li>You can also add a duration by clicking and holding the blue timecode (above the marker) and dragging it to the right. You can drag the second marker to the end of the clip to annotate a range instead of a point in time. </li>
      <img src="https://user-images.githubusercontent.com/97705205/168941859-d95c2f7d-18c0-42db-a05d-d2aef7c45afa.jpeg" alt="premiere2" style="vertical-align:middle;margin:12px 0px" border="2">
      <br>
      <br>
     
      <li>Continue adding markers with names for each layer and your annotations under “Comments.” It may help your organization to use distinct colors for markers corresponding to each layer, but it is not necessary. </li>
      <br>
      <li>Once you have finished annotating your video using markers, follow the instructions below to export your annotation file. </li>
    </ol>
      
    <h3><i>Exporting Your Annotations from Premiere</i></h3>
        
    <ol>
      
      <li>Select “File” then select “Export.” </li>
      <br>
      <li>Under the options for “Export” select “Markers.” </li>
      <br>
      <li>The default setting for a .csv file works for AudiAnnotate, so keep this export setting. </li> 
      <br>
      <li>You can rename the file as you wish and select a location for it, but do not edit the formatting of the file before uploading it to AudiAnnotate. </li>
      <img src="https://user-images.githubusercontent.com/97705205/168941863-56477d03-ce0c-4d79-a3b9-14611ca1dadd.png" alt="premiere3" style="vertical-align:middle;margin:12px 0px" border="2">
      </ol>
