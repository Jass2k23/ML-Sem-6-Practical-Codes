hadoop fs -put Desktop/input.txt inputlog.txt

hadoop jar ipCOunt.jar ipCount.ipCount inputlog.txt outputDir

hadoop fs -cat outputDir/part-r-00000
