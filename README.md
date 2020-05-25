APACHE SPARK: Por padrão, persiste os dados apenas em memória.
Estrutura principal de dados: Resilient Distributed Dataset (RDD).
Opera em modos standalone e modo cluster (compatível com YARN).
Spark pode ser até 100x mais rápido que operação em batch do hadoop - verificar capacidade de memória disp.
Spark define automaticamente o número de execuções paralelas. Podemos em uma transformação customizar a quantidade de execuções paralelas.
Spark Streaming: micro-batches.
Python: pyspark

  Core: gestão de recursos, tolerância a falha
  SQL: querys por linguagem SQL com suporte a Hive
  Streaming: processamento real time
  Mllib: library para ML
  GraphX: library de processamento de grafos

RDD - Resilient Distributed Datasets

  Dados imutáveis distribuídos pelos clusters: Operações sobre RDD criam novo RDD. Passa a trabalhar com outro RDD após transformação.
  Em RAM podendo ser persistido em disco
  

