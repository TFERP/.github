# Tropical Forest Ecology Research Programme

The Tropical Forest Ecology Research (TFER) programme is coordinated by the Forest Ecology team at the Singapore Botanic Gardens, National Parks Board (Singapore).

## Access management

Current Forest Ecology staff (and interns) will be added to respective teams which will give Read access to all repositories, as well as Admin/Maintain/Write access to selected repositories for that team. When they leave service, a discussion will be held on which repositories they will retain access to, if any. They will then be converted to outside collaborators and given access accordingly to these repositories; they will otherwise be removed from the organisation by default.

## IMPORTANT: Data security measures

All classified data, i.e., Closed and above, should be placed in a `./data/classified` folder. The contents of this folder should be 'gitignored', i.e., not pushed to GitHub. Therefore, all scripts and R Markdown files should point to this folder to access the data.

When generating products in the course of analysis, do consider if the products should be classified. If so, the destination output should be in the `./data/classified` folder as well.

Unclassified, i.e., Open data can be placed outside of this folder.

Graphs, tables, and R Markdown files that are generated with the intent of scientific publication will eventually be classified as Open and hence can be treated as such.

Code in scripts and R Markdown notebooks in and of themselves are not considered data. If any classified information has to be embedded in the files, move them to the `./data/classified` folder. Alternatively, think of how to avoid having such information embedded within, e.g., by reading source files or generating outputs into the `./data/classified` folder.

After copying the GitHub repositories back to the Analytics.Gov GitLab projects, remember to delete the `.gitignore` files so that the data can be accessible to others.

## Tips

* Create a folder on your computer (e.g., called "TFER") and clone all repositories from this organisation as sister folders inside. This will help to ensure cross-repo use of script, data, etc. It will also help to resolve the problem of same names for any repositories forked between organisations or with your personal GitHub account.

## Useful resources

* [R for Data Science](https://r4ds.had.co.nz/index.html)
* [Geocomputation with R](https://r.geocompx.org/)
* [Happy Git and GitHub for the useR](https://happygitwithr.com/)
* [R Graphics Cookbook, 2nd ed.](https://r-graphics.org/)
