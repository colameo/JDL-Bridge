# JDL-Bridge

### Installation
  
  - Follow [installation instruction of JHipster](https://www.jhipster.tech/installation/)
  
  ```
  $ npm install -g jdlbridge
  ```

### Usage

  ```
    usage:
           jdlbridge [-puml] [-png] [-adoc] -f <file(s)>

    Options:
     -puml                     Generate PlantUML for each JDL file
     -png                      Generate PNG for each JDL file
     -adoc                     Generate an AsciiDoc for each JDL file
     -f,--jdlfiles <file(s)>   JDL files or folders separated by a space with
                               wildcards
    $ jdlbridge -f myApp/MyApp.jdl
    $ jdlbridge -f myApp/My*.jdl
    $ jdlbridge -f myApp/*.jdl
    $ jdlbridge -f myApp/
    $ jdlbridge -f myApp/ myApp2/A*.jdl myApp3/*.jh
   ```
