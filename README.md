# Day4-Lab2-Condition

You want to recommend a movie to a friend based on the rating and popularity. To accomplish this do the following:
- Create a variable for the movie (choose any movie you like).
x="Harry Potter"

- Create a variable of type int to hold the rating of the movie out of 5. Give this movie rate = 3
total_rate=5
rate=3

- Create a popularity score of type float, let it be 72.65
score=72.65

- Using an if statement:
  - Check if the movie rating is 4 or greater and the popularity is greater than 80, print "Highly recommended".
                          
  - Else if the movie rating is 3 or greater and the popularity is greater than 70, print "I recommended it, It is good".
  
  - Else if the movie rating is 2 or less and the popularity is greater than 60, print "You should check it out!".
  - Else the movie rating is 2 or less and the popularity is less than 50, print "Don't watch it, It is a waste of time".
  if rate>=4 and score > 80: 
                          print("Highly recommended")
elif rate>=3 and score > 70: 
                          print("I recommended it, It is good")
elif rate<=2 and score > 60: 
                          print("You should check it out!")
elif rate<=2 and score < 5: 
                          print("Don't watch it, It is a waste of time")
