# manifest
Multiple repositories management scripts for repo tool

## Sync Repositories
* curl https://storage.googleapis.com/git-repo-downloads/repo > ~/repo
* sudo mv ~/repo /usr/bin
* repo init -u https://github.com/OctopusNetwork/manifest.git --repo-url=https://github.com/OctopusNetwork/google-repo.git
* repo sync
