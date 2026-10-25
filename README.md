# CS 320 Portfolio

this repo has my work from project one and project two.

project one: contact service (Contact.java, ContactService.java, ContactTest.java, ContactServiceTest.java)

project two: summary and reflections report

## How can I ensure that my code is functional and secure?

i test it against the requirements. for every rule i write a test for the good case and tests for the bad stuff like null, too long, and right at the limit. i used junit and checked coverage to see what my tests actually ran. coverage by itself dont prove its working tho so i made sure each test checks for the exact thing i expect, like a specific exception.

for security i dont trust input. everything gets checked for null and length before its saved, and the id is final so nobody can change it later. bad data gets rejected right away so it cant get into the rest of the program.

## How do I interpret user needs and incorporate them into a program?

i start with the requirements and turn each one into something i can check. like "id cant be longer than 10 characters" turns into a rule in the code and a test that tries 10 and 11. if somethings unclear i would just ask the customer instead of guessing. writing tests from the requirement list also helps me see if i missed anything.

## How do I approach designing software?

i keep it simple. small classes that do one job each, one for the data and one for add, update, and delete. i put each rule in one spot so i dont copy the same check twice. then i write tests as i go instead of waiting till the end, so problems get caught early and its easier to fix.
