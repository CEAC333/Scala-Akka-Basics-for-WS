# Scala-Akka-Basics-for-WS

# Installation 
### Installing IntelliJ for Scala Development
https://www.youtube.com/watch?v=A2c4mDDn-QM
### Installing Postman
https://www.getpostman.com/apps

# Useful commands
#### Inside the Project Folder with the Terminal:

Run Project
```
sbt run
```
Run Tests
```
sbt test
```

# Documentation Resources & Repos
- General                                     - https://akka.io/docs/
- Actors Become/Unbecome                      - https://doc.akka.io/docs/akka/snapshot/actors.html?language=scala#Become_Unbecome

- Cassandra Plugins for Akka Persistence      - https://github.com/krasserm/akka-persistence-cassandra 
- Akka Persistence JDBC                       - https://github.com/dnvriend/akka-persistence-jdbc
- Persistency Query                           - https://doc.akka.io/docs/akka/2.4.0/scala/persistence-query.html
- Persistency Query for LevelDB               - https://doc.akka.io/docs/akka/2.4.0/scala/persistence-query-leveldb.html#persistence-query-leveldb-scala

- Cluster Specification                       - https://doc.akka.io/docs/akka/2.4.0/common/cluster.html
- Cluster Singleton                           - https://doc.akka.io/docs/akka/2.4.0/scala/cluster-singleton.html
- Cluster Sharding                            - https://doc.akka.io/docs/akka/2.4.0/scala/cluster-sharding.html

- Testing Actor Systems                       - https://doc.akka.io/docs/akka/2.4.0/scala/testing.html
- Multi Node Testing                          - https://doc.akka.io/docs/akka/2.4.0/dev/multi-node-testing.html

- Stream Introduction                         - https://doc.akka.io/docs/akka-stream-and-http-experimental/1.0/scala/stream-introduction.html
- Stream Quickstart                           - https://doc.akka.io/docs/akka-stream-and-http-experimental/1.0/scala/stream-quickstart.html
- Testing Streams                             - https://doc.akka.io/docs/akka-stream-and-http-experimental/1.0/scala/stream-testkit.html
- Stream Graphs                               - https://doc.akka.io/docs/akka/current/stream/stream-graphs.html?language=scala
- Stream IO                                   - https://doc.akka.io/docs/akka-stream-and-http-experimental/1.0/scala/stream-io.html

- Balancing Workload Across Nodes with Akka 2 - http://letitcrash.com/post/29044669086/balancing-workload-across-nodes-with-akka-2
- Throttling Messages in Akka 2               - http://letitcrash.com/post/28901663062/throttling-messages-in-akka-2
- Shutdown Patterns in Akka 2                 - http://letitcrash.com/post/30165507578/shutdown-patterns-in-akka-2
- An Akka 2 Terminator                        - http://letitcrash.com/post/29773618510/an-akka-2-terminator

# Reactive Manifesto
### + Responsive
### + Resilient
### + Elastic
### + Message Driven

# Related Concepts

### Latency - Percentiles (Table)
![Latency - Percentiles (Table)](https://lh6.googleusercontent.com/fY4Lijccstukuerm7YTsNqso8F4e-8_EBMWG7ub01ui6PjxGhFKVTs6mFjSlItk9-TaDiwQutnmESRbchuuF=w2870-h1442-rw)

### Responsive
![Responsive](https://lh3.googleusercontent.com/-9ctjeTJKxfg1lwCcFcoleQeHp_-HvEprChxX9i_I5QtDVizwIYAsnprwF3YzpPglrVIKDBeRkCAU815ulXMUiHT_e4IYcuUhr6XcizjeRwnedI6unwe-LP7tbPzQVKOYhRyAzRMJVb_GBOhsH2EvACzCkkF6JNwKT9SRhKLLXYycnQLb4kj2H3hr017AUQ3SqpHryO71qbtlCJHwy5T--eaAckbAz_Jm1QOgIfYestn3rclfSZXLJiX-itpsmiV_tPAmyV0tLkieMBe-2eQFxkVJBbizslcGvTnw4GhV084hspZQ5Hg27VPFdIfQpQ4rrqB4nmbvU0Z8STdlZW4tpsBcXEC3VWFkKZUBv16hIU-JDkVAypgpLjinWxBjVKCbAu3ImXPaJC8hK4-sYCffA1t_oqkzYA2D_xyKVB0jb1fotXm5UiqS9cLrlEtWwFu2k403SBBor_OjElMTjUSJ5XuZrv4YeMItWd5dC_TNUasARH6_drblu80fn6xIyzC6uaQCgXCVnCkUB-YZ8J_ESmHPRJTkQgkO4JHynhT-OC4CClFfbUV2J1wTmEKMEnP=w2880-h1652
)

### Replication
![Replication](
https://lh3.googleusercontent.com/NTmftZNHHFLjrbysOa6RozLNdnsT_uZR3J7PgU-P4z1-Aj4ZMcx37XEbAHAr2lnvihstvPMfKXl0B95arV9JLtJVIo9F7ZLpDNxeaUJj5hoQrq0H4hXegTIXP7TR7kcwXxfvMOvHcz5CnapGkNiKjpng2zZTYKd980Rs3pAeL1CD9cFR5zWqMhSRLvfIIYCZ7tGN9YLFDog6HbTxn8_FHMKxBDvS6aCxTOc1BsuTGQCg8RAq7zBeSiJSX7sol3Pj11AY0Wk0nQhirdyp1G5Oy5KSbRSDIgFONXLQvCrKioyZaZkqJnBJHCWdn0Zri5AyDWNDUOphoUgqohajg792PIG_hp2izR6il4Cl8h8EDF-Dbqp7aKfPzS1k6LgyEpunEqNfII73hksZGc7GzJpADngWF41w_9XgaclR6i40K-DeDuw6Im-e2yQX4I4bFNP21pK6xP3A2QpJa1-adrK1X_kRcNs1NWAb5noqwLdXxBwOdSlwvtDrNzy50xc42o5cfIiy6VgW_DQ27ildoBy3ixf0JimppFSaqfARcGeqPO5dVM1B2qhUV3JChFuax9Gm=w2880-h1652
)

### Scale
![Scale](
https://lh3.googleusercontent.com/nA_rt-fvfKIX0PmJxLTIoLDOV-jCohJph5SgxSprTiU5-2A2nmVlGLEWP6kJHrjzdsHMJJ5x6YI_XLvaH2fLLUTrMdEK4_8guKPIeoceuGmSXphS7prDgmFg3RswhOx3O7_c-EeAApn0XZMf3UdiMX5WHD66QeJJD9j2f4obYxjVNt3qzHiE7lYotBhsAMG7RIisDXFWeY_ZLWBBTcfoAd84N-NHilh5RFYVhVgaThMTpohd7ayNEA_jsRdH6_eUVXjnjKmyXE8GdbqzCh-MMGfunFoqph8fzVfM-57bF9anEVplq_e9Op-0TPZqCesfCm-0q5Ft92oMkxUeQySSdM3geBziF_oUL2RJ04wiYwwcmH1spoaR2kH6_ToHOwMG8H8T-afn9X_QL_wNq7Sq81UcHpqyo0Nnmn2anxfdfs2b_exiOUXTrlsMiqi9gBuL_CEC1JWVUeaETWqU5czNyGn5iedCUU5c_L5oxy59PGmjBpdH4yeocTyhxwQBJZuMF58-UGmY2FfPqnMpMAfg5JKlSU5a9sSHiBN3IUawG565UwuUlaotd8CmqWQcpHyA=w2880-h1652
)

### Event-Driven
![Event-Driven](
https://lh3.googleusercontent.com/3_7YiuvPu7vuUZrjgk1S1hxOIb267mhDg59yxEwW5clh6CVekkfR_qTqxSx8JjZjn_Qqe_-Ojg_W74O6jUlkdiLbl6KlW4WXtfrC5QFUgEoPDEoshN1ViI56j-W18fO_m87VPRQh1fYU-0S5VY1VypPZRUD7m4F62WN5HGRxgR71_YAg9mCttqjWHnPzEz9UcHFGeJIgNKszFwOVJTbPpw_UmgiZZapqat3AtWHYDexYFuC0v87gCRRn0FPMapeIKuiawxirreQJlQckrXMPhPjc37OzDZA5ypoqzpV6e2aIx6EjnBW9X4Q_KTSvzSLioK6374NK11q0IupnePo-b2-SnDwgZqF7KvZtyBUHg56jrJztvOdpGS-pFqV4eGX2NyeJhTbMGk4tx3HCf9uE2GGD291lX9wXYiUqjQk3EetufJ09no-p4k0_7oQvzDiaKs4kVfxBjGsZOxavwig5YInnJw-KHRyTVR0kr-0oN4hZrujBjtRtwaNQ7jTqe8jaqZpQgmF9ONZ8vGp7Ty10cfdoixI8AWQg6phpgI1Y0Do3pR-JaKdDKIWzSh3P7s39=w2880-h1652
)

### Publish Suscribe Model
![Publish Suscribe Model](
https://lh3.googleusercontent.com/wCywzsdlzfaZzu2sg9BCWI-7C4b1S6M2w0IyTiX6E4QYV57CZYNbNLLmPm1NvY-vCoJZvktjK1BADsheoRpbwZvwc-ZEScpRVDNXapjH3o82_jWYoS78D329_iXQrREQw2v7aq5gxY4N8pN0-3KFV03xMxiJjCdA28L36NNR7_4uJVhXQaEwMfkpShXNXa96AvPGIHk_GlTzpVvNxD2fK-uaiCCUaLoH4OB6KJ2M9AxAwBdfhfU4NhT_CRktAq-hHfVA5faqQPSoRhVQ4ToJyKNu5LOg-vQXiVFuUG5X_Qgr8Jdt-rdCmGNRQksIcwzj3NbH3xCYTSElLKBoBC_903oEa695OVrpbvuYeYk6J11tWp_XUi9DvPsZa_wKhD37iBWntgViT3CNJi9CaB1nwblh4O8oB3Ky0iuO6pO7aNrGEDlIzTCGBiUjRN9Hr-BTED0xNhtIR8_55vHsiYCuBhBbY14eAYaevwk4_mfvT_dqZ1ahCa2yVYcuLebtziua1cwlnKfhsVfvdNjSVWOLJMa61bb2wU9DtRsPJxhrkfi926n-e-zFXwiqYceCV-5g=w2880-h1652
)

# Testing

- Performace Testing - https://gatling.io/


# Books 
- Building Applications in Scala (2016) - http://sd.blackball.lv/library/Building_Applications_with_Scala_(2016).pdf
- Scala High Performance Programming - http://ebook.pldworld.com/_eBook/-Packt%20Publishing%20Limited-/9781786466044-SCALA_HIGH_PERFORMANCE_PROGRAMMING.pdf

# References
- https://www.udemy.com/learning-path-akka-building-applications-and-microservices

