### Google Chrome
* After google chrome installed and run `google-chrome`, it appears
```
[6346:6382:1204/103614.981944:FATAL:nss_util.cc(632)] NSS_VersionCheck("3.26") failed. NSS >= 3.26 is required. Please upgrade to the latest NSS, and if you still get this error, contact your distribution maintainer.
```
run
```
sudo apt install --reinstall libnss3
```
