# Deploying a mongo db application using kubernetes and its components

To create kubernetes secret containing mongo db credentials (base64 encoded) to be refrenced in deployment:
> kubectl apply -f mongo-secret.yaml

To create kubernetes configmap mongo db  containing configurations to be refrenced in deployment:
> kubectl apply -f mongo-configmap.yaml

To create a mongo-db deployment
> kubectl apply -f mongo-db-deployment.yaml

To create a mongo-express deployment
> kubectl apply -f mongo-express-deployment.yaml
