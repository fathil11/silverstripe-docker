# silverstripe-docker
A simple docker compose set up for development in SilverStripe 4 framework.

## Requirement
1. Docker
2. Docker Compose

## How to use
1. Clone this repository inside your SilverStripe 4 project.
2. Setup MySQL password inside dokcer-compose.yaml file.
3. Run ```docker-compose up -d``` command.
4. Don't forget to set up your database credentials in .env file matching the docker-compose.yaml file. 

## To-do
- [ ] Persistent Database.

## License
[MIT](https://choosealicense.com/licenses/mit/)
