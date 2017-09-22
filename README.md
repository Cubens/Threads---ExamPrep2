# Threads---ExamPrep2

This assignment has not been solved properly, seeing as i found it quite hard and didnt have more time..

The rest has been set up and if i had more time i would add a group entity class that could be filled with the fetched data and then returned as a json object

furthermore i would fetch the data from the sites (using threads) similar to the way i have done it in Excercise3(day3)..

i would then use jsoup to create a document from which i could pull the data like:

list.get(i).get().select("div#authors").text();

list.get(i).get().select("div#class").text();

list.get(i).get().select("div#group").text();


this if ofcourse just an idea i have for the solution, but i did not have time to complete it. 

There is a very simple rest example at: __/api/data/__
