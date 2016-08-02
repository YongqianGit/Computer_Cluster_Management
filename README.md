# Computer_Cluster_Management
Regular data management in computer cluster.

## Introduction
Check the work directory of computer cluster. If the time stamp is longer than
120 days, the corresponding data will be purged to keep enough space for normal
functionality of work directory. Three weeks, 10 days, one week and one day
before the deadline, a file named "PURGE_NOTICE" will be generated in the user
account's main directory to notify the upcoming purging activity and remind the
user to move the data out of work directory in time.
