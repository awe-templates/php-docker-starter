# php-docker-starter

PHP Docker starter template with serversideup/php images for PHP apps (*Laravel compatiable*).

> [!NOTE]  
> This setup may not work with your PHP apps directly. According to your app, you may need to configure with entrypoint. For example in Laravel apps, you need to consider `public` folder as document root. It dependds on your app/framework configurqation, you may need to change the `Dockerfile` or `docker-compose.yml` file.

## Usage

### 1. Add the following variables to your `.env` file

Copy [.env.example](./.env.example) file and rename as `.env`.

### 2. Run the following command

```bash
docker-compose up -d
```

When you need install specific PHP extensions, check [Dockerfile](./Dockerfile#L10).
