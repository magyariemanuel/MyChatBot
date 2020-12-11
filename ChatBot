# I watched a tutorial on this and the link to that is https://www.youtube.com/watch?v=zHj1axji6Dc
# importing the chat and reflection modules s that I canmake the chatbot.
from nltk.chat.util import Chat, reflections

# these are the pairs that I am going to use, the reply on the right is what the user will respond with and the one on the left is that the bot will reply
pairs = [

    # General conversation so that the bot seems a bit more responsive and friendlier
    [ "my name is (.*)", ["Hello %1, How can I help you today ?"]],
    [ r"what is your name ?", ["My name is Bobby, how can I help you today?"]],
    [ r"i want a new (.*)", ["Okay I can help with that, what phone do you have in mind?"]],
    [ r"i want (.*)", ["Would you like a new phone contract? I can help you with that."]],
    [ r"hi|hey|hello", ["Hello", "Hey there, how can I help you today?"]],
    [ r"quit", ["Bye take care. See you soon "," It was nice talking to you. See you soon"]],

    # these are the 2 phone types that I am going to use, and the colour and memory as a list to make it easier to select and for the user to see what color and memory we have for that phone.
    [ r"Iphone (.*)", ["Great Choice, What colour do you want your Iphone %1 in? We have \n 1. Black \n 2. White \n 3. Red \n 4. Green \n 5. Silver \n Please choose a color."]],
    [ r"Samsung (.*)", ["Great Choice, What colour do you want your Samsung %1 in? We have \n 1. Black \n 2. White \n 3. Red \n 4. Green \n 5. Silver \n Please choose a color."]],

    # this is when the user choses a colour, the code will get the user to chose a memory to finalize the query.
    [ r"red", ["Perfect, Now please choose the memory \n 1. 32GB, \n 2. 64GB, \n 3. 128GB, \n 4. 256GB"]],
    [ r"black", ["Perfect, Now please choose the memory \n 1. 32GB, \n 2. 64GB, \n 3. 128GB, \n 4. 256GB."]],
    [ r"white", ["Perfect, Now please choose the memory \n 1. 32GB, \n 2. 64GB, \n 3. 128GB, \n 4. 256GB."]],
    [ r"green", ["Perfect, Now please choose the memory \n 1. 32GB, \n 2. 64GB, \n 3. 128GB, \n 4. 256GB."]],
    [ r"silver", ["Perfect, Now please choose the memory \n 1. 32GB, \n 2. 64GB, \n 3. 128GB, \n 4. 256GB."]],

    [ r"32", ["Perfect, Lets set this up for you"]],
    [ r"64", ["Perfect, Lets set this up for you"]],
    [ r"128", ["Perfect, Lets set this up for you"]],
    [ r"256", ["Perfect, Lets set this up for you"]],

]

# this function intorduces the bot, it states the name and a little bit of information for the user so that the program works.
def myChatBot():
    print("Hi, I am Bobby, what is you name?")
    chatbot = Chat(pairs, reflections)
    chatbot.converse()


# this is to test the program to see if it works.
if __name__=='__main__':
    myChatBot()

