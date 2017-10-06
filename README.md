# This repository is deprecated

>	I do not work anymore on Liferay 7 support for XML Portlet Factory.
>
>	Now I contribute to [Damascus](https://github.com/yasuflatland-lf/damascus) project, the natural successor of XML Portlet Factory.
>
>	Sébastien Le Marchand
  
  
  
  
  
  
___

   
  
  
  
  
  
  
# XML Portlet Factory

The XML Portlet Factory is a command line java tool that generate CRUD portlets from XML files, using Service Builder. 

## Installation

Download **XMLPortletFactory_4.0-beta1.zip** from releases tab then unzip the archive.

## Usage

Drop your XML file into XMLPortletFactory directory then type the following command

```
$ java -jar xmlpf.jar <my-file> <path-to-liferay-workspace>
```

## Previous versions

For informations about version 3.0 (compatible with Liferay 6.0, 6.1 and 6.2), go to http://xmlportletfactory.org. 

## Features 

* Because XMLPortletFactory uses Liferay's Service Builder, tables are automaticly created for you at portlet deployment.
* Generated portlets use Liferay's search container, tags, etc. So they have very "Liferay" behavior, melting very well with themes.
* Languages English, French, Italian, Finnish and Spanish already implemented.

## License

XMLPortletFactory is licensed under the terms of GNU General Public License version 3.0 (GPLv3), and is OS Independent.

