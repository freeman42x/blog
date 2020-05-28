# Setting up Atom with agda-mode using Nix package manager

1. Install `haskellPackages.Agda` Nix package
2. Install `atom` Nix package if you do not have it already installed
3. Install the following Nix packages which are required by the Atom Agda extensions:
    * `python2Full`
    * `nodejs`
    * `gcc`
    * `binutils`
    * `gnumake`
4. Install following Agda extensions:
    * `language-agda`
    * `agda-mode`
5. Install the `Agda standard library` by [following the instructions here](https://github.com/agda/agda-stdlib/blob/master/notes/installation-guide.md).