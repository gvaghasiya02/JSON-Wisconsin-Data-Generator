Steps:
> export DATAGEN_HOME=$HOME/datagen

> cd $DATAGEN_HOME

> mvn clean package 

> $DATAGEN_HOME/scripts/run_datagen.sh workload=wisconsin_1GB_std_zero_fixedLength_noBigObject.json writer=couchbase(default = file)
