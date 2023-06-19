# YuLearn

### Setup Instructions (for a rainy day...)

1. Clone yulearn folder
2. `git submodule update --init --recursive`
3. `git submodule sync`
3. `git submodule update --init --force remote`

If some stuff is missing, it's because it's detached. 

1. `cd <plugin_folder>`
2. `git branch -a`
3. `git branch --track <branch_name> origin/<branch_name>`