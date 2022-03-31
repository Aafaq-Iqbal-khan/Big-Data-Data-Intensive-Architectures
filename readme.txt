Hadoop, Spark and HIVE:
I completely followed the tutorial instructions.
##############################

For Flume. 

installation guide:
https://www.tutorialspoint.com/apache_flume/apache_flume_environment.htm
https://www.tutorialspoint.com/apache_flume/apache_flume_configuration.htm

Version: FLUME 1.6.0

Instruction to run the code
the "twitter.conf" file in folder need to be moved into flume conf directory "usr/local/flume/conf"

the commands to run the flume:

1) cd $FLUME_HOME #go to flume directory

2) bin/flume-ng agent –conf ./conf/ -f conf/twitter.conf -Dflume.root.logger=DEBUG,console -n TwitterAgent



# move the streamed JSON files into project directory in HDFS and load the data in PySpark for further analysis.
################################

Jupyter notebook version: 6.2.0