# week-2-assignment
. Program to create a list of integers and compute their sum
python
Run
Copy code
# Accept user input to create a list of integers
user_input = input("Enter integers separated by spaces: ")
integer_list = [int(num) for num in user_input.split()]

# Compute the sum of all integers in the list
total_sum = sum(integer_list)
print(f"The sum of the integers is: {total_sum}")
2. Tuple of favorite books and printing each book name
python
Run
Copy code
# Create a tuple containing the names of five favorite books
favorite_books = ("1984", "To Kill a Mockingbird", "The Great Gatsby", "Pride and Prejudice", "Moby Dick")

# Use a for loop to print each book name on a separate line
for book in favorite_books:
    print(book)
3. Program to store information about a person in a dictionary
python
Run
Copy code
# Create a dictionary to store information about a person
person_info = {}

# Ask the user for input
person_info['name'] = input("Enter your name: ")
person_info['age'] = input("Enter your age: ")
person_info['favorite_color'] = input("Enter your favorite color: ")

# Print the dictionary to the console
print("Person Information:")
print(person_info)
4. Program to create two sets of integers and find common elements
python
Run
Copy code
# Accept user input to create two sets of integers
set1_input = input("Enter integers for the first set separated by spaces: ")
set2_input = input("Enter integers for the second set separated by spaces: ")

set1 = {int(num) for num in set1_input.split()}
set2 = {int(num) for num in set2_input.split()}

# Create a new set that contains only the elements that are common to both sets
common_elements = set1.intersection(set2)

# Print the common elements
print(f"The common elements are: {common_elements}")
5. Program to filter words with an odd number of characters using list comprehension
python
Run
Copy code
# Store a list of words
words = ["apple", "banana", "cherry", "date", "fig", "grape"]

# Use list comprehension to create a new list with words that have an odd number of characters
odd_length_words = [word for word in words if len(word) % 2 != 0]

# Print the new list
print("Words with an odd number of characters:", odd_length_words)
