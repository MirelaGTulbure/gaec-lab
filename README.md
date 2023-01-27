# GAEC website
This is the repo that hosts the information used in the [GAEC website](https://gaec-lab.netlify.app/), which is from the Academic Template for [Hugo](https://github.com/gohugoio/hugo) (see the documentation [here](https://wowchemy.com/docs/) for specific info). The goal for this website is that anyone in the lab can update when needed via markdown files, so this is meant to be a collaborative effort.

The URL for the website is currently the basic, free one (gaec-lab.netlify.app). If we want to have a custom domain, that is easy to do but there is a small cost per year).

> **Note** 
> 
> We can edit this Github repository online or offline; once we update the files, Netlify will sync the website after a very short time delay. But, sometimes the website could fail to render due to issues in some files, especially when many things are added to the repository. There is a way to debug and preview the website locally using our computers. To configure offline debug settings, please see the end of this document.

## Poster Fix
In order to add a poster, navigate to static/media and upload the poster file labelled as 'YYYY-MM_lastName_conferenceAbbrv.jpg'. Please make sure your file is around 1 MB in order to make sure loading times are not too long. Information on resizing images is provided below in Adding Pictures. After adding your picture, navigate to `content/poster/poster_gallery.md` and add the details for your poster following the examples of the other ones. Here you can add a caption labeling the event at which you presented your poster. 

## Brooke's Edits ^^

## Adding Pictures
Photos can be added to different website items, like lab member profiles, publications, and lab updates. **PLEASE** make sure you re-size your images to ~ 1MB before including, otherwise we will quickly get to a point where the website is slow to load due to a number of large file size pics. Re-sizing can be done at sites like [this one](https://resizeimage.net/) or [this one](http://www.simpleimageresizer.com/). These were found with a quick google search, there are also others.

## Updating Content
Content can either be edited directly in GitHub or by cloning the repository to your local machine, editing files, and pushing back to GitHub. Website deployments (rendering the website) are done automatically with each commit via Netlify, so it's advised that you clone the repo when possible (e.g. push several commits at once, instead of one for each small change). 
- *NOTE:* currently the Netlify account is linked to Mirela's GitHub, but anyone can have access if they want. Please send an email to her asking to be added.

### Lab member info
Each lab member has their own "page" on the website, under the [Team section](https://gaec-lab.netlify.app/people/). To update your page, navigate to your [folder](https://github.com/MirelaGTulbure/gaec-lab/tree/main/content/authors) and update the information in `_index.md` as appropriate. To add a profile picture, upload an image labeled `avatar.jpg` (can be png, but then update the reference accordingly) that preferably is <= 1 MB.
- Each lab member belongs to a different category. These can be seen (and/or edited) in `content/people/people.md`. Note that the attribution must be spelled and capitalized exactly the same.
- If you do not have one of the social options (e.g. you don't have a Twitter), then remember to comment out those lines with `#`.

### Add a lab update
To add lab update (i.e. short post like a blog or news announcement), navigate to `content/post` and create a folder starting with the date and a short qualifying of the name, for example "2021-08-15_testPost". Inside the folder create a file named `index.md` that files the standard toml format; see the [sample post](https://github.com/MirelaGTulbure/gaec-lab/blob/main/content/post/21-07-13-finesst-vini) for an example. You can also add an associated image (`image.png`) if you want.

## Mollie's editing ^ Ian's README below

### Add a poster picture
If you have a poster you'd like to add to our image gallery, navigate to `assets/media/albums/poster_img` and upload a png (or jpg) of your poster there. After adding your picture, navigate to `content/poster/poster_gallery.md` and add the details for your poster following the examples of the other ones. Here you can add a caption labeling the event at which you presented your poster.
- **Please** make sure your file is < 5 MB maximum; we don't want to bog down the website with large files when they don't have to be.
  - To re-size your images, please see the section above labeled **Adding Pictures**.
- Please also label your file as `YYYY-MM_lastName_conferenceAbbrv.png` to be consistent.

### Add a publication
To add a publication, navigate to `content/publications` and create a folder labeled as Date-journalAbbr-descriptor, so for example "2021-01-04_AWM-Perin-Tulbure" or "2020-12-07_AGU-southeastern-Gaines" (these examples come from Mirela's site). 

**If having issues with the YAML then see Troubleshooting below**

Inside each folder you can have the following 4 items
- citation file (`cite.bib`): this is a BibTex file with the citation for the paper. If this is added, then it allows people to download the citation from the lab website.
- pdf of the paper
  - **NB** If your paper is open access, please just add the URL in the `index.md` file in the "pdf" place in order to save memory.
  - Otherwise, upload a pdf of the paper and rename the file to be the exact same name as the publication folder
- an associated image (`featured.jpg`): some image if you want, otherwise the publication will show up only with text on the website.
- `index.md`: this is the primary metadata for hoow the website renders the publication info. Similar to other index files, this has a specific toml format, so make sure everything is filled out as needed. Remember, if other lab members are on the publication, refer to them using their username on the website, which is all lowercase (e.g. joshgray). This way their user page is linked to the publication.
- If you're adding a paper that has a publish date after the current date (e.g. it is 8 Dec and your paper will be published 14 Jan), then you need to add yesterday's date to the `publishDate:` field and the future date to the `date:` field in order for it to be shown on the website.

### Default info for the website
To change around how the website looks, including color, background pictures, etc, see the following, plus the Wowchemy documentation (linked at top) for more details.
- `content/home` controls the home page
- `config/_default/` controls the underlying metadata and parameters

### Offline debug with `Hugo`

> **Cautiion**
> 
> Normally, this part is not necessary if we just want to add some content to the website. Unless there are some errors rendering the website. 

The website is created by the [Wowchemy Academic Template](https://wowchemy.com/) using [Hugo](https://github.com/gohugoio/hugo), so we can configure Hugo on our local computer and debug the website. The method of configuring Hugo varies by the operation system we use. There is a [comprehensive documentation](https://gohugo.io/getting-started/installing/) describing the required steps, but special attention should be paid to some stuff. 

#### Install Hugo

If we use Mac OS and Linux, it's easy, we can just follow the [documentation](https://gohugo.io/getting-started/installing/) to install Hugo. But, be sure to choose **version 0.87.0** as our website template depends on that version. Newer version could introduce compatibility issues. 

Here, we describe the configuration steps for Windows machines without using Chocolatey or Scoop. We use the pre-compiled Hugo binary.

1. Download [Hugo extended for Windows](https://github.com/gohugoio/hugo/releases/tag/v0.87.0) binary version 0.87.0. *Be sure to download "hugo extended", not "hugo", it has extended functionalities used by our website template*. 
2. Unzip the downloaded file to a system folder, for example, `C:/Program Files`. The folder should have three files: `hugo.exe`, `LICENSE`, and `README.md`. 
3. Download and install [Go](https://go.dev/dl/) if don't have one installed on the machine. The installation of Go is straightforward and thus skipped here.
4. Add the Hugo folder to system Path. Right click on the **Start** button -> Click on **System** -> **Advanced System Settings** -> **Environment Variables**. Then, in the **User variables** section, select the row labeled **“Path”** and click the **Edit...** button. In the popped up dialog, click the **Browse…** button and select the directory to which **hugo.exe** was extracted, for example, `C:/Program Files/hugo_extended_0.87.0_Windows-64bit/`. Click **OK** at every window to exit.
5. Open a terminal and execute `hugo help` to check whether the installation has succeed. 

#### Debug the website

1. Clone the website repository to the local machine using `git clone`, open up a terminal and `cd` to that folder. 
2. In the terminal, execute `hugo server -D`, the website should be compiled and can be found in a web browser using the address `http://localhost:1313/`. The argument `-D` stands for `debug`, so any warning and error information would be shown in the terminal. 
3. To close the server, press `CTRL + C` in the terminal.

Hugo supports live update, which means when the local server is running, changing the content of the website would trigger a rendering event and update the local previewing website. However, the live update does not handle structure changes, which means for example when adding a new blog post folder in the `post` directory, we'd have to quit and restart the hugo server to see it.


----

## Troubleshooting

How do I fix YAML errors?
- Especially if you're copying content from elsewhere online (e.g. an abstract into a publication `index.md` file), it's best to check the YAML is valid before you try pushing (it will just fail anyways if something is wrong). Here's a helpful site for you to double-check: http://www.yamllint.com/

What happens if the website hasn't updated despite you making changes?
- Most likely there the rendering process didn't find something where it thought it should. If you don't have access to the Netlify account, either ask Ian to check or ask for access. Usually this is because everything must be in its specific place with a specific name (and references to different files also need to be matched). This can take some trial and error, but one thing that can help is comparing with a fully-done website, like Mirela's [site](https://practical-pike-e67a8a.netlify.app/) and the associated [GitHub repo](https://github.com/MirelaGTulbure/gaec-lab).

---

# Wowchemy's Research Group Template for [Hugo](https://github.com/gohugoio/hugo)

The **Research Group Template** empowers your research group to easily create a beautiful website with a stunning homepage, news, academic publications, events, team profiles, and a contact form.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 5 minutes, or [view the showcase](https://wowchemy.com/user-stories/).

_[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio (via Blogdown), generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs._

- 👉 [**Get Started**](https://wowchemy.com/templates/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to unlock rewards with sponsorship](https://wowchemy.com/plans/)

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli/):** Automatically import publications from BibTeX

[![Screenshot](./preview.png)](https://wowchemy.com/templates/)

## Demo Credits

Please replace the demo images with your own.

- [Female scientist](https://unsplash.com/photos/uVnRa6mOLOM)
- [2 Coders](https://unsplash.com/photos/kwzWjTnDPLk)
- [Cafe](https://unsplash.com/photos/RnDGGnMEOao)


[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/starter-research-group/readme?pixel)](https://github.com/igrigorik/ga-beacon)
