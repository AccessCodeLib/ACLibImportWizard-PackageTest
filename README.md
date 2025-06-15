# ACLib Import Wizard: Package Test
Only for testing packages (repository will be deleted or restructured)

These packages can be used to import code modules, Access forms or reports with the [ACLib Import Wizard](https://github.com/AccessCodeLib/ACLibImportWizard).

## Package structure
```
<codelib>
  <package>{package name}</package>
  <description>{package description}</description>
  <use>%GITHUB%:{owner}/{repository name}@{branch name}/{relative path and file name}</use>
  <ref><name>{lib name}</name><major>{major version no}</major><minor>{minor version no}</minor><guid>{guid}</guid></ref>
  <test>{path to test file}</test>
  <test>{path to example file}</test>
</codelib>
```
