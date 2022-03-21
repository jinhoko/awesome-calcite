# awesome-calcite
A curated list of awesome Apache Calcite references.

There are not much detailed references on Apache Calcite. The first thing you need to do is read through the official [docs](https://calcite.apache.org/docs/) with extreme care, and then read all contents of Calcite [javadoc](https://javadoc.io/doc/org.apache.calcite/calcite-core/latest/index.html) with patience.

## Contents

- Basics
  - Data Academia ([link](https://datacadamia.com/db/calcite/start))
  - @masayuki/calcite-code-reading ([part-1](https://medium.com/@masayuki/calcite-code-reading-part-1-4ff7cdc56959)) ([part-2](https://medium.com/@masayuki/apache-calcite-code-reading-part-2-594e8ca17acf))
- Tutorial
  - zabetak/calcite-tutorial ([link](https://github.com/zabetak/calcite-tutorial/blob/main/solution/src/main/java/com/github/zabetak/calcite/tutorial/LuceneQueryProcessor.java))
  - milinda/calcite-tutorial ([link](https://github.com/milinda/calcite-tutorial))
  - codetinkering.com ([link](https://codetinkering.com/apache-calcite-tutorial/))
- Modules
  - michaelmior/calcite-notebooks ([query-optimization](https://github.com/michaelmior/calcite-notebooks/blob/master/query-optimization.ipynb)) ([query-parsing](https://github.com/michaelmior/calcite-notebooks/blob/master/query-parsing.ipynb))
  - Schema-on-read in Calcite : Dynamic Record Type and Star Column Validation ([link](https://docs.google.com/document/d/1vCWlqRyJQCtYbtVAjGOKP-8BD4_hrhoM9-4qbdoJs6k/edit))
- Modules (query planner)
  - Assembling a query optimizer with Apache Calcite ([link](https://www.querifylabs.com/blog/assembling-a-query-optimizer-with-apache-calcite))
  - Calcite Hepplanner ([link](https://blog.knoldus.com/exploring-hepplanner-for-apache-calcite/))
  - Volcano planner analysis ([link](https://www.jianshu.com/p/9422b7b71867))
  - Examples of using volcanoplanner ([link](https://www.programcreek.com/java-api-examples/?api=org.apache.calcite.plan.volcano.VolcanoPlanner))
  - Volcanoplanner blog posting ([link](https://aaaaaaron.github.io/2020/02/09/Calcite-Volcano-Planner/))
  - Volcano optimization example on flink ([link](https://chowdera.com/2021/11/20211103041700339x.html))
- Calcite adapters
  | **Adapter**      | **Target Language**            |
  |------------------|--------------------------------|
  | Apache Cassandra | Cassandra Query Language (CQL) |
  | Apache Pig       | Pig Latin                      |
  | Apache Spark     | Java (RDD)                     |
  | Druid            | JSON                           |
  | Elasticsearch    | JSON                           |
  | JDBC             | SQL                            |
  | MongoDB          | Java                           |
  | Splunk           | SPL                            |
- Calcite in commercial systems (w.o. code)
  - MaxCompute ([link](https://www.alibabacloud.com/blog/maxcompute-query-optimization-with-calcite_595363))
  - MongoDB
  - Xtdb ([link](https://xtdb.com/blog/xtdb-sql))
- Open-source systems that embeds Apache Calcite
  - Dremio ([site](https://www.dremio.com/)) ([code](https://github.com/dremio/dremio-oss/tree/master/sabot/kernel/src/main/java/com/dremio/exec/planner/cost))
  - Apache Kylin ([site](https://kylin.apache.org/)) ([code](https://github.com/apache/kylin/tree/main/query/src/main/java/org/apache/kylin/query))
