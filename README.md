# obsidian-git-pages
Template for iCloud-compatible git controlled obsidian vault with mkdocs and GitHub pages

## features 

* The Obsidian vault is located in the root directory, to make it compatible with iCloud's folder structure
* A workflow publishes your site to your GItHub Pages using Mkdocs
* Beautiful theme, very configuratble, Material
* Ready to use in Obsidian
* All the power and control of Git at your fingertips, with the convenience of iCloud syncing

## how to use

* create new repo with this template
* checkout to anywhere, eg iCloud folder on windows
* open and edit in obsidian 
* Commit and push in your favorite client
* see the result on your GitHub pages

## why

* iCloud on Windows is very buggy
* sync is too expensive for hobby purposes

## Does it work?

Let's see. [[Here]]'s a link.

## Configuration

* Adjust your Obsidian settings as you wish
* Read the [mkdocs user guide](https://www.mkdocs.org/user-guide/) and the [mkdocs material documentation](https://squidfunk.github.io/mkdocs-material/setup/)
* Configure `mkdocs.yml` to adjust settings
* Update `.github/workflows/publish-to-pages.yml` to install additional pip packages