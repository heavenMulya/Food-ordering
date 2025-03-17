# `Restaurant Customer Food Ordering Laravel System`

The Food Ordering System is built using the Laravel framework. This application is developed to address a longstanding challenge faced by restaurant: streamlining the ordering process that has traditionally relied on staff waiters. With this web application, customers can conveniently place orders via their mobile devices. The primary objective of this application is to facilitate swift and efficient ordering, ensuring that customers receive their orders within 10 to 15 minutes.

# `Installation`

- Clone repository
    ```
    git clone https://github.com/heavenMulya/Food-ordering
    ```

- Change directory
    ```
    cd YOUR-PATH-TO-PROJECT\Food-Ordering
    ```
    ```

- Copy sample `env` file and change configuration according to your need in ".env" file
    ```
    copy .env.example .env
    ```

- Install php & javascript libraries
    ```
    composer install
    ```
    
- Generate key
    ```
    php artisan key:generate
    ```
- Migrate database
    ```
    php artisan migrate
    ```    
- Run seeder
    ```
    php artisan db:seed
    ```
- Link local storage (Optional)
    ```
    php artisan storage:link    
    ```

# `Authentication`

- Admin
    ```
    ID: heavenadmin
    ```
    ```
    Password: 123456
    ```

- Staff
    ```
    ID: heavenjohn
    ```
    ```
    Password: 123456
    ```
