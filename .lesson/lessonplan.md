# Lesson Plan

This week, we will learn about working with dictionaries. Dictionaries are another data structure in Python. They’re similar to a list in that they can be used to organize data into collections. However, data in a dictionary isn't accessed based on its position. Data in a dictionary is organized into pairs of keys and values. You use the key to look up the corresponding value. A list index is always a number, but a dictionary key can be any data type, like a string, integer, or float.

In this lesson, we are also going to learn about using a for loop to iterate over a sequence of values. For example, we can process text character by character, or iterate over numbers in a range of numbers. A more streamlined way of doing this is using list comprehension. List comprehensions allow you to create a new list from a sequence or a range in a single line. For example, [ x*2 for x in range(1,11) ] is a simple list comprehension. This would iterate over the range 1 to 10, and multiply each element in the range by 2. This would result in a list of the multiples of 2, from 2 to 20.

In this week's lesson we will walk you through how to:

* Create a dictionary
* Using a for loop and a list comprehension to process text character by character
* Use dictionary methods to check if something exists or retrieve a value, or find all of the keys or values
* Use a dictionary to substitute keys with their values, and print a new string.

## Homework (solfege)
Can you use these new skills in the homework? This week, our script will accept positional arguments from the user with syllables (Do, Re, Me, Fa. Sol, La, Ti) from the solfege song in the Sounds of Music. Each of these syllables has a phrase that goes with it. For example, the syllable "Do" goes with the phrase "A deer, a female deer". You will be creating a dictionary of these where the key is the syllable and the phrase is the value. Then, you will look up and print the phrase for each of the syllables the user provides. Watch out! Users are tricky and can give you a syllable that doesn't exist. You will need to check for this possibility and give the user feedback. 

Reach out if you need any help! We use the same tests you are given to test the code and assign a grade for your assignment.

## Learning Objectives:

Learn how to add, remove, and replace elements in a dictionary. Learn about accessing values in dictionaries with dict.get(), or all keys dict.keys(), or all values dict.values(), or all items dict.items() as a list of key/value pairs. Learn how to use for loops to iterate over a sequence of values, or more advanced options like list comprehensions to create a new list from a sequence or a range in a single line of code.