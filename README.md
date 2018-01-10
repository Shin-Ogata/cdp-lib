﻿# cdp-lib

## About cdp-lib

Contains npm modules used primarily by cdp boilerplate generator.


### Repository structure
Folder and file structure of this repository is the following list.

    root/
        dist/                                       // deploy target directory.
            @types/                                 // type definition file here.
        src/                                        // source file directory.
        docs/                                       // specification documents.
            reports/                                // test reports directory.
                coverage/                           // output test coverage reports.
                metrics/                            // output source metrics reports.
            typedoc/                                // typedoc generated documents here.
        tests/                                      // tests scripts directory.
        built/                                      // temporary built scripts here.


### How to install

```
    $ npm install cdp-lib
```

### How to development

* build

```
    $ npm run build
```

* test

```
    $npm test
```

* deplay and update dependencies

```
    $ npm run update
```


### How to use
Please see the following documentation.

- [English/英語](docs/en)
- [Japanese/日本語](docs/ja)

## Release Notes
Please see the following link.

- [Release Notes](RELEASENOTE.md)

## License

Copyright 2017, 2018 Sony Network Communications Inc.  

Licensed under the Apache License, Version 2.0 (the "License");  
you may not use this file except in compliance with the License.  
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software  
distributed under the License is distributed on an "AS IS" BASIS,  
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  
See the License for the specific language governing permissions and  
limitations under the License.
