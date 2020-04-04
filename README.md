Doma CodeGen Plugin Sample
==========================

This project show you how to use the [Doma CodeGen Plugin](https://github.com/domaframework/doma-codegen-plugin).

How to run
----------

Clone this repository:
```
$ git clone https://github.com/domaframework/codegen-sample.git
```

Change directory:
```
$ cd codegen-sample
```

Prepare a sample Database (If you use your Database, skip this step):
```
$ ./gradlew createDb
```

Try Doma CodeGen Plugin tasks.   
For example, generate all Java and SQL files:
```
$ ./gradlew domaCodeGenDevAll
```

Now the files are generated.  
Check under the src directory.

Finally, build your application with the generated files:
```
$ ./gradlew build
```

License
-------

```
Copyright 2020 domaframework.org

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
