https://onspatial.github.io/geo-health-2025/

# Use GitHub:

## Build the Website and publish to GitHub.io page

The website source code is at the `main` branch and the compiled code is at the `gh-page` branch

1. Clone the project to your repository
2. Go to repository setting -> find the GitHub Pages
3. Set the branch to `gh-page` and save it.
4. Go to 'config.yml' and edit the baseurl to "https://yourGitHubUserName.github.io/youRepositoryName/"
5. Check the URL; it might take a while for the repo to be compiled and published to the url.

# Use Local Machine:

## Building the website

1.  Install [Hugo](https://gohugo.io/getting-started/installing/)

2.  It's done. Just start Hugo server to see it live!

        hugo server

3.  Open your browser: http://localhost:1313/geo-health-2025/

## Configure the website

Everytime when you change a place, Hugo will automatically refresh your browser.

1. Change the concent in "about": Edit `themes/hugo-conference/layouts/partials/about.html`
2. Change the cover image: replace `static/img/cover.jpg`
3. Change all other content: Edit `config.yml`

## Publish to GitHub.io page

The website source code is at the master branch

1. Compile the source code in the master branch by running the following commnd the terminial: `hugo `
2. Copy the content in the generated folder `public` and push it the "gh-page" branch.

The website will be published in a few seconds once you push the content to "gh-page" branch.
