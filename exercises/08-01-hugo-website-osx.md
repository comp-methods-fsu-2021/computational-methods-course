## Exercise 8 tutorial: Build a Hugo Website for GitHub Pages in OSX

The jekyll tutorial from Programming Historian is creating a few problems for some OSX users since the advent of Big Sur. It is possible to solve those problems, but it is simpler to just build a Hugo site instead. Here's what to do.

### 1. Read the hugo quickstart guide
It is available [here](https://gohugo.io/getting-started/quick-start/). Follow its steps exactly, with the following slight tweaks:

1. Before running the code in the guide's _Step 2: Create a New Site_, navigate in Terminal to your GitHub folder (i.e. the location on your local hard drive where GitHub Desktop looks for its files). (Here's a [basic introduction](https://www.macworld.com/article/2042378/master-the-command-line-navigating-files-and-folders.html) to navigating around in the Terminal.)
2. In _Step 6: Customize the Theme_, when you edit the `config.toml` file, change the `baseURL` to `"https://<yourGitHubUserName>.github.io/quickstart/"`. This will serve the site from the repository that the quick guide establishes. Later (if you like), you can change the name from `quickstart` to something else by changing the repository name (in GitHub) and the baseURL (in `config.toml`).
3. Before running the `hugo -D` command in _Step 7: Build static pages_, add the line `publishdir = "docs"` to the `config.toml` file (and save). This variable sets the directory where hugo puts the html site that it build will for you. The default directory is `public`, but GitHub Pages wants to look for a `docs` directory.
4. To complete this GitHub-Pages-specific tweak: within the `quickstart` folder on your hard drive, change the name of the `public` folder to `docs`. Do this in Finder. (If there's already a `docs` folder, you can go ahead and delete the `public` folder.)

### 2. Publish your local quickstart repository to Github
In GitHub Desktop, choose File > Add Local Repository... Select your `quickstart` folder. Then, commit your initial changes to master, and publish the repository.

### 3. Change the settings on GitHub to publish the site
Navigate to the repository that you've just published on github.com. In "Settings" (a tab on the top right), under "Manage Access," set the site to public. Then, scroll to the GitHub Pages section. Set the Source as `Branch:master` and the folder as `/docs`, then press Save.

### 4. Behold your site
In a minute or two, your site should be published at `https://<yourGitHubUserName>.github.io/quickstart/`.

### 5. Adding content
Now that you have a basic site running, you can learn to develop it. In Visconti's _Programming Historian_ lesson, the [tweaking the settings](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages#tweaking-the-settings-) section covers these basics in the context of jekyll. Hugo operates on similar principles, with slightly different semantics. For example, Jekyll's `_config.yml ` file is `config.toml` in Hugo, and Jekyll's `_posts` folder is Hugo's `content` folder.

The particular Hugo configuration requirements are specific to each [theme](https://themes.gohugo.io/), and you will have to experiment in order to get things right. Fortunately, this is easy using localhost. Themes with good documentation will tend to be easiest to use. The documentation is typically in the theme's README.md file on Github, or on the Homepage linked via Hugo's [theme directory](https://themes.gohugo.io/).
