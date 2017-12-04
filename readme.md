# Templated example of use

This is an example of use of "templated" project:
https://github.com/miyoda/templated-mvn.git

This example use the template:
https://github.com/miyoda/templated-example-template.git


The example copy a file with name "simple-file.txt".
The example copy a folder with a file with name "simple-folder/simple-file-on-folder.txt"

This files are in .gitignore but is not necesary, you can upload this to repository.

This example copy automatically in test.md and in test.html an embed text in the position with the code:
```html
<!-- start|embedded-text --> it was replaced <!-- end|embedded-text -->
```
From file:
> test.md|embedded-text.part
And
> test.html|embedded-text.part

In test.md is copied on start an end the files
> test.md|start.part
> test.md|end.part