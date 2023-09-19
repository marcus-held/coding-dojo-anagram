# Coding Dojo

## Principles
* All skill levels are welcome
* We do not compete – We learn
* Code without tests does not exist
* Refactoring is highly encouraged

## Roles
* Sensei
  * Asks only questions
  * Enforces principles and rules
* Pilot
  * Types code
  * Explains everything he types
* Co-pilot
  * Teams with the pilot
* Audience
  * Must ask when something is unclear
  * Helps (only) when team is stuck

## Rules
* After 5 minutes:
  * the co-pilot becomes the pilot
  * A new co-pilot is picked from the audience
* At half-time, 10 minute break
* Everyone must be (co-)pilot
* Tests must be written first
---
## Setup
* Download JDK 21
* Make sure that you can run the [main()](src/main/java/com/dojo/Main.java) function and [MainTest#success](src/test/java/de/hogrefe/MainTest.java) unit test

## The Challenge
Write a program that generates all two-word anagrams of the string “documenting”. You must focus on the readability of your code, and you must not include any kind of documentations to it. The goal is to create a code that everybody can read and understand easily.

Use the [word list](src/main/resources/word_list.txt) as a dictionary.

### Stretch Goal
Try to improve the performance of your solution but keep in mind that making it faster affects readability.
Continue to focus on readability first.
