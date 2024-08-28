# Tropical Forest Ecology Research Programme

The Tropical Forest Ecology Research (TFER) programme is coordinated by the Forest Ecology team at the Singapore Botanic Gardens, National Parks Board (Singapore).

## Access management

Current Forest Ecology staff (and interns) will be added to respective teams which will give Read access to all repositories, as well as Admin/Maintain/Write access to selected repositories for that team. When they leave service, a discussion will be held on which repositories they will retain access to, if any. They will then be converted to outside collaborators and given access accordingly to these repositories; they will otherwise be removed from the organisation by default.

## IMPORTANT: data security and use of folders

All classified data, i.e., Closed and above, should be placed in a `./data/classified` folder. The contents of this folder should be 'gitignored', i.e., not pushed to GitHub. Therefore, all scripts and R Markdown files should point to this folder to access the data.

When generating products in the course of analysis, do consider if the products should be classified. If so, the destination output should be in the `./data/classified` folder as well.

Unclassified, i.e., Open data can be placed outside of this folder.

Scripts that do not contain data are not considered data.

Graphs, tables, and R Markdown files that are generated with the intent of scientific publication will eventually be classified as Open and hence can be treated as such.

## Tips

* Create a folder on your computer (e.g., called "TFER") and clone all repositories from this organisation as sister folders inside. This will help to ensure cross-repo use of script, data, etc. It will also help to resolve the problem of same names for any repositories forked between organisations or with your personal GitHub account.
