# NEXTCLOUD

## How to run this project?

To run this project inmmediatly, you only need to do the next steps:

1. Cloning this project

2. Creating three *.env* files:

    ```bash
    # nextcloud.env

    NEXTCLOUD_ADMIN_USER=your_email@mail.com
    NEXTCLOUD_ADMIN_PASSWORD=your_super_secure_password
    ```

    ```bash
    # postgresql.env

    POSTGRES_DB=nextcloud
    POSTGRES_USER=postgres
    POSTGRES_HOST=nextcloud_db:5432
    ```

    ```bash
    # pgamdin.env
    PGADMIN_DEFAULT_EMAIL=your_email@mail.com
    PGADMIN_DEFAULT_PASSWORD=your_super_secure_password
    ```

3. Running the application with:

    ```bash
    $ docker-compose up
    ```