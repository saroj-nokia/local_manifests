To initialize your local repository use
---------------------------------------

    git clone https://github.com/saroj-nokia/local_manifests.git -b lineage-20-rosy .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j $(nproc --all) --current-branch --no-tags --no-clone-bundle --optimized-fetch
