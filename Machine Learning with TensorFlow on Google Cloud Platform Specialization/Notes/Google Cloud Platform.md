# Google Cloud Platform

## Compute

### Compute Engine

#### start up jupyter notebook

- nohup jupyter notebook &
- nohup jupyter-notebook --no-browser --port=5213 > jupyter.log &

### Cloud Storage

#### copy file

gsutil cp \<source file\> \<target file\>

1. from Google Storage to Instance

   gsutil cp example gs://zintrulcre-storage

#### publish files to web

gsutil acl ch -u AllUsers:R gs://<BUCKET-NAME>/<FILE-NAME>





## Networking

### Network Segment

- UniMelb: 128.250.0.0/16

- Unilodge: 103.44.0.0/16

