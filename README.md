# VBA-project-template

A set of configuration files for VBA projects

Copy the following files into your project to make sure that Git, text editors
and [VBA-Import-Export](https://github.com/mattpalermo/VBA-Import-Export) all
work properly:

* `.editorconfig`
* `.gitattributes`
* `.gitignore`

When using Git and text editors with VBA code, it is very important to make sure
the line endings are always CRLF. The `.gitattributes` and `.editorconfig` will
make sure this is always taken care of. `.editorconfig` also makes sure that the
indenting is kept consistent with how the VBE likes it.

Appropriate configuration for using
[VBA-Import-Export](https://github.com/mattpalermo/VBA-Import-Export) has also
been included in `.gitattributes` and `.editorconfig`.

The `.gitignore` is a helpful starting point for your Git ignore. It ignores
the Microsoft office temporary files. I have also assumed that you don't want
to accidentally commit your built add-in file(s) to the repo.
