#**Fork only to raise MARKER to 131072 for issue #465**


Picasso
=======

A powerful image downloading and caching library for Android

![](website/static/sample.png)

For more information please see [the website][1]



Download
--------

Download [the latest JAR][2] or grab via Maven:

```xml
<dependency>
    <groupId>com.squareup.picasso</groupId>
    <artifactId>picasso</artifactId>
    <version>(insert latest version)</version>
</dependency>
```


ProGuard
--------

If you are using ProGuard make sure you add the following option:

```
-dontwarn com.squareup.okhttp.**
```



License
--------

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


 [1]: http://square.github.io/picasso/
 [2]: http://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=com.squareup.picasso&a=picasso&v=LATEST
