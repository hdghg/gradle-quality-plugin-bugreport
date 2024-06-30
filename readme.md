```
$ gradlew tasks

FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring project ':lib'.
> class ru.vyarus.gradle.plugin.quality.service.TasksListenerService$Inject cannot be cast to class ru.vyarus.gradle.plugin.quality.service.TasksListenerService (ru.vyarus.gradle.plugin.quality.service.TasksListenerService$Inject is in unnamed module of loader org.gradle.internal.classloader.VisitableURLClassLoader$InstrumentingVisitableURLClassLoader @1eeea369; ru.vyarus.gradle.plugin.quality.service.TasksListenerService is in unnamed module of loader org.gradle.internal.classloader.VisitableURLClassLoader$InstrumentingVisitableURLClassLoader @1a7e32df)

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
> Get more help at https://help.gradle.org.

BUILD FAILED in 939ms
```