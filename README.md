## RSA FACTORING CHALLENGE

## Description 
<code> We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents. </code>

<code> This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score wont get hurt if you dont do it, but if your current average is greater than your score on this project, your average might go down. Have fun! </code>

## Resources
## Read or watch:

## RSA
<li> How does HTTPS provide security? </li>
<li> Prime Factorization </li>
<li> Why RSA? </li>

## Requirements
## General
<li> You can choose the language of your choice. </li> 
<li> OS needs to be Standard Ubuntu 20.04 LTS/ </li>


## Task 0
<li> Factorize as many numbers as possible into a product of two smaller numbers. </li>

<li> <code> Usage: factors <file> </code> </li>
<li> where<code>  <file> </code> is a file containing natural numbers to factor. </li>
<li> One number per line </li>
<li> You can assume that all lines will be valid natural numbers greater than 1 </li> 
<li> You can assume that there will be no empy line, and no space before and after the valid number </li>
<li> The file will always end with a new line </li>

* Output format: =p*q 

* one factorization per line
* p and q dont have to be prime numbers
* See example
* You can work on the numbers of the file in the order of your choice
* Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
* Time limit: Your program will be killed after 5 seconds if it hasnt finish
* Push all your scripts, source code, etc to your repository
* we will only run your executable factors
-------------------
[factors](./factors)


## Task 2
* RSA Laboratories states that: for each RSA number  n, there exist prime numbers p and q such that
* n = p  q. The problem is to find these two primes, given only n.
* This task is the same as task 0, except:
* p and q are always prime numbers
* There is only one number in the files
* How far can you go in less than 5 seconds?

Read:
---------------------- 
[RSA Factoring Challenge](./www.en.wikipedia.org/wiki/RSA_Factoring_Challenge)

------
[rsa](./rsa)


## Student Name 
* Joseph Kakai

## Cohort 
* C9
