## CS214 – Software Development (Spring 2025)

### [Project: Music Analyzer — Interactive CLI Application](https://github.com/yeahbrahh/Music-Analyzer)

This project involved developing a stateful, menu-driven command-line program in Java that analyzed music datasets stored in CSV files. Users could load a folder of files, select a dataset, and run a variety of analytical features such as Song Stats, User Similarity, User Prediction, and User Recommendation.

### My Work

I built both the core analysis logic and the interactive user interface that tied everything together.
	
•	Implemented all major features:

•	Song Stats: computed aggregate statistics for songs across users.

•	User Similarity: calculated similarity scores between user profiles.

•	User Prediction: predicted user ratings for songs based on patterns in data.

•	User Recommendation: generated personalized song suggestions based on prior inputs.

•	Created the menu system.

•	Added support for dynamic menus that listed available files and songs in lexicographical order.

•	Implemented file I/O for both reading CSV datasets and writing output results.

•	Integrated all previous features into one cohesive, user-friendly CLI.

### Technical Notes
	
•	Language: Java 20

•	Files: Cs214Project.java (main program), TestCs214Project.java (JUnit tests)

### Reflection

Building the Music Analyzer from core logic to full user interface gave me hands-on experience with modular program design. It was the first time I had to integrate multiple independent features into one smooth user experience, a challenge that strengthened both my technical skills and my ability to structure large projects clearly.
