# spark_streaming
# reading spark streaming from sockets, conversion of batch code to streaming code
Tutorial on spark streaming

Main Concepts : Spark streaming, docker, socket, batch, stage, ncat, 
First a batch version (not committed here) and finally a streaming version of this code.


Docker container name = ed-pyspark-jupyter-lab
ab22f38285d5
easewithdata/pyspark-jupyter-lab:latest
4040:4040⁠
8888:8888⁠
25/05/26 16:32:21 WARN ResolveWriteToStream: Temporary checkpoint location created which is deleted normally when the query didn't fail: /tmp/temporary-d34f1c26-8b66-4537-8781-b348f94b2017. If it's required to delete it under any circumstances, please set spark.sql.streaming.forceDeleteTempCheckpointLocation to true. Important to know deleting temp checkpoint folder is best effort.


25/05/26 16:32:22 WARN ResolveWriteToStream: spark.sql.adaptive.enabled is not supported in streaming DataFrames/Datasets and will be disabled.


-------------------------------------------


Batch: 0


-------------------------------------------


+----+---+


|word|cnt|


+----+---+


+----+---+






[Stage 9:=====> (18 + 8) / 200]




[Stage 9:======> (24 + 8) / 200]




[Stage 9:=========> (35 + 8) / 200]




[Stage 9:============> (44 + 8) / 200]




[Stage 9:===============> (54 + 8) / 200]




[Stage 9:==================> (67 + 8) / 200]




[Stage 9:======================> (80 + 8) / 200]


