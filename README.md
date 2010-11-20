# usage from cli :

* interactive Mode (select scala-archetype-simple and response to questions) :

      mvn archetype:generate -DarchetypeCatalog=http://nexus.scala-tools.org/content/groups/public

* non interactive / batch (change info in the last line) :

      mvn archetype:generate -B \
        -DarchetypeRepository=http://scala-tools.org/repo-releases/ \
        -DarchetypeGroupId=org.scala-tools.archetypes -DarchetypeArtifactId=scala-archetype-simple -DarchetypeVersion=1.3 \
        -DgroupId=com.company -DartifactId=project -Dversion=0.1-SNAPSHOT -Dpackage=com.company

# Changes:

## 1.3

* upgrade to scala 2.8.0 (as default)
* upgrade version of Specs and ScalaTest
* provide sample of Specs and ScalaTest runnable from maven and eclipse (at least)

Have fun!

