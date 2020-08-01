





**Prerequisites:** PHP, Composer, [Okta developer account](https://developer.okta.com/)




### Configure the application

Install the project dependencies, Copy the `.env` file and fill in your Okta details:

```
composer install
cp .env.example .env
```

### Run the application

For the project directory, run:

```

php -S 127.0.0.1:8080 -t public

run in application folder
```

Then open `http://localhost:8080` and you will see the application.


