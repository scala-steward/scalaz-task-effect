# scalaz-task-effect [![Build Status](https://travis-ci.com/ChristopherDavenport/scalaz-task-effect.svg?branch=master)](https://travis-ci.com/ChristopherDavenport/scalaz-task-effect) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.chrisdavenport/scalaz-task-effect_2.12/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.chrisdavenport/scalaz-task-effect_2.12)

Cats Effect Instances for Scalaz Concurrent Task. Trying to allow everything
to play nicely together with minimal hardships.

## Quick Start

To use scalaz-task-effect in an existing SBT project with Scala 2.11 or a later version, add the following dependency to your
`build.sbt`:

```scala
libraryDependencies += "io.chrisdavenport" %% "scalaz-task-effect" % "<version>"
```