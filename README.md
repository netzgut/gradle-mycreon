# Common Gradle Tasks for our Projects


## Files

### clean-pom.gradle

generate a pom for your java gradle project which can be imported to eclipse as maven project. Supports multi-module projects.

### mercurial.gradle

 - add method `hgBranch` to _ext_ properties to read current mercurial branch name
 - add method `hgFeature` to _ext_ properties to get current feature name (or null, if not in feature/XXX branch
 
## jenkins.gradle

depends on mercurial.gradle.

creates/updates/delets jenkins task based on a jenkins-config-template.xml in the project folder

## Licence
Licensed under the WTFPL ![WTFPL Badge](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)
