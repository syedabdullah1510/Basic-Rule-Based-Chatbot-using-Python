while True:
  user_input=input("You : ").lower()

  if user_input in ["hi","hello","hey","hy"]:
    print("I hope this interaction finds you well. Please let me know how I may be of assistance")
  elif user_input in ["how are you?","how are you","what about you?"]:
    print("I’m doing well, thank you. How may I assist you?")
  elif user_input in ["can you help me with something?","can you help me?","can you explain something?"]:
    print("Certainly. Please specify how I may assist you")
  elif user_input in ["quit","exit","stop","end","close","bye","leave","goodbye"]:
    print("Thank you for your time. The session has been concluded. Have a great day")
    break
  else:
    print("I’m sorry, but I’m unable to understand your request")
    break
