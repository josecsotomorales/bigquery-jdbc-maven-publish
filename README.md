# BigQuery JDBC Maven Publish
Publish BigQuery JDBC drivers to a private Maven repo on S3

Google issue tracker: https://issuetracker.google.com/issues/180413368


### Steps

1 - Download the jdbc drivers [here](https://storage.googleapis.com/simba-bq-release/jdbc/SimbaJDBCDriverforGoogleBigQuery42_1.2.23.1027.zip)
2 - Unzip all files under `./bigquery-jdbc`
3 - Adjust parameters in `build.gradle`
4 - Run `./gradlew publish`
