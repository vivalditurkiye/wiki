# Linux snapshot alternative install script
Linux users on non-DEB/RPM distributions now have a new way to try out our snapshots.


Vivaldi strives to be a browser for everyone, which is why we support so many different workflows, operating systems and desktop architectures. Up until now we have only produced Linux .rpm and .deb packages and yet, Vivaldi is already in use on a far wider range of Linux distributions. This is possible due to the Linux community of package maintainers, who repackage our official packages for our shared userbase. Unfortunately, in many cases these non-official packages are only maintained for the stable update stream, leaving some of our fans out in the cold with regards to trying out our snapshots.

In the future, we hope this situation will improve, as we plan to introduce support for [Snap packages](https://docs.snapcraft.io/snaps/intro).
In the mean time (and for users of distros where Snap is not introduced), we are now providing a shell script that automates extracting the contents of a Vivaldi snapshot package and installing it, along with a convenient uninstall script.

**Note:** Updates to the information below will appear on the [“vivaldi-install.sh” help page.](https://help.vivaldi.com/article/installing-linux-snapshots-on-non-deb-rpm-distributions/)

## install-vivaldi.sh
To use, open a Terminal in the directory where you saved [“install-vivaldi.sh”](https://downloads.vivaldi.com/snapshot/install-vivaldi.sh/) and issue the following command: 

`
sh install-vivaldi.sh
`

To upgrade to newer builds in the future, simply re-run your local copy of the installer script whenever a new snapshot blog post comes out.

Pre-testing builds and other options
If you would like to test run the build with a clean profile/settings before you commit to installation, use the command line switch --test. For even more options, have a look at --help.

 

Note: This script is provided for users where no native package is readily provided by us (or your distribution). For Vivaldi stable releases in particular, we strongly recommend you use one of our official packages or ask your distribution if they provide unofficial repacks. We are more than happy to work with distribution maintainers to help facilitate this.

