
[Google Container Registry] (https://console.cloud.google.com/gcr/images/non-prod-pdz/EU/frontend-propitix?project=non-prod-pdz&authuser=1&gcrImageListsize=30) (Depending on the environment. Either non-prod or prod)

## pulling the image
```
docker pull eu.gcr.io/$environment/frontend-propitix:$tag-version
```

## Running (You can do this step without the pulling the above as it will put down if not found locally)
To run the container:
```
$ docker run -d eu.gcr.io/$environment/frontend-propitix:$tag-version
```

Default web root:
```
/usr/share/nginx/html
```

## If you require permissions to GCP, or Gitlab resources, please send an email to dare@propitix.com
