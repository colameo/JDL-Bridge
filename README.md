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
           jdlbridge [-h] [-u] [-p] [-a] [-f <file(s)>]

    options:
     -h,--help                 Print this help message
     -u,--uml                  Generate PlantUML file for each JDL file
     -p,--png                  Generate UML diagrams in PNG for each JDL file
     -a,--adoc                 Generate an AsciiDoc and PlantUML files for
                               each JDL
     -f,--jdlfiles <file(s)>   JDL file search pattern (wildcards allowed) or
                               folders separated by a space

    examples:
    $ jdlbridge -u -f myApp/MyApp.jdl
    $ jdlbridge -p -f myApp/My*.jdl
    $ jdlbridge -a -f myApp/*.jdl
    $ jdlbridge -a -f myApp/
    $ jdlbridge -adoc -f myApp/ myApp2/A*.jdl myApp3/*.jh
   ```
