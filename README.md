# ThumborMongoDocker
Thumbor6 with upload and download image by Mongo GridFS

Base from https://github.com/APSL/docker-thumbor

Thumbor code https://github.com/thumbor/thumbor

## Thumbor compatible with mongo GridFS Test with mongo 3.4
MongoDB https://www.mongodb.com/download-center

# https://github.com/lionants02/ThumborMongoShardingCompose

### Thumbor compatible with mongoDB GridFS
### You can connect to mongoDB with default setting.

pull by `docker pull lionants02/thumbormongodocker:1.0`

## Parameter env docker
```
MONGO_STORAGE_SERVER_HOST         =     localhost    #host MongoDB
ENV MONGO_STORAGE_SERVER_PORT     =     27017        #27017 is default port
ENV MONGO_STORAGE_SERVER_DB       =     picture      #database name autocreate
ENV MONGO_STORAGE_SERVER_COLLECTION =   files        #collection autocreate
ENV UPLOAD_ENABLED                =     True         #enable upload
ENV UPLOAD_PUT_ALLOWED            =     True         #enable put update file
```

Test get image by http://<host-thumbor>/unsafe/smart/1c6d2372252f4e18a54112a589017441

`1c6d2372252f4e18a54112a589017441` is file parth

Read: https://github.com/lionants02/thumbor_mongodb/tree/Workwith_tc_mongodb


GitHub https://github.com/lionants02/ThumborMongoDocker

Docker: https://hub.docker.com/r/lionants02/thumbormongodocker/
