# Build and deploy

Command to build the application. PLease remember to change the project name and application name
```
gcloud builds submit --tag gcr.io/grd-streamlit/grd-streamlit-test  --project=grd-streamlit
```

Command to deploy the application
```
gcloud run deploy --image gcr.io/grd-streamlit/grd-streamlit-test --platform managed  --project=grd-streamlit --allow-unauthenticated
```

https://share.streamlit.io/gr3gorycode/grd_streamlit/main/app2.py
