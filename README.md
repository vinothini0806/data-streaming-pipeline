# Data-Streaming-Pipeline

Implementation to building a highly scalable data streaming pipeline in Python modified based on [here](https://github.com/iam-mhaseeb/Data-Streaming-Pipeline)


Installation
-----------
1. Install the Redis and run it locally.
2. Clone the repository.

    ```
    git clone https://github.com/iam-mhaseeb/Data-Streaming-Pipeline.git
    ```
    
2. Install the requirements.

    ```
    pip install -r requirements.txt
    ```

3. You are good to go!

Quick start
-----------

1. Start the producer `quotes_spider`:
    ```
    cd producer
    scrapy crawl quotes
    ```
2. Start the consumer `quotes_consumer`:
    ```
    cd consumer
    python quotes_consumer.py
    ```
3. See data flowing between pipeline as soon as data is generated from the producer.





