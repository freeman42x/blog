# Setting up Atom with agda-mode on Windows 10

1. Install Haskell Stack using one of the following options:
    * [Chocolatey - Haskell Stack package](https://chocolatey.org/packages/haskell-stack)
    * [Installer download](https://get.haskellstack.org/stable/windows-x86_64-installer.exe)
2. In `C:\sr\global-project\stack.yaml` change resolver to `lts-14.20`
3. Run `stack install Agda` to install the Agda binary and each time `stack` complains about `extra-deps` add them in the file above under a `extra-deps:` section
4. Install following Agda extensions inside Atom:
    * `language-agda`
    * `agda-mode`
5. Install the `Agda standard library` by [following the instructions here](https://github.com/agda/agda-stdlib/blob/master/notes/installation-guide.md).