# Hello friend

My name is Tommaso and i'm a freelance data analyst from 🇮🇹.

I ❤️ defining data strategies and build cloud infrastructures for collect, store, analyse and visualize data with Google Marketing Platform and Google Cloud Platform.

Here some dashboards i made with Data Studio:
- [All space missions](https://datastudio.google.com/u/0/reporting/c013eca9-9d6f-4fbe-89cd-2e7357a48724/)
- [All LEGO minifigures](https://datastudio.google.com/u/0/reporting/747a8c57-a584-42f5-8241-31c8b65bdfb8/)

Here some datasets i published on Cloud Analytics Hub:
- [All space missions](https://console.cloud.google.com/bigquery(analyticshub:projects/927812107311/locations/eu/dataExchanges/all_space_missions_1801cd49715/listings/all_space_missions_1801cd9607d))
- [All LEGO minifigures](https://console.cloud.google.com/bigquery(analyticshub:projects/927812107311/locations/eu/dataExchanges/all_space_missions_1801cd49715/listings/lego_1801ce395ce))

---

## Build a marketing data infrastructure with Google Cloud Platform

**WARNING: This is a work in progress** 🚧



---

## Architecture

![GCP Warehouse](https://user-images.githubusercontent.com/29273232/162455675-182f614c-20f1-4388-99d5-26a87f92a7c8.png)

---

## Get start:
### Google Cloud Platform:
  - [Google Cloud overview](https://cloud.google.com/docs/overview)
  - [Google Cloud products](https://cloud.google.com/products)
  - [Google Cloud Developer cheat sheet](https://googlecloudcheatsheet.withgoogle.com/)

## How to:
### Google Tag Manager:
  - #### Client-side GTM:
    - [Create Google Tag Manager client side container](https://developers.google.com/tag-platform/tag-manager/web) 

  - #### Server-side GTM:
    - [Create Google Tag Manager server side container](https://developers.google.com/tag-platform/tag-manager/server-side#create_a_tag_manager_server_container)
    - [Automatically deploy server-side GTM on App Engine](https://developers.google.com/tag-platform/tag-manager/server-side/script-user-guide)
    - [Manually deploy server-side GTM on App Engine](https://developers.google.com/tag-platform/tag-manager/server-side/script-user-guide)
    - [Manually deploy server-side GTM on App Engine](https://www.simoahava.com/analytics/provision-server-side-tagging-application-manually/) with Simo Ahava
    - [Deploy server-side GTM on Cloud Run](https://code.markedmondson.me/gtm-serverside-cloudrun/) with Mark Edmondson
    - [Import GTM custom template](https://developers.google.com/tag-platform/tag-manager/templates#export_and_import)

### Compute engine:
  - [Create and manage Compute Engine VM instances](https://cloud.google.com/compute/docs/instances/create-start-instance)
  - [Deploy and manage AirByte on Compute Engine](https://docs.airbyte.com/deploying-airbyte/on-gcp-compute-engine)
  - [Create and manage scheduled snapshots for Persistent Disks](https://cloud.google.com/compute/docs/disks/scheduled-snapshots)

### Cloud functions:
  - [Deploy Cloud Functions](https://cloud.google.com/functions/docs/deploying)

### AppScript:
  - [Deploy AppScript functions](https://www.benlcollins.com/apps-script/google-apps-script-beginner-guide/)
 
### Cloud Scheduler:
  - [Create and manage Cloud Scheduler cron job](https://cloud.google.com/scheduler/docs/creating)

### Cloud Logging:
  - [Query Cloud Logging logs with Logs Explorer](https://cloud.google.com/logging/docs/view/logs-explorer-interface) 
  - [Create and manage Cloud Logging sinks](https://cloud.google.com/logging/docs/export/configure_export_v2)

### Pub/sub:
  - [Create and manage Cloud Pub/Sub topic](https://cloud.google.com/pubsub/docs/admin)
  - [Create and manage Cloud Pub/Sub subscription](https://cloud.google.com/pubsub/docs/create-subscription)

### Storage:
  - [Create and manage Cloud Storage bucket](https://cloud.google.com/storage/docs/creating-buckets)
  - [Create and manage Cloud Firestore database](https://cloud.google.com/firestore/docs/data-model?hl=it)
  - [Create and manage Stream Collections to BigQuery](https://firebase.google.com/products/extensions/firebase-firestore-bigquery-export)

### BigQuery:
  - [Create and manage BigQuery datasets](https://cloud.google.com/bigquery/docs/datasets)
  - [Create and manage BigQuery tables](https://cloud.google.com/bigquery/docs/tables)
  - [Create and manage BigQuery external tables](https://cloud.google.com/bigquery/external-data-sources)
  - [Query Google Analytics 4 export](https://www.ga4bigquery.com/tag/ga4-dimensions-metrics/)
  - [Query Google Analytics Universal export](https://www.ga4bigquery.com/tag/ua-dimensions-metrics/)

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
