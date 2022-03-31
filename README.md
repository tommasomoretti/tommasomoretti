# Hello friend

My name is Tommaso and i'm a freelance data analyst from 🇮🇹.

I ❤️ defining data strategies and build cloud infrastructures for collect, store, analyse and visualize data with Google Marketing Platform and Google Cloud Platform.

---

## Build a marketing data infrastructure with Google Cloud Platform

🚧 This is a work in progress 🚧

![GCP](https://user-images.githubusercontent.com/29273232/161065600-9684e4f0-d075-4010-bc05-aef6da6b31d2.png)

---

## How to
- [Create Google Tag Manager client side container](https://developers.google.com/tag-platform/tag-manager/web) 
- [Automatically deploy server-side GTM on App Engine](https://developers.google.com/tag-platform/tag-manager/server-side)
- [Manually deploy server-side GTM on App Engine](https://www.simoahava.com/analytics/provision-server-side-tagging-application-manually/)
- [Deploying server-side GTM on Cloud Run](https://code.markedmondson.me/gtm-serverside-cloudrun/)
- [Deploying AirByte on Compute Engine](https://docs.airbyte.com/deploying-airbyte/on-gcp-compute-engine)
- [Deploying Cloud Functions](https://cloud.google.com/functions/docs/deploying)
- [Deploying AppScript functions](https://www.benlcollins.com/apps-script/google-apps-script-beginner-guide/)
- [Create Cloud Scheduler cron job](https://cloud.google.com/scheduler/docs/creating)
- [Create Cloud Pub/Sub topic]()
- [Create Cloud Logging sinks](https://cloud.google.com/logging/docs/export/configure_export_v2)
- [Create Cloud Storage bucket](https://cloud.google.com/storage/docs/creating-buckets)
- [Create Cloud Firestore database]()
- [Create BigQuery datasets](https://cloud.google.com/bigquery/docs/datasets)
- [Create BigQuery tables](https://cloud.google.com/bigquery/docs/tables)

---

## Scripts

### Google Tag Manager

- #### Client-side GTM Tags:
  - [HTTP POST/GET request sender](https://github.com/tommasomoretti/cs-http-tag): send HTTP POST and GET requests from client-side GTM to an endpoint

- #### Server-side GTM Tags:
  -  [HTTP POST/GET client](https://github.com/tommasomoretti/ss-http-client-tag): collect HTTP POST and GET requests
  -  HTTP POST/GET request sender: send HTTP POST and GET requests from server-side GTM to an endpoint
  -  [Google BigQuery data writer](https://github.com/tommasomoretti/ss-bq-tag): write data in realtime into Goole BigQuery
  -  [Google Cloud Firestore data writer](https://github.com/tommasomoretti/ss-fs-tag): write data in realtime into Google Cloud Firestore
  -  Google Cloud Storage data writer: write data in realtime into Google Cloud Storage

### Cloud Functions
  - EL from GCS to BQ: extract and load data (CSV, JSON, Avro, Parquet, ORC) scheduled/in realtime from Google Cloud Storage (with versioning) to BigQuery tables
  - Alerts: scheduled/in realtime emails alert

### App Script
  - [EL from Google Sheets to BQ](https://techandeco.medium.com/apps-script-tutorial-upload-to-a-database-sheets-bigquery-2fee3724f3ca): extract and load data scheduled/on-demand from Google Sheets to BigQuery table.
  - EL from Google Sheets to Cloud Storage: extract and load data scheduled/on-demand from Google Sheets to Gloud Storage file.

---

Reach me at: [Email](mailto:hello@tommasomoretti.com) | [Website](https://tommasomoretti.com/) | [Twitter](https://twitter.com/tommoretti88) | [Linkedin](https://www.linkedin.com/in/tommasomoretti/)
