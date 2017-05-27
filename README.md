# random-library
random library
import random
 
print "Generate some random numbers :"
 
print "\nNumber in the range 0.0 to 1.0"
print random.random()
 
print "\nNumber in the range 1.2 to 2.5"
print random.uniform(1.2, 2.5)
 
print "\nWhole number in the range 3 to 9"
print random.randint(3,9)
 
print "\nNumber in the range 0 to 10"
print random.randrange(10)
 
print "\nNumber in the range 2 to 10 in steps of 3"
print random.randrange(2,30,3)
 
print "\nCharacter from the list ['a','e','i','o','u']"
print random.choice(['a','e','i','o','u'])
 
print "\nThree random numbers from list [12,16,19,34,23,34,56,67]"
print random.sample([12,16,19,34,23,34,56,67], 3)
 
print "\nShuffle contents of list [1,2,3,4,5]"
mylist = [1,2,3,4,5]
random.shuffle(mylist)
print mylist
