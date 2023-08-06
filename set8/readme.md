TODO: Reflect on what you learned this week and what is still unclear.
This week we completed our in class exam. The exam reflected the content we learnt over the course of sets 1-4. The exam included functions such as:

"give_me_five()": This function returns the integer 5. It does so by converting the string "5" to an integer and then returning it. The function is straightforward and fulfills its purpose of providing the number five.

"password_please()": This function is supposed to return a string that is 8 or more characters long and contains at least one uppercase letter and one lowercase letter. However, the implementation currently returns the string "Avacados," which does not meet the specified requirements. It could be improved to generate a random password that satisfies the conditions.

"list_please()": This function returns a list containing the characters 'c', 'a', 't', ',', ' ', 'd', 'o', 'g', ',', ' ', 'c', 'h', 'i', 'c', 'k', 'e', and 'n'. However, the intention seems to be creating a list with three elements: 'cat', 'dog', and 'chicken'. To fix this, the string inside the list() constructor should be converted to a list properly, like this: return ['cat', 'dog', 'chicken'].

"int_list_please()": This function returns a list of integers from 1 to 5. It correctly returns the list [1, 2, 3, 4, 5], as intended.

The last few questions of the exam were a little bit tricky as I could not recall some of the information needed to correctly complete the function. This included the "fast_filler" function which addressed the need to generate filler text efficiently. It uses caching to speed up the process by saving the dictionary generated from "make_filler_text_dictionary" to a file on the first run and then reusing it on subsequent runs.  