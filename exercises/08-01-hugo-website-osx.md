## Exercise 8 tutorial: Build a Hugo Website for GitHub Pages in OSX

The jekyll tutorial from Programming Historian is creating a few problems for some OSX users since the advent of Big Sur. It is possible to solve those problems, but it is simpler to just build a Hugo site instead. Here's what to do.

### 1. Read the hugo quickstart guide
It is available [here](https://gohugo.io/getting-started/quick-start/). These are the steps that you will follow, but you will tweak them slightly, as follows:

1. Before running the code in the guide's _Step 2: Create a New Site_, navigate in Terminal to your GitHub folder (i.e. the location on your local hard drive where GitHub Desktop looks for its files).
2. In _Step 6: Customize the Theme_, when you edit the `config.toml` file, change the `baseURL` to `"https://<yourGitHubUserName>.githug.io/quickstart/"`. This will serve the site from the repository that the quick guide establishes. Later, you can change the name from `quickstart` to something else (if you like) by changing the repository name (in GitHub) and the baseURL (in `config.toml`).
3. In _Step 7: Build static pages_, set the `publishdir` to `"docs"`. This is the directory where hugo puts the html site that it builds for you. The default directory is `public`, but GitHub Pages wants to look for a `docs` directory.
4. Change the name of the `public` folder on your hard drive to `docs`. Do this in Finder.

### 2. Publish your local quickstart repository to Github
Do this using GitHub Desktop: File > Add Local Repository... Then, commit your initial changes to master, and publish the repository.

### 3. Change the settings on GitHub to publish the site
Navigate to the repository that you've just published on github.com. In "Settings" (a tab on the top right), scroll down to GitHub Pages. Set the Source as `Branch:master` and the folder as `/docs`, then press Save.

### 4. Behold your site
In a minute or two, your site should be published at `https://<yourGitHubUserName>.githug.io/quickstart/`.
