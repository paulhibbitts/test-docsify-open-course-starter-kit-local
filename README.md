| 🛑 | **This is a testing-only repository. View the main project repository at https://github.com/hibbitts-design/docsify-open-course-starter-kit-local.** |
|---|:--|

# Docsify Open Course Starter Kit Local

[![Docsify](https://img.shields.io/npm/v/docsify?label=docsify)](https://docsify.js.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/hibbitts-design/docsify-open-course-starter-kit/blob/main/LICENSE)
<a href="https://discord.gg/zT8eS8ZG">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289DA.svg" alt="Docsify Discord Chat" />
</a>
> This is a starter kit to quickly create a Markdown-based open course site with the site generator [Docsify](https://docsify.js.org) (v5 Preview). To address possible privacy/GDPR concerns all needed css/js files are loaded locally and not via CDN (thanks to [@mandrasch](https://github.com/mandrasch) for the suggestion).

📸 Docsify Open Course Screenshots
---
![ Docsify Open Course Starter Kit](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/smartmockups_lzlzwwuj.png)
_Figure 1. Docsify Open Course Starter Kit. Explore a demo at [hibbitts-design.github.io/demo-docsify-open-course-starter-kit/](https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/)_

🚀 GitHub Pages Quickstart
---
**Pre-flight Checklist**  

1. GitHub account

**Installation and Deployment**

1.  Sign in to [GitHub](https://github.com) if you have not already done so

2. Tap **Use this template** on the source repository (upper-right green button)  and then choose **Create a new repository**
![ Docsify Open Course Starter Kit - Install Page 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-1.png)

3. Choose the name for your new repository to contain the copied site files and then tap **Create repository from template**
![ Docsify Open Course Starter Kit - Install Page 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-2.png)

4. Go to **Settings** of your newly created repository, tap the **Pages** tab (on the left-hand side), choose **main branch**, then **docs folder** and finally tap the **Save** button (see more details in the [Docsify documentation](https://docsify.js.org/#/deploy?id=github-pages))
![ Docsify Open Course Starter Kit - Install Page 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-3.png)

5. And you're done! (view your new site using the provided URL on the **Pages** tab - it can take up to 10 minutes for your site to be initially available)
![ Docsify Open Course Starter Kit - Install Page 4](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-4.png)

Do you use GitLab? You can also use Docsify with [GitLab Pages](https://docsify.js.org/#/deploy?id=gitlab-pages)!

✏️ Editing Your Docsify Site Pages on GitHub
---  

1. Go to the Docsify Markdown (.md) page in the `docs` folder of your repository you want to edit
![ Editing Your Docsify Site Pages 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-1.png)

2. Tap the **Pencil Icon** (top left-hand toolbar area) to start the editor
![ Editing Your Docsify Site Pages 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-2.png)

3. Scroll down to the bottom of the page and tap the **Commit changes** button to save your changes
![ Editing Your Docsify Site Pages 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-3.png)

[Learn more about creating pages in Docsify.](https://docsify.js.org/#/more-pages)

🔗 Activating the “Edit this Page” Link on Your Docsify Site
---   

1. At the top-level of your GitHub Repository copy the URL
![ Docsify Open Course Starter Kit - “Edit this Page” Link 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-1.png)

2. Tap on the **docs** folder
![ Docsify Open Course Starter Kit - “Edit this Page” Link 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-2.png)

2. Tap on the **index.html** file
![ Docsify Open Course Starter Kit - “Edit this Page” Link 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-3.png)

3. Tap the **Pencil Icon** (top left-hand toolbar area) to start the editor
![ Docsify Open Course Starter Kit - “Edit this Page” Link 4](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-4.png)

4. Find the line `var gitLinkRepoURL = '';` and enter the URL of your own GitHub Repository between the two quotes (replace `github.com` with `github.dev` to use the GitHub.dev web-based editor currently in Beta) and then scroll down to the bottom of the page and tap the **Commit changes** button to save your changes
![ Docsify Open Course Starter Kit - “Edit this Page” Link 5](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-5.png)

To remove the “Edit this Page” link on your Docsify site, restore the value of `gitLinkRepoURL` to `''`.

💻 Locally Editing Your Docsify Site Pages
---  

**Editing Your Docsify Site Pages on Your Desktop**
1. Tap **Code** on your repository (upper-right green button)
2. Choose **Open Desktop** and follow the prompts, installing [GitHub Desktop](https://desktop.github.com/) if not already present
3. You will now be able to edit your Docsify site (in the `docs` folder) using the desktop editor of your choice (e.g. [Atom](https://atom.io/))
4. Use GitHub Desktop to push any changes to your repository.  

[Learn more about using GitHub Desktop](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project).

You can also clone (i.e download) a copy of your repository to your computer and [run Docsify locally](https://docsify.js.org/#/quickstart) to preview your site. See the below video for details.

🧩 Embedding your Docsify Page Content into Other Systems
---  

![ Docsify Open Course Page Embedded into the Canvas LMS](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-canvas.png)
_Figure 2. Docsify Open Course Page Embedded into the Canvas LMS. Explore an example Canvas LMS course using Docsify Open Course pages for content at [https://canvas.sfu.ca/courses/44038/](https://canvas.sfu.ca/courses/44038)_

The optional `embedded` (all lowercase) URL parameter hides a site’s sidebar for seamlessly embedding Docsify page content within another platform such as Canvas LMS, Moodle, Microsoft Teams or being displayed in an existing or new Browser tab. The parameter `standalone` is supported as an alias for `embedded`.

To only display Docsify page content, add the following to a Docsify page URL:

`?embedded=true`

Example standard Docsify page:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources  

Example Docsify page displaying only page content (i.e., no sidebar is shown):  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true  

To optionally show a page Table of Contents (based on included Headers), use the following:

`?embedded=true&toc=true`

Example Docsify page displaying only page content:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true  

Example Docsify page displaying only page content with a page Table of Contents included:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true&toc=true  

To optionally override the hiding of the navbar when displaying only page content, use the following:

`?embedded=true&navbar=true`

Example Docsify page displaying only page content:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true  

Example Docsify page displaying only page content with the navbar still displayed:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true&navbar=true  

To optionally hide the 'Edit this Page' link, use the following:

`?embedded=true&hidegitlink=true`

Example Docsify page displaying only page content:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true  

Example Docsify page displaying only page content with the 'Edit this Page' link hidden:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true&hidegitlink=true  

To optionally show the footer ('_footer.md' file), use the following:

`?embedded=true&footer=true`

Example Docsify page without footer:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true  

Example Docsify page with footer shown:  
https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true&footer=true  

🖼 Presenting your Docsify Page Content as Standalone Webpages
---  

In addition to using URL parameters when embedding Docsify page content into other systems, it is possible to permanently display all pages as standalone, and to also always display a page Table of Contents.

**To Display all Pages as Standalone**
1. Open the `index.html` file for editing.
2. Locate the line `var standalone = false;` and change it to `var standalone = true;`.
3. Save the `index.html` file and reload site.

**To Display Page Table of Contents**
1. Open the `index.html` file for editing.
2. Locate the line `var ToC = false;` and change it to `var showToC = true;`.
3. Save the `index.html` file and reload site.

Please note a page must have a series of Headings (#, ##, ###) for the Table of Contents to be displayed correctly.

❛❜ Setting the Name of your Docsify Site 
---  

1. Open the `index.html` file for editing.
2. Locate the line `<title>Docsify Open Course Starter Kit</title>` and change the text between the title tags to be displayed as the site name on the Browser tab
3. Locate the line `name: 'Docsify Open Course Starter Kit',` and change the text between the quotes to be displayed as the site name at the top of the Docsify Sidebar
4. Save the `index.html` file and reload site.

🛠 Using an LMS to Host a Docsify Open Course Site
---

As Docsify Open Course Starter Kit does not require a web server, it can actually be hosted on many LMSs that support file libraries such as Canvas and Moodle.

For example, here is a [Docsify Open Course Site hosted within a Canvas course](https://canvas.sfu.ca/courses/44038/files/15884796/download) and here is a [Docsify Open Course Site hosted within a Moodle course](https://paulhibbitts.net/moodle/mod/resource/view.php?id=25). Single Docsify Open Course site pages can also be embedded while hosted on the same system.

**Hosting a Docsify Open Course Site on your LMS**
1. Tap **Download** on your repository page
2. Upload to your LMS file storage area, and unzip the upload file
3. Based on your LMS, determine the external URL required to load the `index.html` file within the Docsify `Docs` folder. In Canvas, an example URL would look similar to `https://canvas.sfu.ca/courses/44038/files/15884796/download`.

| :warning: | Once hosted within your LMS, changes made to the source GitHub repository are no longer automatically reflected on your hosted Docsify site. Any GitHub repository updates must be manually uploaded to the LMS file library area. |
|---|:--|

📚 Docsify and Markdown Resources
---
**Docsify**  
[Docsify Documentation](https://docsify.js.org/#/?id=docsifyg)  
[Docsify Basics by MichaelCurrin](https://michaelcurrin.github.io/docsify-js-tutorial/#/?id=docsify-basics)  

**Markdown**  
[Markdown Here Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)  
[Markdown Guide](https://www.markdownguide.org/)  

💡 Content Display Tips and Techniques
---
**Including Code Blocks**  
Using [Prismjs](https://prismjs.com/) code blocks with syntax highlighting is supported for the languages [included with Docsify](https://docsify.js.org/#/language-highlight?id=language-highlighting) and as well Bash, Go, Java, Kotlin, PHP, Python and Swift. To embed a code block use the Markdown standard of triple backticks and start the block with the name of the language, for example to embed a block of Javascript code with syntax highlight the following would be used:

<pre>
```javascript
function test() {
  console.log("Hello world!");
}
```
</pre>
Which would then appear as:
```javascript
function test() {
  console.log("Hello world!");
}
```

**Displaying Images in a Grid**  
3 or more images can be transformed into a responsive grid gallery by including them in lists. For example:
```markdown
- ![image1](path/to/image1.jpg)
- ![image2](path/to/image2.jpg)
- ![image3](path/to/image3.jpg)
```

🧰 Useful Markdown CSS Classes
---

`accordion`

```html
<div class="accordion">

<details>
  <summary>Topic One</summary>
  
  Topic one details here.
  
</details>

<details>
  <summary>Topic Two</summary>
  
  Topic two details here.
  
</details>

</div>
```

`announcement`  
When the Docsify v5 theme is enabled, to style Blockquotes similarly to the default Docsify-This style.  

```html
<blockquote class="announcement">
  <h2>What’s Happening This Week</h2>
  <h3>How to explore the problem space?</h3>
  <h4>Important Reminders</h4>
  <ul>
    <li><a href="#">Journey Map</a> assignment <span class='badge'> Tue Jun 12th 11:59pm PDT</span></li>
    <li><a href="#">Course Reflection Log</a> assignment <span class='badge'> Fri Aug 3rd 11:59pm PDT</span></li>
  </ul>

  <h4>Required Reading</h4>
  <ul>
    <li>
      <a href="https://www.smashingmagazine.com/2014/10/the-skeptics-guide-to-low-fidelity-prototyping/">
        The Skeptic’s Guide To Low-Fidelity Prototyping
      </a>
    </li>
  </ul>

  <p>
    <a href="https://canvas.sfu.ca/courses/44038/quizzes/166553" class="button primary">
      Required Reading Quiz due Jun 4th
    </a>
  </p>
</blockquote>
```

`badge`  

```html
<span class='badge'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge' style='--badge-bg-color: #0164db;'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge' style='--badge-bg-color: #e7c500; --badge-text-color: #000;'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge'> [Tue May 16 2:30pm PT](https://www.timeanddate.com/worldclock/fixedtime.html?msg=CMPT-363+Blackboard+Mini-lectures+and+Activities&iso=20220516T1430&p1=256&ah=1&am=50)</span>  
```

`banner-image` (cropped to height of 250px on large screens, 125px on small screens)  

```markdown
![UX - User Experience](images/12650723674_d5c85af332_k.jpg ':class=banner-image')
```

`banner-tall-image` (cropped to height of 350px on large screens, 175px on small screens)  

```markdown
![UX - User Experience](images/12650723674_d5c85af332_k.jpg ':class=banner-tall-image')
```

`button`  

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button')
```

`button-rounded`  

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-rounded')
```

`button-secondary`  

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-secondary')
```

`button-rounded-secondary`  

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-rounded-secondary')
```

`card`

```html
<div class="card">

  ## [Card Title](#)
  ![Card Image](images/example.jpg)
  Card content goes here.

</div>
```

`card-list`

```html
<div class="card-list">
 <div class="card">

 ## [Blog Post Title Link](#)
 ![Blog Post Image](images/mountain.jpg)

 Blog post preview text goes here with more details about the content.  

 Jan 1, 1970. 

 [Read More](# ":class=navpill")

 </div>
 <div class="card">

 ## [Another Blog Post](#)
 ![Blog Post Image](images/forest.jpg)

 Another blog post preview with different content.  

 Jan 1, 1970. 

 [Read More](# ":class=navpill")
    
 </div>
</div>
```

`card-rounded`

```html
<div class="card-rounded">

  ## [Card Title](#)
  ![Card Image](images/example.jpg)
  Card content goes here.

</div>
```

`embedly-card` (for linked article previews, embedded slides/videos, etc.)  

```markdown
<a class="embedly-card" data-card-controls="0" data-card-align="left" href="https://blog.prototypr.io/defining-usability-e7bf42e8abd0">Defining usability</a>
```

`header-image-fade` (suggested width of 1200px to 2000px)  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image-fade')
```

`header-image-fade-full-width` (suggested size of 1200px to 2000px, and display of Table of Contents is not available)  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image-fade-full-width')
```

`header-image-full-width` (suggested size of 1200px to 2000px width and 400px to 600px height, and display of Table of Contents is not available)  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image')
```

`image-75` (scale image to 75%)

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-75')
```

`image-50` (scale image to 50%)

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-50')
```

`image-25` (scale image to 25%)

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-25')
```

`image-75-border`

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-75-border')
```

`image-50-border`

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-50-border')
```

`image-25-border`

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-25-border')
```

`image-border`

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-border')
```

`image-border-rounded`

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-border-rounded')
```

`navpill`

```markdown
[GitHub](https://github.com/hibbitts-design/docsify-this ':class=navpill')
```

```html
<a class="navpill" href="https://github.com" target="_blank"><i class="fab fa-github fa-fw"></i>GitHub</a>
```

`responsive`

```html
<img src="https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main/images/docsify-this-web-page-builder.jpg" width="910" height="682" class="responsive image-border" alt="Docsify-This Web Page Builder">
```

`row` & `column`  

```html
<div class="row">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

```html
<div class="row reverse-columns">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

```html
<div class="row">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column-right">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

`video-container-4by3`  

```html
<div class="video-container-4by3"><div class="video-container-16by9"><iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ"></iframe></div>
```

`video-container-16by9`  
Automatically added to all iFrames with the source domains 'youtube.com' or 'docs.google.com'.  
```html
<div class="video-container-16by9"><iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ"></iframe></div>
```

🎨 Visual Customization
---

A Docsify Open Course Starter Kit site can be visually customized using CSS within the `custom.css` file located in the folder `docs/assets/css`. Using this file new Markdown CSS classes can be defined.

CSS:  
```css
.markdown-section .mybutton, .markdown-section .mybutton:hover {
  cursor: pointer;
  color: #CC0000;
  height: auto;
  display: inline-block;
  border: 2px solid #CC0000;
  border-radius: 4rem;
  margin: 2px 0px 2px 0px;
  padding: 8px 18px 8px 18px;
  line-height: 1.2rem;
  background-color: white;
  font-family: -apple-system, "Segoe UI", "Helvetica Neue", sans-serif;
  font-weight: bold;
  text-decoration: none;
}
```

Markdown:  
```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=mybutton')
```

Docsify theme settings can also be configured, as seen in the examples provided in the default `custom.css` file.

CSS:  
```css
:root {
    --link-color: #0F6CBF!important;
}
*/
```

It is also possible for dual CSS styling to be configured, with CSS applied to when viewing the site (with overriding custom CSS included in a `STYLE` tag in the `_sidebar.md` file) and then other CSS settings within the `custom.css` file applied to when viewing standalone pages (i.e. `?embedded=true`)

CSS in Sidebar file (`_sidebar.md`):  
```css
<style>
  :root {
    --link-color: #CC0633;
    --link-text-decoration: none;
    --link-text-decoration--hover: underline;
  }
</style>
```

🌐 Using MAMP to View Docsify Sites Locally
---

An alternative to installing Docsify locally (as described following this section) is to use MAMP to view your Docsify sites locally on your own computer.

1. Download [MAMP](https://www.mamp.info/)
2. Move your local Docsify site to the **htdocs** folder of MAMP
3. Turn MAMP on, tap **WebStart** and then tap **My Website**
4. Tap on the folder containing your local Docsify site and then tap on the **docs** folder

📼 Video Walkthrough of Local Docsify Install/Config
---
[![Generating Documentation Sites with GitHub and Docsify - Alysson Alvaran](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/youtube.png)](https://www.youtube.com/watch?v=TV88lp7egMw)  
_Video 1. Generating Documentation Sites with GitHub and Docsify - Alysson Alvaran_

🙇‍Credits and Special Thanks
---
All past and current Docsify.js.org maintainers and contributors.