# Whiteboarding

Whiteboarding is a common practice in technical interviews. The goal is to
convey how you think through a challenging problem and what steps you'd take to
get started. You do not need to arrive at a solution or write perfect code. In
fact, think of it as writing detailed pseudocode.

## Instructions

Each group member will take turns being the candidate (the one whiteboarding)
and the interviewers (the ones reading and assessing the prompt).

If you are the candidate, stand up at the white board without looking at your
prompt. One of the interviewers should read out the prompt to you and set
a timer for 10 minutes. The candidate should work through the prompt until the
timer goes off. If you feel like you've solved the problem before the timer goes
off, start to talk and think through ways to make your code faster or more
efficient.

### Candidate Instructions

The prompt will be read off to you. Ask clarifying questions if something seems
unclear, then start whiteboarding. It's a good idea to take notes about the
prompt on the white board as the prompt is being read to you.

As you work on the solution, talk it out. The goal is not to arrive at the
correct answer, but rather to convey how you would approach solving the problem.

When the timer goes off, take a seat in front of your interviewers!

### Interview Instructions

When the candidate is ready, read their prompt out loud to them. If they have
questions, come up with what you think would be a good answer. Your goal is to
only provide information that they ask for!

Watch the candidate as they white board and take notes. You're looking for them
to talk through their thinking and explain not only what they're doing but why
they're doing it a certain way. Stop them and ask them why they're approaching
the problem they way that they are.

When the timer goes off, have the candidate take a seat. First, ask them what
they thought went well. Then discuss the prompt and their process with them.

Try to debrief each question as a group for at least 10 minutes.

## Prompts

<details>
  <summary>Prompt</summary>

  Given an array of integers, write a function that returns a sorted list of all the
  duplicates in the array.

  e.g.:

  ```js
    dups([1, 2, 3])    // = []
    dups([1, 2, 2])    // = [2]
    dups([3, 3, 3])    // = [3]
    dups([2, 1, 2, 1]) // = [1, 2]
  ```

  How would you make your solution more efficient?

  [Source](https://www.byte-by-byte.com/findduplicates/)
</details>

<details>
  <summary>Prompt</summary>

  A linked list is a list structure made of of nodes where each node contains
  a value and a reference to the next node in the list:

  ![Linked
  List](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Linked%20Lists/pix/linkedlist.bmp)

  Given an unsorted linked list, write a function that removes all duplicates
  (i.e. returns a new linked list containing only the unique values).

  [Source](https://www.byte-by-byte.com/deduplinkedlist/)

</details>

<details>
  <summary>Prompt</summary>

  Given two strings, write a function to determine whether they are anagrams.

  e.g.:

  isAnagram("", "") = true

  isAnagram("A", "A") = true

  isAnagram("A", "B") = false

  isAnagram("ab", "ba") = true

  isAnagram("AB", "ab") = true

  [Source](https://www.byte-by-byte.com/anagrams/)

</details>

<details>
  <summary>Prompt</summary>

  New York City has the highest population of any city in the U.S., with
  8,550,405 people. Bonanza, Utah has the smallest population with only 1 person
  living in it (his name is John).

  How would you calculate the exact population of the United States.
</details>

<details>
  <summary>Prompt</summary>

  Given an array of numbers, write a function that returns the largest
  difference between two consecutive numbers in the array.

  e.g.:

  largestDifference([1, 3]) // => 2

  largestDifference([1, 3, 8]) // => 5

  largestDifference([1, 3, 8, 0, 9]) // => 9

</details>

<details>
  <summary>Prompt</summary>

  Given two integers, write a function that swaps them without using any temporary variables.

  [Source](https://www.byte-by-byte.com/swapvariables/)

</details>

<details>
  <summary>Prompt</summary>

  Given two strings of integers, write a function that will return the number
  of common characters.

  e.g.:

  commonChars('abc', 'abc') // => 3

  commonChars('aef','hqa') // => 1

  commonChars('ferlv','evlrf') // => 5

</details>
