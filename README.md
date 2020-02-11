# JDL-Bridge

### Installation
  
  1. Follow [JHipster installation instructions](https://www.jhipster.tech/installation/)
  
  2. Use npm to install this utility
  ```
  $ npm install -g jdlbridge
  ```

### Usage
```
                              _
      _ _____  _            .'x|.        _      _                _
     | |  __ \| |         .'|xx| `.    '|x|    | |         x    | |
     | | |  | | |       .'  |xx|   `..' |x|`.  | |__  _ __ _  __| | __ _  ___
 _   | | |  | | |     .'    |xx|        |x|  `.| '_ \| '__| |/ _` |/ _` |/ _ \
| |__| | |__| | |____.=========|==========|====| |_) | |  | | (_| | (_| |  __/
 \____/|_____/|______/~~~~~~|**|~~~~~~~~|*|~~~~|_.__/|_|  |_|\__,_|\__, |\___|
                                                                    __/ |
                                                                   |___/
JDLBridge (c) Copyright 2019-2020 - JHipster Project - Serano Colameo

usage:
       jdlbridge [-h] [-s] [-u] [-p] [-a] [-f <file(s)>]

options:
 -h,--help                 Print this help message
 -s,--skip-validation      Skip validations
 -u,--uml                  Generate PlantUML for each JDL file
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
$ jdlbridge --adoc --jdlfiles myApp/ myApp2/A*.jdl myApp3/*.jh
```
