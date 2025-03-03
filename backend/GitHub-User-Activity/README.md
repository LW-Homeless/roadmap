Sample solution for the [Github-user-activity](https://roadmap.sh/projects/github-user-activity) challenge from [roadmap.sh](https://roadmap.sh)

# GitHub User Activity  
In this project, you will build a simple command line interface (CLI) to fetch the recent activity of a GitHub user and display it in the terminal. This project will help you practice your programming skills, including working with APIs, handling JSON data, and building a simple CLI application.

# Requirements  
The application should run from the command line, accept the GitHub username as an argument, fetch the user's recent activity using the GitHub API, and display it in the terminal. The user should be able to:

- Provide the GitHub username as an argument when running the CLI.
`github-activity <username>`

- Fetch the recent activity of the specified GitHub user using the GitHub API. You can use the following endpoint to fetch the user's activity:  
 `https://api.github.com/users/<username>/events`  
 
  `Example: https://api.github.com/users/kamranahmedse/events` 

- Display the fetched activity in the terminal  

	**Output:**  
	*Pushed 3 commits to kamranahmedse/developer-roadmap  
	Opened a new issue in kamranahmedse/developer-roadmap  
	Starred kamranahmedse/developer-roadmap*  
	...

# Solution
Programming Language	:	 Python 3.11.3  
Type of programming	:	 Object-oriented programming (OOP)  
Design pattern	:	 Behavioral design pattern **Command**  

The Command design pattern has the following structure.

![image](https://github.com/user-attachments/assets/73d2fcac-e4fe-40b5-afec-f5c7f556546a)

# How to use
`python github-activity <username>`

![video](https://github.com/LW-Homeless/roadmap/blob/main/backend/GitHub-User-Activity/video.gif)
