# JDL-Bridge

### Installation
  
  1. Follow [JHipster installation instructions](https://www.jhipster.tech/installation/)
  
  2. Use npm to install this utility
  ```
  $ npm install -g jdlbridge
  ```

### Usage

  ```
    usage:
       jdlbridge [-puml] [-png] [-adoc] [-f <file(s)>]

    options:
     -puml                     Generate PlantUML for each JDL file
     -png                      Generate UML diagrams in PNG for each JDL file
     -adoc                     Generate an AsciiDoc with PlantUML for each JDL 
     -f,--jdlfiles <file(s)>   JDL files or folders separated by a space with
                               wildcards

    examples:
    $ jdlbridge -f myApp/MyApp.jdl
    $ jdlbridge -f myApp/My*.jdl
    $ jdlbridge -f myApp/*.jdl
    $ jdlbridge -f myApp/
    $ jdlbridge -f myApp/ myApp2/A*.jdl myApp3/*.jh
   ```
