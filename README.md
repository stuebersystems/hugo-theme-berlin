# Berlin - A Hugo theme

Berlin is a simple Bootstrap 5 based [Hugo](https://gohugo.io) theme for a blog website. It uses pure [Bootstrap 5](https://getbootstrap.com) without any custom CSS and [Bootstrap Icons](https://icons.getbootstrap.com/) Web Font for icons. The idea is to give you a framework for easy additional customization (e.g. CSS, custom fonts or own Bootstrap theme). This theme includes a sample blog for demonstration.

<small>This theme is based on [Hugo Bootstrap v4 Theme](https://github.com/Xzya/hugo-bootstrap)</small>

## Screenshots

The sample blog with Berlin theme but **without** any custom CSS.

![Screenshot - Default](https://raw.githubusercontent.com/stuebersystems/hugo-theme-berlin/master/images/screenshot.png)

The sample blog with Berlin theme and **with** additional custom CSS.

![Screenshot - Custom](https://raw.githubusercontent.com/stuebersystems/hugo-theme-berlin/master/images/screenshot-custom.png)

## Installation (under Windows)

Assuming you have already installed Hugo you should:	

1. Open the Windows command prompt

2. Run `hugo new site c:\myblog`. A new Hugo project will be created.

3. Switch to that newly created folder with `cd c:\myblog`.

Now you need to install the Berlin theme. You can do that by cloning the GitHub repository with Git or by manually copying the files.

With Git:

1. Run `git clone https://github.com/stuebersystems/hugo-theme-berlin c:\myblog\themes\berlin`

Manually:

1. Open a Web browser and go to `https://github.com/stuebersystems/hugo-theme-berlin`

2. Download the repository as zip archive.

3. Extract the files to `c:\myblog\themes`.

4. Rename the extracted folder `themes\hugo-berlin-theme` to `themes\berlin`.

You are now ready to configure your blog and to write your first article. 

## Sample blog

Let's set up a sample blog:

1. Go to `themes\berlin\exampleSite` and copy all files to `c:\myblog\`.

2. Run `hugo`. This will create your static pages under `c:\myblog\public`.

3. Run `hugo server` to start the embedded web server.

3. Open your web browser and navigate to `http://localhost:1313`.

4. Et voilà!

You can now study this example:

1. Sample configuration is inside `c:\myblog\config.toml`.

2. Sample custom CSS is found under `c:\myblog\static`

3. Sample custom layout overwrites are found under `c:\myblog\layouts`

4. And the sample blog posts are found under `c:\myblog\content`.

## Berlin theme specific configuration

Site related configuration:

Variable                           | Type   | Description
---------------------------------- | ------ | ---------
Site.Params.Author                 | string | Default author
Site.Params.Description            | string | Default description
Site.Params.Publisher              | string | Publisher info (for schema.org support)
Site.Params.PublisherLogo          | string | Publisher logo (for schema.org support)
Site.Params.DateFormat             | string | Date format
Site.Params.Truncate               | bool   | Show blog post summaries in home page
Site.Params.MainSections           | array  | In which sections blog posts are located?
Site.Params.Areas.ShowRelated      | bool   | Show related posts for current blog post
Site.Params.Areas.ShowShareButtons | bool   | Show social share buttons for current blog posts
Site.Params.Areas.ShowComments     | bool   | Enable comments for current blog posts
Site.Params.Sidebar.ShowRecent     | bool   | Show section "Recent" in sidebar
Site.Params.Sidebar.ShowTaxonomy   | bool   | Show sections "Tags" and "Categories" in sidebar
Site.Params.Sidebar.MaxRecentCount | int    | Max count of recent links in sidebar

Page related configuration:

Variable          | Type  | Description
------------------| ----- | -----------
Params.Share      | bool  | Show social buttons for the current page 
Params.NoComments | bool  | Disable comments for the current page
Params.NoAuthor   | bool  | Do not show author for the current page

For build in variables of Hugo see [Methods within your templates](https://gohugo.io/methods/).

## More resources

* [Hugo Documentation](https://gohugo.io/documentation)
* [Hugo Themes](https://themes.gohugo.io)
* [Hugo on GitHub](https://github.com/gohugoio/hugo)
