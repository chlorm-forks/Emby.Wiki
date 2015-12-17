###Installation:
Emby-Server is packaged and supported on as many platforms and architectures as possible. You can find installation instructions that are distribution specific either [here](./Installation) or on our [OBS project page](https://software.opensuse.org/download.html?project=home%3Aemby&package=emby-server). Additionally, you can find our official docker images on the hub which support amrv7l and amd64.

###Before running the Wizard:
Ideally before running the setup wizard you might want to follow some of the following guide lines. Linux is very particular about permissions and if the permissions on folders which hold your media or the ones containing Emby-Server's user data are not set right, your experience maybe be sub-par. Packing guidelines across distributions suggest that daemons run as their own user and Emby-Server by default runs under the user `emby`. Now, user emby might not have read and write access to the directories that house your media and this can be addressed one of two ways. One, you can adjust the user Emby-Server runs as. You can do this by adjusting the conf file which can be found in `/etc/emby-server.conf`. Please read the comments and directions within the file. Or secondly, you can adjust append the user emby to the groups that have read and write access to your media files. You may read more about Linux permissions [here](https://www.digitalocean.com/community/tutorials/an-introduction-to-linux-permissions).