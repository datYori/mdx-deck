|               Name              |    Operator    |  Host type |    Base Image    |                           Tag                          |
|:-------------------------------:|:--------------:|:----------:|:----------------:|:------------------------------------------------------:|
|      CI Engine Tier1 Tests      |     Jenkins    | OnPrem/EC2 | raw-scala-runner | buster_jdk-11.0.16.8_hadoop3.3.0_scala2.12.15_sbt1.6.2 |
|   CI Engine Tier2 Scala Tests   |     Jenkins    | OnPrem/EC2 | raw-scala-runner | buster_jdk-11.0.16.8_hadoop3.3.0_scala2.12.15_sbt1.6.2 |
|            CI Repose            |     Jenkins    | OnPrem/EC2 | raw-scala-runner | buster_jdk-11.0.16.8_hadoop3.3.0_scala2.12.15_sbt1.6.2 |
| CI Truffle Executor Scala Tests |     Jenkins    | OnPrem/EC2 | raw-scala-runner |       ol8_java17_gvm22.3.0_scala2.12.15_sbt1.6.2       |
|            Docs CI/CD           | Github Actions |   OnPrem   |     raw-docs     |                         16-slim                        |