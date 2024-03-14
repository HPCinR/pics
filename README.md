# Common files for several HPC-R docs

First commit and push selected files here.

Then in the other doc using this submodule:
` git submodule update --remote` 

When configuring a new project to use this submodule, use
`git submodule add git@github.com:HPCinR/pics.git pics`

When the pics repo is moved to another organization or needs to be removed, use
`git rm pics` in the submodule-using repo. This removes the pics directory as well as cleans up the `.gitmodules` file. Commit and push submodule-using repo afterwards. Proceed as with a new project above to bring it back from its new location. This and more is explained at: [](https://stackoverflow.com/questions/1260748/how-do-i-remove-a-submodule).
