# Getting Started

## On MacOS (using Homebrew)

1. Install Redis

    ```shell
    brew install redis
    ```

2. Show Redis info

    ```shell
    brew info redis
    ```

3. Start Redis server

    ```shell
    redis-server /usr/local/etc/redis.conf
    ```

4. Start Redis server as service

    ```shell
    brew services start redis
    ```

5. Stop Redis service

    ```shell
    brew services stop redis
    ```

6. Restart Redis service

    ```shell
    brew services restart redis
    ```

## On Ubuntu

1. Download latest Redis at https://redis.io/download

2. Navigate to the containing folder and run

    ```shell
    tar xzf {redis_tar_file}
    cd {redis_folder}
    make
    ```

    Run make test (optional)

    ```shell
    make test
    ```

3. Start Redis server

    ```shell
    src/redis-server
    ```



### References:
1. [Redis download page](https://redis.io/download)
2. [Homebrew/homebrew-services](https://github.com/Homebrew/homebrew-services)
