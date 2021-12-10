<h1> zss one - One theme fits all </h1>
<br>
<font size="4">Premium theme using Jekyll version 4.1.2 & Bootstrap 5</font>
<hr>
<font size="4">Multipurpose (multiple homepage layouts)</font>
<hr>
<font size="4">Fully ready for production within minutes</font> 
<hr>
<font size="4">Responsive, SEO Friendly and Mobile optimized</font>
<hr>
<font size="4">Step by step documentation</font>
<hr>
<font size="4"> Detailed features</font>
<ul>
    <li>3 homepage designs which you can choose from</li>
    <li>Easily create and use your own with Bootstrap designs </li>
    <li>Includes multiple blog posts and frontpage as sample content </li>
    <li>Customizable through config files and properties:</li>
    <ul>
        <li> show/hide authors</li>
        <li> show/hide dates</li>
        <li> show/hide social integrations</li>
        <li> show/hide watermark</li>
        <li> show/hide selected posts on the front page</li>
        <li> change footer color </li>
    </ul>
    <li>Has Authors, Posts, Categories features </li>
    <li>Supports multiple image sizes for fast loading </li>
    <li>Lightbox and Image galleries support </li>
    <li>Code snippets highlight </li>
    <li>Git helper scripts (.bat) for easy GIT interaction </li>
    <li>Jekyll helper scripts (.bat) to easily build or start HTTP server locally </li>
    <li>100% Responsive </li>
    <li>Many SEO features; Open Graph protocol; schema.org using Microdata; meta tags </li>
    <li>No dependency on external resources </li>
    <li>Track your visitors with Google Tag Manager or Google Analytics integration </li>
    <li>YouTube and other video website support for embeded videos</li>
    <li>Pinterest integration </li>
    <li>Links and icons to other social platforms like YouTube, Facebook, Instagram, Medium, TikTok, Pinterest (hidden if not needed) </li>
    <li>Search feature </li>
    <li>Clean code </li>
    <li>Favicons for all types of devices</li>
    <li>.htaccess redirects with HTTPS support </li>
    <li>Minimized HTML CSS and JS code on build for super speed </li>
    <li>Sitemap with latest modification date </li>
    <li>RSS feed </li>
    <li>Great documentation and support in max. 48 hours </li>
    <li>Easy to upgrade Jekyll and Bootstrap version</li>
    <li>Easy to deploy, customize and extend </li>
</ul>


<font size="4"> Documentation</font>
<hr>
<font size="4"> Initial settings </font>
 <ul>
    <li>Install Jekyll https://jekyllrb.com/docs/installation/</li> 
    <li>Open _config.yml and customize settings. </li>
    <li>Replace the logo in ./assets/images and size in _config.yml </li>
    <li>Replace favicons in root folder and site.webmanifest. https://favicon.io/favicon-converter/ </li>
    <li>Edit .htaccess. </li>
    <li>Run clean.bat to delete temporary files. </li>
    <li>Run develop.bat to start the development server. </li>
    <li>Run build.bat to create the _site folder and prepare for production. </li>
    <li>Run git init and add your remote repository before using git-push.bat to clean the project, stage all files, commit and push. </li>
    <li>Change the text in ./includes/footer.html and ./includes/header.html to change the menu content</li>
    <li>Move your enabled social icons on the same row in ./includes/footer.html if needed </li>
 </ul>

<font size="4"> How to add a post </font>
 <ul>
    <li>Go to _posts folder </li>
    <li>Create a new file following the name convention from the old posts from _posts folder. </li>
    <li>Add images into ./assets/images/posts/number/full/ full size, 1200px width thumbnails into ./assets/images/posts/number/1200/ and 600px size in ./assets/images/posts/number/600/. You can create thumbnails using https://picresize.com/en/batch and convert them to webp for better compression with https://cloudconvert.com/. For better speed use .webp extension </li>
    <li>Look at the example posts to see how you can add a featured image, featured image thumbnail, featured image style, add an image gallery inside the post and add more images inside the post. </li>
    <li>Use Bootstrap 5 to customize your posts. https://getbootstrap.com/docs/5.0/getting-started/introduction/ </li>
 </ul>

<font size="4"> How to add an author </font>
 <ul>
    <li>Create a new page into the ./_authors folder similar to author-zeespire.md</li>
 </ul>

<font size="4"> How to customize pages </font>
 <ul>
    <li>Change homepage style: edit index.html and switch between homepage-style-1, homepage-style-2 and homepage-style-3</li>
    <li>Change posts style: ./_layouts/post-style-1.html </li>
    <li>For Contact and About page edit: ./about.markdown, ./contact.markdown </li>
 </ul>

<font size="4"> How to host on GitHub pages </font>
<ul>
    <li>Create a new repository on GitHub named <your_repo_name>.github.io </li>
    <li>Build using: build.bat </li>
    <li>Push the project in the new repo. </li>
</ul>

<font size="4"> How to host on your HTTP server and upload through FTP </font>
<ul>
    <li>After customization run build.bat</li>
    <li>Copy the content of ./_site folder to your FTP account</li>
</ul>
 