`/A/gt/`

Gloabsyetm #`A.sh`

Exlufdeils @`./.gitignore`

# configuration

Git-configs are split on 3-levels: *system* (all users), *global* (current user) & *local* (current project); where latter config overrides former. 

Configs are saved at `/etc/gitconfig` (system), `~/.gitconfig` (global) & `./.git/config` (local). 

Configs can also be accessed through CLI—`git config` & providing a flag `--system`|`--global`|`--local`. Providing no flags defaults to *local*, thus `git config --local --edit` is the same as `git config --edit`. 

```sh
# edit config-file
git config --edit

git config user.email "user@email"
git config user.name "User Name"
```