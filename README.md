# Developing dockerPMS

### Stack Requirements

you need a copy of Docker and Python3.12 on your system to build and develop this project.

I suggest using Pycharm Professional as it should be an out-of-the-box solution.

### Structure

- `DjangoPMS/DjangoPMS` - Top Level of the program. Things like settings and Urls will be registered here


### Running the project
If you aren't using Pycharm where there is a Run Config set up to build the project.
```bash
docker-compose up                             #Start Containers
docker-compose down                           #Stop Containers
```
If you build without cache (Useful if changes in the files are made)
```bash
docker-compose up --build --force-recreate
```