# Overview
Docker container for Realm Object Server in order to be able to set it up fast. 

# Usage
```docker run -d -v <config-folder>:/etc/realm/ -p 9080:9080 spirosoik/realm-object-server```

## Docker-compose

```
# realm database
realm:
  image: spirosoik/realm-object-server
  ports:
   - 9080:9080
```

# Available

https://hub.docker.com/r/spirosoik/realm-object-server/


# License

```
Copyright 2016 Spiros I. Economakis

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
