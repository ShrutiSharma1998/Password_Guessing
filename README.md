# Password_Guessing


The aim of the project was to deduce the right passwords used by the customers, using the hash function concept. 

The project relied on the assumtion that the passwords are in most cases related to our personal details. 

1. On the Integrated Development and Learning Environment (IDLE), we ran our Python 3 code for the particular project.
2. The engineering design of the project was as follows: ![image](https://user-images.githubusercontent.com/93303431/139307046-a397dcb8-16ae-4123-875d-d0dc1cbbb5f4.png)
3. There were ways to tackle this requirement:
    a.  Method #1: brute-force attack with numbers 0–9 only. This is like trying to guess the combination on a bicycle or suitcase lock. If we think someone uses only numbers           for a password (such as for a PIN [personal identification number] at an ATM or on their smart phone), one method is simply to count from 0 to 999 and try each of               these as a password. Since all the dials on the lock are always used, we fill the number with leading zeros to give "000", "001", etc. all the way up to "999".
    b.	Method #2: brute-force attack with numbers and upper/lowercase letters. Imagine a lock that also has letters a–z and A–Z on each wheel. This gives 62 characters per             wheel instead of 10. This method will start out with a single "wheel" and test all 62 possibilities. It then adds a second, and tries all 622 possibilities, then a             third and tries 623, etc., up to 8 characters. This method can take a very long time to run for longer passwords, so we actually save it for last in the program.
    c.	Method #3: dictionary attack using a list of common passwords. A third method takes advantage of a list of passwords that people often use in real life. Mark Burnett,           the author of the book Perfect Passwords compiled a list of the 500 most common passwords used in 2005. We started with that list to make a list of 400+ words, saved in         passwords.txt. This third method tries all of these passwords. Since people may use capital letters or not, it also tries each word with the first letter as a capital.
    d.	Method #4: advanced dictionary attack that combines words. The fourth method builds on the third and takes advantage of the fact that people very often use passwords           that combine two words with a number or punctuation in between. A fan of wizarding stories might use the password "Harry+Ginny" for example, where the password is much         stronger than either "Harry" or "Ginny" alone (unless someone knows they like those characters). It also changes the punctuation in the middle and utilizes capital             letters at the beginning of words as well.
4. Using the hash code of the password enetered and crack_password.py, we then deduce the password for each user. 
5. The project was implemented successfully. 
