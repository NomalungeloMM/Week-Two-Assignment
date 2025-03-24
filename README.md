# Week-Two-Assignment
# Task 1: Sum of a List of Integers
numbers = list(map(int, input("Enter integers separated by spaces: ").split()))
print("Sum of the numbers:", sum(numbers))

# Task 2: Tuple of Favorite Books
favorite_books = ("The Hobbit", "1984", "To Kill a Mockingbird", "The Great Gatsby", "Pride and Prejudice")
for book in favorite_books:
    print(book)

# Task 3: Dictionary to Store Person's Info
person = {}
person['name'] = input("Enter your name: ")
person['age'] = int(input("Enter your age: "))
person['favorite_color'] = input("Enter your favorite color: ")
print("Person's information:", person)

# Task 4: Common Elements in Two Sets
set1 = set(map(int, input("Enter integers for the first set separated by spaces: ").split()))
set2 = set(map(int, input("Enter integers for the second set separated by spaces: ").split()))
common_elements = set1.intersection(set2)
print("Common elements:", common_elements)

# Task 5: List Comprehension for Odd-Length Words
words = ["apple", "banana", "cherry", "date", "elderberry"]
odd_length_words = [word for word in words if len(word) % 2 != 0]
print("Words with odd number of characters:", odd_length_words)

# Task 6: List Manipulation
my_list = []  # Create an empty list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)  # Insert 15 at the second position
my_list.extend([50, 60, 70])  # Extend the list with another list
my_list.pop()  # Remove the last element
my_list.sort()  # Sort the list in ascending order
index_30 = my_list.index(30)  # Find the index of value 30
print("Sorted list:", my_list)
print("Index of 30:", index_30)
