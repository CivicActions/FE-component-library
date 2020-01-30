# CivicActions USWDS Frontend Component Library
Your can use this repo to reference components built with version 2 of the USWDS. It is also encouraged for you to contribute your own USWDS components ot this repo.
## How to update
This repo uses a git subtree to host the contents of the public directory on github pages in this repo. Once you add a new component and build sass and patternlab, add and commit all of your src files and push to the repo. Next add and commit all the changed files in `/public` then run `git subtree push --prefix=public origin gh-pages` to update the published version of this style guide to github pages.
## TODO
* Fix up patternLab header and footer (from starter template)
* Add more USWDS v2 components
* Add gulp tasks to combine patternlab build with sass compilation
* Look into Drupal compatibility
