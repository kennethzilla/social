# Social Media Challenge




## Ruby
It is written in Ruby 3.0.2p107 and Rails 7.0.6

## Dependencies
Ruby
Ruby on Rails

## Test suite
RSPEC

## How to run the MiniTest Test suite

```
bunsle exec rake rspec
```

## How to run the program

```
bundle exec rails s
http://localhost:3000/social_media_posts
```

## The Challenge

## Approach to the Toy robot problem 

My first approach of the problem. 

My first step is to to make a decision how much time do I have with this challenge. Since time is a constraint.
So I've given myself a time limit of no longer than 4 hours to complete this challenge.

My second step is to decide the goals and objectives I wanted to demonstrate and achieve through this challenge.

Third step, I chose to design the database schema. This step ensures efficient structuring and organisation of the data required for the challenge.

### Objectives:              
 
 
 Object-oriented 
 Readability - Easy to read and understand
 Easy to modify by making the code DRY.

  
     
#### Database design of the Social Media Challenge

Here is the DB table diagram I've designed using DB Designer tool

https://dbdesigner.page.link/dPkCYfwMC9dhV7f89

Database Definition
##### Team table
**is used to store information about different teams**
##### Custom_lists
**is designed to store custom lists that are related to specific teams**
##### Custom_list_persons
**stores information about people who are associated with the custom lists.**
##### Social_media_types
**store different types of social media platforms. eg facebook, twitter etc...**
##### Social_media_people_identifiers:
**holds the social media identifier of a person.**
##### Social_media_posts
**store posts specific person made on social media platforms**

I believe that using polymorphism for both the custom lists and federal legislators table would be a suitable and elegant solution

#### Conclusion

After careful consideration, I've choosen test suite with Rspec and shoulda-matchers gem for writing clean and neat model specs.

https://github.com/thoughtbot/shoulda-matchers

This is because is something easy to set up and get it running due to this challenge limited time constraint.

Overall I'm happy what I've done in this challenge in this 4 hour slot. 

### Improvements

Will be good to have Rubocop gem install to enforce Ruby Style Guide standard to the code.

GUI part - Displaying meaningful messages and User friendly Prompts for the user input. And als will be good to validate user input value.

If this wasn't a code challenge exercise. The GUI filter presentation logic can be extract into a separate service class object. This approach would help improve code organisation, promote reusability, and maintain a clearer separation of concerns.


