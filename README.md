# ChromaWay Interview Assignment

## Notice

- Assignment was done on Ubuntu 22.04, but because of Docker it should be working on every OS. Docker engine version should be at least 19.0.5 (idealy 24.0.7 - latest version)

## Tests

By running tests, all of the listed assignments are tested

1. Create new course
2. Create new student
3. Enrolling new student to an existing course as **enrollment service administrator**
4. Enrolling new student to an existing course as **other user**
5. Counting how many students are enrolled in specific course
6. Listing all courses specific student is enrolled in

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
