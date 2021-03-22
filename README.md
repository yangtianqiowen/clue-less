# Clue-less
Clue-less is a simplified version of the board game, Clue. There are the nine rooms, six weapons, and six people as in the board game. It's a team Porject for Johns Hopkins University Founations of Software Engineering 

# Team Members
- Jianhui Li (jli159@jh.edu)
- Junyan Tan (jtan42@jhu.edu)
- Tianqi Yang (tyang43@jh.edu)

# Project Document
- [Project description](https://drive.google.com/drive/u/0/folders/1gE9GEivgcxBHGKukTApNiZKdNTw_P3L9)

# Related resources
https://www.youtube.com/watch?v=Q7Yc-WqwnSg

# Steps to run the application

1) Install Docker from https://www.docker.com/get-started
2) Using the following command to build and run docker
    1. git clone https://github.com/yangtianqiowen/clue-less.git
    2. cd clue-less
    3. docker-compose build
    4. docker-compose up
3) Go to http://localhost:5000/api/db/create_database to create a database 
4) Go to http://localhost:5000/api/setup_game to set up the MurderDeck in the database
5) Go to http://localhost:5001/ to play your game 
6) Use http://localhost:8080/ to set up database