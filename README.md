[![](https://img.shields.io/maven-central/v/net.imagej/pom-imagej.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22net.imagej%22%20AND%20a%3A%22pom-imagej%22)
[![](http://jenkins.imagej.net/job/pom-imagej/lastBuild/badge/icon)](http://jenkins.imagej.net/job/pom-imagej/)

Maven POM parent for [ImageJ projects](https://github.com/imagej).
and for projects wishing to inherit the ImageJ
[Bill of Materials](http://imagej.net/BOM).

Projects that use `pom-imagej` as a parent project need to
override the following configuration sections:
* `<name>`
* `<description>`
* `<url>`
* `<inceptionYear>`
* `<organization>`
* `<licenses>`
* `<developers>`
* `<contributors>`
* `<scm>`
* `<issueManagement>`
* `<ciManagement>`
