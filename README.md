### One time setup

* install hugo

* create dir 
`mkdir repo-dir & cd repo-dir`

* create directory structure for site

`hugo new site .`

* git init 
`git init .`

* add theme

`git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod`

* remove hugo.toml and customize it in hugo.yml

* view development server
`hugo serve`


* generate site
`hugo -d docs`

* push generated site to main branch 

* add CNAME record for the custom dns record

* Update github pages setting to use custom dns, enforce https and serve the content from docs directory. 

### on re-cloning the repo

* pulling submodules
`git submodule update --init --recursive`

* generate site

`hugo -d docs`

* to update papermod

`git submodule update --remote --merge`
