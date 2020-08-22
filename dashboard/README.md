# Web

> **NOTE:** If you are looking for the web application source code you will no
> longer find it in this location. The source has moved to it's own repository,
> and it can be found [here](https://github.com/sensu/web).
Web

NOTE: If you are looking for the web application source code you will no
longer find it in this location. The source has moved to it's own repository,
and it can be found here.

This package contains the assets for the web application that are embedded into
the sensu-go binary. For more on asset embedding, see
Embedding Assets in Go.

Updating
To update the set of assets embedded in to the binary, from this directory
simply run:
# NOTE: the process pulls the assets from S3 and as such will require an active
#       internet connection.
go generate ./
