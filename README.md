# usage from cli :

* interactive Mode (select scala-archetype-simple and response to questions) :

        mvn archetype:generate

* non interactive / batch (change info in the last line) :

        mvn archetype:generate -B \
          -DarchetypeGroupId=net.alchim31.maven -DarchetypeArtifactId=scala-archetype-simple -DarchetypeVersion=1.5 \
          -DgroupId=com.company -DartifactId=project -Dversion=0.1-SNAPSHOT -Dpackage=com.company


# Changes:

## 1.5

* upgrade of scala 2.10.0 
* upgrade version of Specs(2), ScalaTest, Surefire, scala-maven-plugin

## 1.4

* move to sonatype for hosting
* change groupId to net.alchim31.maven
* upgrade version of scala to 2.9.2, version of JUnit, Specs(2) and ScalaTest
        
## 1.3

* upgrade to scala 2.8.0 (as default)
* upgrade version of Specs and ScalaTest
* provide sample of Specs and ScalaTest runnable from maven and eclipse (at least)

Have fun!

