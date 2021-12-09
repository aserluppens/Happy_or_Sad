# Happy_or_Sad
Count the number of happy or sad emojis in a text and print the mood of the writer

Problem ccc15j2 from DMOJ

"We often include emoticons in our text messages to indicate how we are feeling. The three consecutive characters ":-)" indicate a happy face and the three consecutive characters ":-(" indicate a sad face. Write a program to determine the overall mood of a message."

Input Specification:
There will be one line of input that contains between 1 and 255 characters.

Output Specification:
The output is determined by the following rules:

If the input line does not contain any happy or sad emoticons, output "none".
Otherwise, if the input line contains an equal number of happy and sad emoticons, output "unsure".
Otherwise, if the input line contains more happy than sad emoticons, output "happy".
Otherwise, if the input line contains more sad than happy emoticons, output "sad".
