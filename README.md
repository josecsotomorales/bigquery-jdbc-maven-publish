# BigQuery JDBC Maven Publish
Publish BigQuery JDBC drivers to a private Maven repo on S3

Google issue tracker: https://issuetracker.google.com/issues/180413368


### Steps

- Download the jdbc drivers [here](https://storage.googleapis.com/simba-bq-release/jdbc/SimbaJDBCDriverforGoogleBigQuery42_1.2.23.1027.zip)
- Unzip all files under `./bigquery-jdbc`
- Adjust parameters in `build.gradle`
- Run `./gradlew publish`
