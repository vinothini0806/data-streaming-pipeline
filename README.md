# Data-Streaming-Pipeline

Implementation to building a highly scalable data streaming pipeline in Python modified based on [here](https://github.com/iam-mhaseeb/Data-Streaming-Pipeline)


Requirements
-----------
1. Install the Redis.
2. Install the the required libraries
    
    ```
    pip install -r requirements.txt
    ```



How to run the code?
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





