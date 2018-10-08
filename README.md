# Berlin

Berlin is a simple Bootsrap 4 based Hugo theme for a blog website. It uses pure [Bootrap 4](https://getbootstrap.com) without any custom css and [Material Design Icons](https://materialdesignicons.com) Web Font for icons. The idea is to give you a framework for easy further customization (e.g. additional css, own fonts or bootstrap theme). This theme includes a sample blog for demonstration.

<small>This theme is based on [Hugo Bootstrap v4 Theme](https://github.com/Xzya/hugo-bootstrap)</small>

## Installation (under Windows)

Asumed you have installed hugo already you should:	

1. Open the Windows command prompt

2. Run `hugo new site c:\myblog`. A new hugo project will be created.

3. Switch to that newly created folder with `cd c:\myblog`.

Now you need to install the Berlin theme. You can do that by cloning the GitHub repository with Git or by manually copying the files.

With Git:

1. Run `git clone https://github.com/stuebersystems/hugo-theme-berlin c:\myblog\themes\berlin`

Manually:

1. Open Web browser and go to `https://github.com/stuebersystems/hugo-theme-berlin`

2. Download the reporportry as zip archive.

3. Extract the files to `c:\myblog\themes`.

4. Rename the extracted folder `themes\hugo-berlin-theme` to `themes\berlin`.

You are now ready to configure your blog and to write your first article. 

## Sample blog

Now we are ready to create content:

1. Goto `themes\berlin\exampleSite` and copy all files to `c:\myblog\`.

2. Run `hugo`. This will create your static pages under `c:\myblog\public`.

3. Run `hugo server` to start the embedded web server.

3. Open your web browser and navigate to `http://localhost:1313`.

4. Voilà!

You can now study the example:

1. Sample configuration is inside `c:\myblog\config.tom`.

2. Sample custom CSS you'll find under `c:\myblog\static`

3. Sample custom layout overwrites you'll find under `c:\myblog\layouts`

4. And the sample blog posts you'll find under `c:\myblog\content`.

## Configuration

...

## More resources

[Hugo Documentation](https://gohugo.io/documentation)
[Hugo Themes](https://themes.gohugo.io)
[Hugo on GitHub](https://github.com/gohugoio/hugo)
