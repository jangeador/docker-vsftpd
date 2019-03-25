# Project Title

A docker compose file to create vstfpd server using fauria/vsftpd image

## Getting Started

Install docker and docker compose. Use the included docker-compose.yml file. Rename env.sample as `.env`

### Prerequisites

You may need to change the owner and group of the home directory. You can use the following commands from within the project folder

```
find ./home -exec chgrp -h 80 {} \;
find ./home -exec chown -h 14 {} \;
```

For more information you can go to the original image repo
[https://hub.docker.com/r/fauria/vsftpd/](https://hub.docker.com/r/fauria/vsftpd/)

Credits to [fauria](https://github.com/fauria)
