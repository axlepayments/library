# Axle Library

## Forked Project
- This project is forked so we want to mostly edit the files in `/styles` to prevent conflicts

## Deployment
- When deploying for the first time, we need to create the `.env` file set `GOOGLE_APPLICATION_CREDENTIALS=parse_json`
  and `GOOGLE_APPLICATION_JSON={json_from_gcloud}`
- We set up a Google Cloud project called `axle-library`
- Run this script to deploy: `gcloud app deploy --project=axle-library`
