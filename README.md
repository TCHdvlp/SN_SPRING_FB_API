# SN_SPRING_FB_API
Spring courses for ScholaNova

## Build a Football stats API

### Common rules :

* 1 branch per step
* Peer review after each commit and before each push
* Students may display their codes at any moment (any moment is decided by... me)
* You can ask me anything as long as you respect those points :
    - Explain clearly your intention
    - Explain what you have done
    - Explain what are your expectations
    - Explain what does not work
* There is no competition (yet). This is not a race, everybody must code.

### Create a repository to share your code

## Run a Hellow World SpringBoot application

### Create a REST API where the user can list football teams enlisted in 2019 Champions league

Create an account on https://www.football-data.org/ 
Use the football-data API as your data source
Do not store your API key in the repository !
Make a README so I can run your project localy
Use a proper logger to log activity on your server

1. List football teams engaged in the 2019 CL on your endpoint `/teams`
The representation of a team must be
    - it's ID
    - it's name
    - it's abreviation
    - it's country

**Make a step-by-step design and feel free to validate each steps with me**

2. The user can see a specific team if he has its ID `/teams/1234` 
Only teams that have participated in this competition can be displayed !

3. Sort teams with the request param `sort`
Sort teams by name, descending
Sort teams by year of creation, oldest first

4. List players of a team on `/teams/{team_id}/players`

* To go further...

Use a correlation ID to link logs together
Make your API run on port 5001
Perform test mocking football-data API



