# Setting Password

1. Open redis.conf for editting

    a. On MacOS:

    ```shell
    vim /usr/local/etc/redis.conf
    ```

    b. On Linux: navigate to redis folder and run

    ```shell
    vim redis.conf
    ```

2. Uncomment requirepass line and replace new passphare

    ```
    requirepass 123456
    ```

3. Restart Redis server

4. Start redis-cli with passphare

    a. On MacOS:

    ```shell
    redis-cli -a 123456
    ```

    or

    ```shell
    redis-cli
    ```

    then

    ```shell
    AUTH 123456
    ```

    b. On Linux: navigate to Redis folder

    ```shell
    src/redis-cli -a 123456
    ```

    or

    ```shell
    src/redis-cli
    ```

    then

    ```shell
    AUTH 123456
    ```



### References:
1. [Redis documentation](https://redis.io/documentation)
