def chatbot():
    print("🤖 Chatbot: Hi! I'm a simple chatbot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower().strip()

        # Rule-based responses
        if "hello" in user_input or "hi" in user_input:
            print("🤖 Chatbot: Hello there! How can I help you today?")

        elif "how are you" in user_input:
            print("🤖 Chatbot: I'm doing well, thanks for asking! What about you?")

        elif "your name" in user_input:
            print("🤖 Chatbot: I'm a simple rule-based chatbot.")

        elif "help" in user_input:
            print("🤖 Chatbot: I'm here to help. Try asking about the weather, time, or just say hi!")

        elif "time" in user_input:
            from datetime import datetime
            current_time = datetime.now().strftime("%H:%M:%S")
            print(f"🤖 Chatbot: The current time is {current_time}")

        elif "date" in user_input:
            from datetime import datetime
            current_date = datetime.now().strftime("%Y-%m-%d")
            print(f"🤖 Chatbot: Today's date is {current_date}")

        elif "bye" in user_input or "exit" in user_input:
            print("🤖 Chatbot: Goodbye! Have a great day!")
            break

        else:
            print("🤖 Chatbot: I'm sorry, I didn't understand that.")

# Run the chatbot
chatbot()
