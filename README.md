import random

def chatbot_response(user_input):
    responses = [
        "Hello! How can I help you today?",
        "Hi there! What can I do for you?",
        "Greetings! How may I assist you?",
        "Hello! What would you like to know?",
    ]
    return random.choice(responses)
def chatbot_response(user_input):
    user_input = user_input.lower()
    if "hello" in user_input or "hi" in user_input:
        return "Hello! How can I help you today?"
    elif "how are you" in user_input:
        return "I'm just a bot, but I'm doing great! How about you?"
    elif "your name" in user_input:
        return "I'm a simple chatbot created to assist you."
    elif "tell me a joke" in user_input:
        return "why do the maths book look sad ?Because it had too many problems!"
    elif "what is your age" in user_input:
        return "I dont't have an age like human do since I'm a virtual friend"
    elif "what is bts" in user_input:
        return "bts is a super popular South Korean boy band!That're known for their awesome music"
    elif "exit" in user_input:
        return "Goodbye!"
    else:
        return "I'm sorry, I don't understand that."

# The rest of the code remains the same


def main():
    print("Chatbot: Hello! Type 'exit' to end the conversation.")
    while True:
        user_input = input("You: ")
        if user_input.lower() == 'exit':
            print("Chatbot: Goodbye!")
            break
        response = chatbot_response(user_input)
        print(f"Chatbot: {response}")

if __name__ == "__main__":
    main()
import random

def chatbot_response(user_input):
    responses = [
        "Hello! How can I help you today?",
        "Hi there! What can I do for you?",
        "Greetings! How may I assist you?",
        "Hello! What would you like to know?",
    ]
    return random.choice(responses)
def chatbot_response(user_input):
    user_input = user_input.lower()
    if "hello" in user_input or "hi" in user_input:
        return "Hello! How can I help you today?"
    elif "how are you" in user_input:
        return "I'm just a bot, but I'm doing great! How about you?"
    elif "your name" in user_input:
        return "I'm a simple chatbot created to assist you."
    elif "tell me a joke" in user_input:
        return "why do the maths book look sad ?Because it had too many problems!"
    elif "what is your age" in user_input:
        return "I dont't have an age like human do since I'm a virtual friend"
    elif "what is bts" in user_input:
        return "bts is a super popular South Korean boy band!That're known for their awesome music"
    elif "exit" in user_input:
        return "Goodbye!"
    else:
        return "I'm sorry, I don't understand that."

# The rest of the code remains the same


def main():
    print("Chatbot: Hello! Type 'exit' to end the conversation.")
    while True:
        user_input = input("You: ")
        if user_input.lower() == 'exit':
            print("Chatbot: Goodbye!")
            break
        response = chatbot_response(user_input)
        print(f"Chatbot: {response}")

if __name__ == "__main__":
    main()
