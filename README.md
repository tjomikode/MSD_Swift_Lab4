### This is Lab №4 from Mobile Systems Development:white_check_mark:
#### Author: Artem Sevruk, group IV-71
____
Challenges and issues I could not solve:
* Storing local data after closing an app. E.g. storing new movies cells added by user. I tried using `UserDefaults` and conform my `Movie` class to protocols `NSObject`, `NSCoding`, but it did not work out. I understood that I have to archive all the data, but I did not understand how to implement it. Maybe, is it better to store data in a database? I also tried `Core Data`, but it was hard so I gave up.

* AutoLayout, constraints. I have two labels in each row, so I have to get my second label wrap its text onto the next row, but it wraps like this:

  ![Текст](image_readMe.png)
  
  What do I do?
* Warning message if there are no movies in our list after unknown movie typed. I used `UIAlertController`, but in your example as far as I understood you used segue to another     `ViewController`, did not you? So, I don't know whether `UIAlertController` is good alternative or not in this case?

* For searching movies I am using another array `filteredMoviesArray` where I store filtered list of movies and then use it. It seems like it is working.  

*__Please, feel free to leave all possible comments & suggestions & advices & helps :) Thanks :)__*
