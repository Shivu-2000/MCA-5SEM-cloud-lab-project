<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Shivu-2000/MCA-5SEM-cloud-lab-project">
    <img src="![logo](https://github.com/nansari-0134/MCA-5SEM-cloud-lab-project/assets/85431837/15bf9799-8db4-449d-963d-cbdccb57bda8)" alt="Logo" width="80"  />
  </a>

  <h3 align="center">Quiz App in C</h3>

  <p align="center">
    A C program to demonstrate Building of Quiz App
    <br />
    <br />
    <br />
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a C programming project. In this We have designed the quiz competition using C. the project is console based. We have divided the project in different modules that are listed below to perform a specific task and to provide a better understanding of  the code.</br>
The module used in the code are: 

<ol>

<li> int display_record():shows the highest cash prize won by a particular user </li>
<li> int update_recod():to reset the highest score/cash prize to default </li>
<li>int need_me(): help menu with game summary and rules </li>
<li>int change_record():adds the current cash prize won to the previous one upon giving the right answer to a question.</li>

</ol>

In this quiz we store the player name, view highest score and even can reset it or update it. </br>

The quiz is divided into 2 round in first round player is supposed to give 3 correct answer to be eligible to enter the 2 round where for each round he/she will be rewarded 100000.000 rupee. If the user doesn’t pass the 1 round he/she is not permitted to enter the 2 round. </br>

The game closures when the client's monetary reward stacks up to $1 million. For each inquiry posed, there are 4 choices, specifically A, B, C and D. There are no regrettable markings, so the client's amassed greenbacks will not be deducted for wrong responses to the inquiries.</br>



### Methodology

The methods used in this minor project are FILE HANDLING for storing the information about the players and the highest score achieved. We haven't used it to store the question used in quiz.</br>

We have also used the concept of modules also known as functions to do the specific task separately. The concept of decision making is implemented with the help of if-else and switches case. </br>
 
Along wise I have also used the jump statements like break and goto. </br>




<!-- GETTING STARTED -->
## Getting Started

Welcome to the "Quiz Game using C" project repository! This guide will help you get started with the project and provide you with the necessary steps to set up and run the quiz game on your local machine.

### Prerequisites

Before you begin, make sure you have the following software and tools installed on your system:


1. C Compiler : You'll need a C compiler to build and run the project. GCC (GNU Compiler Collection) is a popular choice, and you can install it on various platforms.

   - Linux: You can install GCC on most Linux distributions using your package manager. For example, on Ubuntu, you can run:
	  ```sh
		sudo apt-get update
		sudo apt-get install gcc
	  ```
   - Windows: You can use MinGW (Minimalist GNU for Windows) to install GCC on Windows. <a href="http://www.mingw.org/">Download MinGW </a>, and follow the installation instructions.
	
   - macOS: For macOS users, you can use Xcode Command Line Tools, which include the GCC compiler. Install it by running:
	  ```sh
		xcode-select --install
	  ```


### Clone the Repository
To get started, you need to clone this repository to your local machine. Open your terminal or command prompt and run the following command:

  ```sh
  	git clone https://github.com/Shivu-2000/MCA-5SEM-cloud-lab-project.git
  ```

### Build and Run the Quiz Game

1. Navigate to the project directory:

	  ```bash
   		cd MCA-5SEM-cloud-lab-project
	  ```

2. Compile the source code using the C compiler:

	  ```bash
	  	gcc cquizgame.c -o cquizgame
	  ```

3. Run the compiled program:

	  ```bash
	  	cquizgame
	  ```


<!-- USAGE EXAMPLES -->
## Usage

Follow the on-screen instructions to play the quiz game. You can customize the questions and answers by modifying the quiz_game.c source code according to your preferences and requirements.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Do not forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request

<!-- Team Members -->
## Team Members
1. Nizam Ansari
2. Shivani Gupta
3. Harshit Kagliwal
4. Ayushman Tiwari
5. Vishal Pandey
