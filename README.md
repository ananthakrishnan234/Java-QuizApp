# Java-QuizApp 

A simple command-line **Java Quiz App** that tests basic Java programming knowledge. The application presents a series of multiple-choice questions, takes user input, and displays results including score and performance level. Ideal for beginners exploring object-oriented programming, conditionals, and maps in Java.

## Features 

- 5 multiple-choice Java questions  
- User input validation  
- Displays number of correct and incorrect answers  
- Calculates and displays performance feedback  
- Object-oriented design using custom `Questions` class

## Technologies Used 

Java  
IntelliJ IDEA  
Command Line (Terminal)

## How to Run 

Clone the repository using:  
`git clone https://github.com/ananthakrishnan234/Java-QuizApp.git`

Navigate to the project directory:  
`cd Java-QuizApp`

Compile and run the Java files:  
```bash
javac src/*.java
java -cp src Main
```

## Folder Structure 

Java-QuizApp/  
├── src/  
│   ├── Main.java     # Contains quiz logic and execution  
│   └── Questions.java # POJO class representing each quiz question  
├── questions.txt   # Questions for quiz 
├── .gitignore     # Git ignored files/folders  
├── out/         # Compiled classes  
└── .idea/        # IDE project config files


## Author 

[Ananthakrishnan Sudhakaran](https://github.com/ananthakrishnan234)

## License 

This project is open-source and available under the [MIT License](LICENSE).
