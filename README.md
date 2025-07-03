def chatbot():
    print("Chatbot: Hi! I'm a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if "hello" in user_input or "hi" in user_input:
            print("Chatbot: Hello there! How can I help you today?")
        
        elif "how are you" in user_input:
            print("Chatbot: I'm just a bunch of code, but I'm doing great! What about you?")
        
        elif "your name" in user_input:
            print("Chatbot: I'm just a simple chatbot created to help you.")

        elif "help" in user_input:
            print("Chatbot: Sure, I can try to help. Ask me anything!")
        
        elif "bye" in user_input or "exit" in user_input:
            print("Chatbot: Goodbye! Have a great day!")
            break
        
        else:
            print("Chatbot: I'm sorry, I didn't understand that.")
chatbot()
