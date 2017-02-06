# ANT Task for JSP Precompilation 
It is used for pre-compilation of JSP files. It will make sure that it won't break in production instance while runtime compilation.

#### Pre-Requisite : `ant` and `tomcat`

## Usage
- Pull this project locally
  `git clone https://github.com/sumitramteke/jsp-compile-ant-jasper.git`
- Publish this project into `tomcat` and start. Make sure project is running.
- Run `ant` script from `build.xml` location in command prompt/terminal
  `-Dtomcat.home=<tomcat-home-path> -Dwebapp.path=<webapp-path/jsp-compile-ant-jasper>`
- You will be able to see logs on console.