# Library Theme jQuery
## _The library that adds jQuery as dependency for Lutece sites that were built with jQuery stuff._

![](https://dev.lutece.paris.fr/jenkins/buildStatus/icon?job=lutece-tech-library-theme-jquery)
The Theme jQuery library permit to add jQuery minimal libs to run older version of Lutece core ( less than 7.5 versions ). 
This lib must only be used for jQuery compatibility problems.

## Features

- Import jQuery main libs and css

> All plugins that are shipped with jQuery plugins
> may require this lib.
> The aim is to remove those dependencies ASAP

## Installation

Add [lutece-tech-library-theme-jquery](https://github.com/lutece-platform/lutece-tech-library-theme-jquery) to your site POM.xml
```xml
<dependency>
    <groupId>fr.paris.lutece.plugins</groupId>
    <artifactId>lutece-tech-library-theme-jquery</artifactId>
    <version>[1.0.0-SNAPSHOT]</version>
    <type>jar</type>
</dependency>
```
