kedn
===

[![main build](https://github.com/whyrising/kedn/actions/workflows/main.yml/badge.svg)](https://github.com/whyrising/kmp-library-template/actions/workflows/main.yml)
[![Sonatype Nexus (Snapshots)](https://img.shields.io/maven-central/v/com.github.whyrising.kedn/core?color=blue&label=latest%20release&server=https%3A%2F%2Foss.sonatype.org)](http://search.maven.org/#search|ga|1|com.github.whyrising.kedn)
![GitHub](https://img.shields.io/github/license/whyrising/kedn)
[![Sonatype Nexus (Snapshots)](https://img.shields.io/nexus/s/com.github.whyrising.kedn/core?label=latest%20snapshot&server=https%3A%2F%2Foss.sonatype.org)](https://oss.sonatype.org/content/repositories/snapshots/com/github/whyrising/kedn)
[![codecov](https://codecov.io/gh/whyrising/kedn/branch/main/graph/badge.svg?token=HYVzZVdfgl)](https://codecov.io/gh/whyrising/kedn)

#### API

`fun readEdn(seq: Sequence<Char>): Any?`

`fun readEdn(edn: String): Any?`

#### Todo

* User tags are not supported yet, only built-in tags: #inst, #uuid 
