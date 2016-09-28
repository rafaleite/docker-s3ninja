# docker-s3ninja
Docker for S3 ninja (S3 ninja emulates the S3 API for development and testing purposes)

## Usage

### Docker

```bash
docker run --name <container-name> -v <volume-path>:/opt/s3ninja/data/s3 -p 9444:9444 -d rafaleite/s3ninja
```
