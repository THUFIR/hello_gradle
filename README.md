# hello_gradle
#
#
#




thufir@mordor:~/java/hello_gradle$ 
thufir@mordor:~/java/hello_gradle$ gradle clean;gradle build;java -jar build/libs/hello_gradle.jar 
:clean

BUILD SUCCESSFUL

Total time: 4.508 secs
:compileJava
:processResources UP-TO-DATE
:classes
:jar
:assemble
:compileTestJava
:processTestResources UP-TO-DATE
:testClasses
:test

net.bounceme.mordor.hello.TestJunit > testPrintMessage STANDARD_OUT
    Hello World

net.bounceme.mordor.hello.TestJunit > testPrintMessage PASSED
:check
:build

BUILD SUCCESSFUL

Total time: 5.825 secs
Hello World!
thufir@mordor:~/java/hello_gradle$ 

