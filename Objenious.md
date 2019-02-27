# Dex pour Objenious

## Construction de l'image
Le Dockerfile officiel semble utilisable tel quel. Il suffit donc de créer l'image comme suit 

```
docker build -t eu.gcr.io/objenious-dev/dex:0.0.1 .
gcloud docker -- push eu.gcr.io/objenious-dev/dex:0.0.1
```