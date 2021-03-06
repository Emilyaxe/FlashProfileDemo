# FlashProfileDemo

A C# application that demonstrates the capabilities of `FlashProfile`, which has been released as [`Matching.Text`][MText] within the [PROSE library from Microsoft][PROSE].

## Installation

### Using VM Image (OOPSLA Artifact)
1. Grab the `oopsla-paper-40.zip` file from my shared [Google Drive folder](https://drive.google.com/open?id=12g3G1H69DSIJWHawD4r-mkKYhrjuN80g)
    - Optionally, verify that the `md5sum` of the zip file matches with the hash in `oopsla-paper-40.md5` file in the same shared folder.
2. Upon extracting the zip file, you should see `FlashProfile_LUbuntu_18.04.ova` VM image, a copy of this file (`Getting_Started.md`), and the artifact evaluation instructions (`Instructions.html`)
2. [Download](https://www.virtualbox.org/wiki/Downloads) and install `virtualbox` on your machine
3. [Import the `.ova` image](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html) to your virtualbox
4. Make sure you assign enough memory (at least 12GB recommended), since some of the datasets are _huge_.
5. Boot the system and perform some basic checks:
    - The password for user `user` is `flash`
    - Start a terminal session and try:
        - `cd FlashProfileDemo`
        - `make clean ; make init`
6. If you didn't see any errors so far, you can proceed with the [artifact evaluation steps](OOPSLA-AE.md).

## LICENSE

[PROSE] library is licensed under a [Microsoft Non-Commercial Software License][PROSE License].

The application code in this repository is licensed under the [MIT License](LICENSE.md).



[MText]: https://microsoft.github.io/prose/documentation/matching-text/intro/
[PROSE]: https://microsoft.github.io/prose/
[PROSE License]: https://microsoft.github.io/prose/SDKLicense.pdf
