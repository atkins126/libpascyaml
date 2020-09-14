# libpascyaml
libPasCYAML is object pascal wrapper around libcyaml library. Library for reading and writing structured YAML documents. The fundamental idea behind CYAML is to allow applications to construct schemas which describe both the permissible structure of the YAML documents.



### Table of contents

* [Requierements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Bindings](#bindings)



### Requirements

* [Free Pascal Compiler](http://freepascal.org)
* [Lazarus IDE](http://www.lazarus.freepascal.org/) (optional)

Library is tested with latest stable FreePascal Compiler (currently 3.2.0) and Lazarus IDE (currently 2.0.10).



### Installation

Get the sources and add the *source* directory to the *fpc.cfg* file.



### Usage

Clone the repository `git clone https://github.com/isemenkov/libpascyaml`.

Add the unit you want to use to the `uses` clause.



### Bindings

[libpascyaml.pas](https://github.com/isemenkov/libpascyaml/blob/master/source/libpascyaml.pas) file contains the translated headers to use this library in pascal programs.

:exclamation: library bindings is not finished now, but you can try to use it soon.