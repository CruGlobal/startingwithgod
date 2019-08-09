# startingwithgod.com
This project is meant to hold AEM customizations for https://www.startingwithgod.com 

## Modules

The main parts of the template are:

* ui.apps: contains the `/apps` and `/conf` parts of the project, ie JS & CSS clientlibs, components, and templates

## How to build

To build all the modules run in the project root directory the following command with Maven 3:

    mvn clean install

If you have a running AEM instance you can build and package the whole project and deploy into AEM with  

    mvn clean install -PautoInstallPackage
    
Or to deploy it to a publish instance, run

    mvn clean install -PautoInstallPackagePublish
