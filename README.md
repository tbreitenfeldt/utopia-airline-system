# Utopia Airline System

This repository uses submodules, so to clone all included modules, you will need to provide the recursive flag when cloning.

git clone --recursive https://github.com/tbreitenfeldt/utopia-airline-system.git

## Description

This is an airline reservation system for a fictitious company (Utopia). All functionallities needed for a user to come in schedule a flight through an agent or online portal are provided, as well as the functionality for an counter agent  to manage the system in its entirety.

This project is designed to be deployed in Amazon Web Services using the cloudformation template provided to stand up an Elastic Container Service (ECS) stack, as well as to use lambda to handle the agent service. 

This project uses spring boot for the counter service, Node JS for the online service, and roobie on railes for the agent service. My SQL is used for the database, and Amazon Web Services is used as the deployment environment.

### Included Modules

- utopia-agent-microservice
- utopia-counter-microservice
- utopia-online-microservice
- utopia-react-ui
- utopia-user-microservice

