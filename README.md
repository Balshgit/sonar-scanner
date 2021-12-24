# HOW TO RUN

MOVE your python project ./code directory

    docker-compose up

# Results

Visit [http://localhost:9000/issues](http://localhost:9000/issues)

    login: admin
    password: password

# Logs

Sonar logs can be found at log folder

# Run properties

Run properties can be changed in docker-compose command line
or something else

    -Dsonar.host.url=http://sonarqube:9000 \
    -Dsonar.jdbc.url=jdbc:h2:tcp://sonarqube/sonar \
    -Dsonar.projectKey=MyProjectKey \
    -Dsonar.projectName="My Project Name" \
    -Dsonar.projectVersion=1 \
    -Dsonar.projectBaseDir=/usr/src \
    -Dsonar.sources=.