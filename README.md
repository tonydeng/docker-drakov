# Drakov Docker image

Run a  api-blueprint Document application in docker.

> Document your API in the API blueprint format, and Drakov mocks your routes and sends the responses defined in the api spec.

See more about the application: https://github.com/Aconex/drakov

## Docker Run Example


### Run Default Example

```bash
docker run -it -p 4007:4007 wolfdeng/docker-drakov
```

### Select API Document

```bash
docker run -it -v $API_DIR:/etc/secrets -p 4007:4007 wolfdeng/docker-drakov
```

## API-Blueprint Example

[API Blueprint Example](example/api.md)
