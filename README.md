# Week-2
Creating a small Jupyter Notebook using the zip() function. 
#The zip () function takes in iterables as arguments and returns an iterator. This iterator generates a series of tuples containing elements from each iterable. Utlizing the zip function in various scenarios to display how it works. 

# First scenario utilizes the zip function to pair the first and last name of various people.
First_Nam = ("Joe", "Kareem", "Mical")
Last_Nam = ("Jones", "Alo", "Joseph")

Full_Nam = zip(Last_Nam,First_Nam)

#convert zip object into tuple so that it can be iterable
print(tuple(Full_Nam))
print('\n')

# Second scenario utilizes the zip function to pair students names and the grade they recieved. 
Student_Name = ("Danny","Hunter","James","Jess","Demarcus","Vince")
Grade = ("A","A-","A+","F","C-","C+")

Each_Grade = zip(Student_Name,Grade)

#convert zip object into tuple so that it can be iterable
print(tuple(Each_Grade))
print('\n')


# Third scenario utilizies the zip function to pair items with their price

Item=("Horse", "Milk", "Car", "Eggs", "Bacon")
Price=("$1", "$50", "$56.49","$49.99", "$3.50")

Label = zip(Price, Item)
print(tuple(Label))
print('\n')
