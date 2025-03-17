# Clear Developer Caches (like old node_modules)

## Project Specific Caches

* find . -name 'node_modules' -type d -prune# du -h -d0; cd 

## Shared Caches
* Golang: #df -h; go clean -testcache; go clean -cache; go clean -modcache
* NVM: cd `nvm cache dir`; du -h -d
* rbenv versions
* cd ~/Library/Caches/Yarn/v6; du -h -d0 #python -m pip cache purge
* brew cleanup --dry-run #brew cleanup

## Docker Images

## VirtualBox Images

## Browser Caches

