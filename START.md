#SETUP

```
gcloud organizations list
export ORGANIZATION_NAME=<ORGANIZATION NAME>

gcloud beta billing accounts list
export ADMIN_BILLING_ID=<ADMIN_BILLING ID>

export ADMIN_STORAGE_BUCKET=<ADMIN CLOUD STORAGE BUCKET>

./scripts/setup.sh --org-name ${ORGANIZATION_NAME} --billing-id ${ADMIN_BILLING_ID} --admin-gcs-bucket ${ADMIN_STORAGE_BUCKET}
```