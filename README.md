# docker-ib-gateway

Docker container that launches the Interactive Brokers Gateway GUI inside of an X virtual frame buffer.

## Usage

    docker pull mannau/docker-ib
    docker run -e USER=<username> -e PASSWD=<password> -p 5900:5900 -p 4003:4003 -d mannau/docker-ib

Once logged in, port 4003 will be open for you to make API calls against.

## Contributing

Send a pull request!
