# php-docker-starter

PHP Docker starter with serversideup/php images for [Laravel](https://laravel.com/) apps.

## Usage

### 1. Add the following variables to your `.env` file

Copy [.env.example](./.env.example) file and rename as `.env`.

### 2. Run the following command

```bash
docker-compose up -d
```

When you need install specific PHP extensions, check [Dockerfile](./Dockerfile#L10).
