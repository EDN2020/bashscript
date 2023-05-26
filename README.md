support-tf( master 🀄︎)🀀🀁🀂🀃 ~ str="cluster-etl-hive/green/backend.tf"  (This part of code defines a str variable
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo $str (here we are reading variable)
cluster-etl-hive/green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo green/backend.tf
green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str#cluster-etl-hive/} (this is stripe certian parts for the output. # is used to stripe from the front. so we are sriping off cluster-etl-hive)
green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str%.tf} ) ( just like # above % is used to stripe the back part of the output)
cluster-etl-hive/green/backend
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str}
cluster-etl-hive/green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str/green/blue} (here we are adding the word green)
cluster-etl-hive/blue/backend.tff
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str/-/# } (here we are replcaing the first - with # making  use of a signle  forward slash /) 
cluster#etl-hive/green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str//-/#} (here we are replacing all the - with # making use of double forward slash //)
cluster#etl#hive/green/backend.tf
support-tf( master 🀄︎)🀀🀁🀂🀃 ~ echo ${str//e/#} ( here we are replacing all e with # making used on double forward slash //)
clust#r-#tl-hiv#/gr##n/back#nd.tf

