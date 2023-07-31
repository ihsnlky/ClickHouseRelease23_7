# ClickHouse Release 23.7 New Features

## Prerequisites: 
You need to install "Docker Desktop" and "docker-compose" before testing.

## Steps
* Clone the repository to your local:
```bash
git clone https://github.com/ihsnlky/ClickHouseRelease23_7.git
```
* Go to the repository directory:
```bash
cd ClickHouseRelease23_7
 ```
 * Run the following command to create a Docker container:
 ```bash
 docker-compose up -d
 ```
* After installation, you should see the following nodes on your Docker Desktop screen:
![Screenshot 2023-07-31 at 21 24 27](https://github.com/ihsnlky/ClickHouseRelease23_7/assets/110613255/543ceb05-e532-409f-ad8e-2aa5e8b862e9)



* **clickhouse01**, **clickhouse02** and **clickhouse03** are on 23.7 version, and **clickhouse04** is on 23.6 which is an older version.
* **clickhouse01**, **clickhouse02** and **clickhouse03** are configured as replication ready.

* You can use the sample dataset (**uk_price_paid**) for testing purposes.
The installation of this dataset is explained as follows:
https://clickhouse.com/docs/en/getting-started/example-datasets/uk-price-paid
