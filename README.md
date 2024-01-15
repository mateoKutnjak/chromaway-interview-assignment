# ChromaWay Interview Assignment

## Notice

By running tests, all of the listed assignments are tested:

1. Enrolling new student to a existing course
2. Counting how many students are enrolled in specific course
3. Listing all courses specific student is enrolled in

## Instructions

### 1. Install Docker

Install Docker by following [commands in step 1](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04#step-1-installing-docker)

### 2. Install Docker compose

Install docker-compose by following [commands in step 1](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04#step-1-installing-docker-compose)

### 3. Clone git repository

- Clone git repository with assignment code by running `https://github.com/mateoKutnjak/chromaway-interview-assignment.git`
- Position yourself inside the root of the project with command `cd chromaway-interview-assignment`

### 4. Run Chromia node and test

- In one terminal run `UID="$(id -u)" GID="$(id -g)" docker compose run chromia chr node start`
- In second terminal run `UID="$(id -u)" GID="$(id -g)" docker compose run chromia chr test`

