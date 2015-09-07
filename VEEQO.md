Customize and tweak CSS
=====

All customization should be provided in this file `src/material-design-lite-veeqo.scss`.
You may also import other files with customizations from `src/veeqo-tweaks` folder.
You can override sass variables here or in any customization file from veeqo folder.
You can add new components. Dont forget to provide a correct example. See this commit for details: https://github.com/vasiliy-pdk/material-design-lite/commit/c3e2cacb7ba89296e6969c120d9607fe4c000411 

BUT YOU SHOULD NOT CHANGE ANY MATERIAL UI COMPONENT THROUGH NATIVE FILE FROM
https://github.com/google/material-design-lite/ REPOSITORY BECAUSE IT WILL CAUSE LOTS
OF CONFLICTS

Easy way to put changes to Veeqo
===

* Run `material-design-lite$ gulp veeqo:build`. This command will create material lite distributive for Veeqo without
unused components
* Run `material-design-lite$ set VEEQO_PATH=./relative/path/to/veeqo/project/folder/`. It is set to `../veeqo/` by default
* Run `material-design-lite$ gulp put:veeqo`. It will place new built files to veeqo/vendor/assets folder

