Sample application for https://github.com/peh/grails-babel-asset-pipeline/issues/14

How to see the error:

1. Checkout the project
2. Call "grailsw war"
3. If you do not get the error, repeat "grails war" until you see it.


```
$ grails war
Using grailsw
| Compiling 10 source files

| Processing File 1 of 26 - apple-touch-icon-retina.png
| Processing File 4 of 26 - grails_logo.png
| Processing File 25 of 26 - jquery/jquery-1.11.1.min.js
Feb 10, 2017 4:34:14 PM java_util_logging_Logger$info$1 call
INFORMATION: [  Envjs/1.6 (Rhino; U; Mac OS X x86_64 10.12.3; en-US; rv:1.7.0.rc2) Resig/20070309 PilotFish/1.2.13  ]
Feb 10, 2017 4:34:14 PM java_util_logging_Logger$info$0 call
INFORMATION: [  Envjs/1.6 (Rhino; U; Mac OS X x86_64 10.12.3; en-US; rv:1.7.0.rc2) Resig/20070309 PilotFish/1.2.13  ]
Feb 10, 2017 4:34:14 PM java_util_logging_Logger$info$0 call
INFORMATION: [  Envjs/1.6 (Rhino; U; Mac OS X x86_64 10.12.3; en-US; rv:1.7.0.rc2) Resig/20070309 PilotFish/1.2.13  ]
Feb 10, 2017 4:34:14 PM java_util_logging_Logger$info$0 call
| Done creating WAR target/sample_babel_issue_14-0.1.war

$ grails war
| Processing File 19 of 26 - application.css
| Processing File 26 of 26 - jquery/jquery-1.11.1.min.map
Feb 10, 2017 4:34:36 PM java_util_logging_Logger$info$0 call
INFORMATION: [  Envjs/1.6 (Rhino; U; Mac OS X x86_64 10.12.3; en-US; rv:1.7.0.rc2) Resig/20070309 PilotFish/1.2.13  ]
Feb 10, 2017 4:34:36 PM java_util_logging_Logger$info$0 call
INFORMATION: [  Envjs/1.6 (Rhino; U; Mac OS X x86_64 10.12.3; en-US; rv:1.7.0.rc2) Resig/20070309 PilotFish/1.2.13  ]
Feb 10, 2017 4:34:36 PM java_util_logging_Logger$info$0 call
| Processing File 26 of 26 - jquery/jquery-1.11.1.min.map.
| Error WAR packaging error: TypeError: org.mozilla.javascript.Undefined@18a12eba is not a function, it is undefined. (file:/Users/roos/.m2/repository/net/errbuddy/plugins/babel-asset-pipeline/1.4.5/babel-asset-pipeline-1.4.5.jar!/asset/pipeline/babel/env.rhino.js#2346
```
