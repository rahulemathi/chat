
# Chat

This Project realtime chat is made using laravel with Chatify and pusher





## Video
[click here for video](https://www.youtube.com/watch?v=JZO7Dfqtb6M)

## Run Locally

Clone the project

```bash
    git clone https://github.com/rahulemathi/chat.git
```

Go to the project directory

```bash
    cd chat
```

Install composer update

```bash
    composer install
```

Install npm packages

```bash
    npm install
```

rename the .env.example file to .env file

```bash
    mv .env.example .env
```

generate key

```bash
    php artisan key:generate
```

make migration

```bash
    php artisan migrate
```

make factories
```bash
    php artisan db:seed
```

Start the serve

```bash
    php artisan serve
```

Start the npm 
```bash
    npm run dev
```

Link the Storage

```bash
php artisan storage:link
```

The Default passwrod for the factory generated accounts is password

make sure that your APP_URL = http://127.0.0.1:8000 to set the images working
## Authors

- [@rahulemathi](https://github.com/rahulemathi)

# Make sure the pusher credientails are added in env file