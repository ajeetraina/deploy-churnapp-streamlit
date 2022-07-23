# Develop and Deploy a Customer Churn App using Streamlit and Docker


## Clone the repository

```
git clone <repo-name>
```

## Build the application


```
docker build -t customer_churn .
```


## Running the app

```
docker run -d -p 8501:8501 customer_chrun
29bf4230fbd48ab17b79a54793d335c7a330224c2e435dcad9e746363bf4d14f
```


```
% docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                    NAMES
29bf4230fbd4  customer_churn   "streamlit run strea…"   3 seconds ago   Up 2 seconds   0.0.0.0:8501->8501/tcp   brave_haibt
```

<img width="1402" alt="image" src="https://user-images.githubusercontent.com/313480/180604352-3a67e3e4-203e-47f9-9e36-403932868213.png">

