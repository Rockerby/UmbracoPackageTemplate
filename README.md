# Umbraco Package Template

This simple project is a starter template to create packages for Umbraco (currently setup for 8.6.1).

**admin email** admin@umpacko.com  
**admin pass** passwordpassword

### UmbracoPackageTemplate.Web

This project contains the Umbraco instance that is used to test the package. There is a post-build event that copies the content of the UmbracoPackageTemplate.Package project into this project. It references the package project should any code elements of the package be needed.

### UmbracoPackageTemplate.Package

This contains the actual code for the package. Having it here allows for easier packaging up to ship out the package.

Credit to [@prjseal](https://github.com/prjseal) for tutorials on how to get started.