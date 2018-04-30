# Listing Classmates

This is a group lab, so make sure you are working in a group of 2-4 students

Arrays can be thought of as ordered lists of _things_.  They can all kinds of
data and return that data upon request.  In order to request a bit of data, we
just need to give an array a number value representing the _index_ of the data
we want.

```ruby
student_names = [
  "Adele",
  "Beyoncé",
  "Cardi B"
]
```

If we want to access the first value in the array `student_names`, we can just
type `student_names[0]`, if we want the second, we can type `student_names[1]`.

# Challenge 1: Using Index Values

In the file `reading_arrays.rb`, we've got a class of superstar students, listed
in alphabetical order. Presentations are due, and our students need to be called
one at a time, using this array, to go in front of the class and perform.

Your challenge is to write solutions for the first three methods in the file
`reading_arrays.rb` using the provided array of `student_names`.  

* `first_student_by_index` should return the first student in the array
* `fourth_student_by_index` should return the fourth student in the array
* `last_student_by_index` should return the last student in the array

Use index values to solve these!

## Using Built In Array Methods, `.first` and `.last`

Ruby arrays have some handy, built in methods that help us access data in
arrays. Using the earlier example, if we wanted the first value in the
`student_names`, instead of `student_names[0]`, we can use
`student_names.first`! The `.first` method always returns, you guessed it, the
_first_ item in an array. Similarly, if we typed `student_names.last`, we would
always get back the last item in the array.

This may seem unnecessary - we've already got a way to access by index, right?
Well, it turns out methods like `.last` are very useful in certain situations.
What if our `student_names` listed around two hundred students, instead of
only a few? What if we didn't know the _exact_ amount of students in the array?

Since, `student_names.last` will always return the last item, we don't need to
know how long the array is, it will just work.

## Challenge 2: Using `.first` and `.last`

Write solutions for the forth and fifth methods in the file `reading_arrays.rb`
using the provided array of `student_names`.  

* `first_student_by_method` should return the first student in the array using the `.first` method
* `last_student_by_method` should return the last student in the array using the `.last` method

## Challenge 3: Returning More Than One Value

Let's say, with our class of superstars, we wanted to form some small groups for
epic song collaboration.  The first group will be Adele, Beyoncé, and Cardi B.
How can we return three items in _one_ method? For the sixth method in this lab,
write a solution that returns the first _three_ students in the list.

* `first_second_and_third_students` should return the first, second and third student in the array

# Summary

* Arrays can either be accessed by index or by using built in methods
* Using methods, you don't need to know how long an array of items is or have
an exact index value
