# PRL Website - Custom Code
<p><strong>*UNDER CONSTRUCTION *</strong> </p>
<p><em>The Mura Content Management System, as set up by the College of Natural Sciences, comes with a pre-built design to maintain visual consistency across all the College's websites. With that said, we do have the option to customize the content that is included between the header and footer areas. Below are the instructions for the PRL's custom code files, as found in their respective folders in this repository.</em></p>
<hr>
<h2>CSS Folder</h2>
<p>The CSS folder contains all custom stylesheets for the PRL website. Instructions for managing the code:</p>
<ul>
  <li><strong>Modifications outside of Mura take place in the 'prlCustomCSS-2018.scss' file</strong>. This file contains variables that allow for control and consistency of visual components. This requires knowledge of SCSS programming language.</li>
  <li> <strong>Use an automated compile and minimize system</strong>. Mura only reads .css files. Instructions:
    <ol>
      <li>'prlCustomCSS-2018.scss file' is automatically compiled into the 'prlCustomCSS-2018.css' file on each new change.</li>
      <li>Then, the 'prlCustomCSS-2018.css' file is automatically minimized into the 'prlCustomCSS-2018.min.css' file</li>
      <li> Finally, copy and paste the contents from the 'prlCustomCSS-2018.min.css' file into Mura's dedicated custom CSS file. The dedicated file is found in Mura's back end. Go to the File Manager, then look for prl_User_Assets/File/websiteTheme/prlCustomCSS.css. Right click and choose 'Edit' under the 'prlCustomCSS.css' file and paste the code. Save your changes.</li>
    </ol>
  <li><strong>In Mura, do not change the name of the 'prlCustomCSS.css' file.</strong> Any change will cause the server to not load the custom CSS.</li>
  <li><strong>All the files in the folder are also found in the PRL server.</strong> Ensure that all versions at all locations are up to date.
</ul>
<hr>
<h2>HTML Folder</h2>
<p> The HTML folder contains files that are used on the PRL website. <strong>All the files in the folder are also found in the PRL server. Ensure that all versions at all locations are up to date.</strong></p>
<p>File listing:</p>
<ul>
  <li><strong>homepage-brands-2018.html:</strong> The content is used in the first section following the hero image on the <a href="https://prl.natsci.msu.edu/">PRL homepage</a>. Any changes are made on the html file and the code is then pasted in the 'Homepage Three Brands Section' component located in the Mura back end.</li>
  <li><strong>PRL-card-markup.html:</strong> This is the markup for all the PRL card styles. It is also found on the PRL <a href="https://prl.natsci.msu.edu/about/internal-resources/brand-style-guide/">Brand Style Guide page</a>.
  </li>
</ul>
<hr>
<h2>History Timeline Folder</h2>
<p> The PRL History Timeline is located in the <a href="https://prl.natsci.msu.edu/about/">About</a> page. The timeline is a CSS and jQUery plugin called <a href="http://preview.codecanyon.net/item/zoomtimeline-css-timeline-pack/full_screen_preview/16918891?_ga=2.76863253.1076320330.1529523907-713049933.1525180595">ZoomTimeline</a> (<a href="http://digitalzoomstudio.net/">developer's site</a>) and allows for different presentation modes. </p>
<p>File listing:</p>
<ul>
  <li><strong>PRLtimelinejQuerycompiled.scss</strong>: The file includes all the package's CSS files in one location. This file is automatically imported to the "prlCustomCSS-2018.scss" file for inclusion on the PRL website. Do not make any modifications to this code.</li>
  <li><strong>about-page-history-timeline.html</strong>: This file is where the timeline content is modified. It also includes the JS scripts. To modify the timeline content, make the changes in this file, then paste the code in the PRL's About page.</li>
  </ul>
 <p> <strong>Any CSS changes to the timeline should be made in the 'prlCustomCSS-2018.scss' file in its relevant 'About' section</strong>. Do not make changes to the timeline SCSS file. Tke timeline is constantly updated by the developer, and on download of new versions, we lose any custom changes made.</p>
