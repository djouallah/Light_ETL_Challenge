# Microsoft Fabric notebook officially Support : Spark, Pandas and Pyarrow, this is just personal stuff.

# Light_ETL_Challenge
extract data fom a csv. the number of columns is higher than what's in the header, filter a subset of data and export to Delta Lake
I started with Duckdb , Polars ,Pandas,Pyspark, Pyarrow, Ibis but I expect more engines like chdb, Raft etc

the script will download 60 files, around 4 GB uncompressed

Please keep the local Path as 

for raw data : raw_landing='/lakehouse/default/Files/raw'

for Delta Python : '/lakehouse/default/Tables/'

For Fabric, it will automatically detect Spark

<img width="764" alt="image" src="https://github.com/djouallah/Light_ETL_Challenge/assets/12554469/a59da4af-da40-46a8-b3d1-c81a53813489">



<img width="866" alt="image" src="https://github.com/djouallah/Light_ETL_Challenge/assets/12554469/8d7ef13a-6ec4-40c4-b692-f414a88ef3d4">

