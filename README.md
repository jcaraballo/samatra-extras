samatra-extras [![Build Status](https://travis-ci.org/springernature/samatra-extras.svg?branch=master)](https://travis-ci.org/springernature/samatra-extras) [![](https://jitpack.io/v/springernature/samatra-extras.svg)](https://jitpack.io/#springernature/samatra-extras)
------------

Samatra with batteries included. 

The aim of Samatra is to have as few dependencies as possible - if fact it only depends on the servlet-api.jar 
Samatra-extras adds more dependencies but offers more out of the box. This includes:

- Jetty web server configuration
- Gzipping
- Logging 
- Json, XML and Templated (Mustache) responses
- Statsd metrics - web responses and jvm
- Route printing on start-up (integrates nicely with Intellij) 

## Supported platforms
- Scala 2.12
- Jetty 9.3.6.v20151106

## How to install
- sbt: 
```
resolvers += "jitpack" at "https://jitpack.io",
libraryDependencies += "com.github.springernature" % "samatra-extras" % "v1.0"	
```

You may also be interested in [samatra.g8](https://github.com/springernature/samatra.g8) which is a giter8 / sbt template for generating new samatra projects.
 
## Licensing
The MIT License (MIT)  http://opensource.org/licenses/MIT

Copyright © 2016, 2017 Springer Nature

## Maintenance
Submit issues and PR's to this github.

## How to use
The easiest way to generate a new stub Samatra-extras project is to use the [samatra.g8](https://github.com/springernature/samatra.g8) template.
