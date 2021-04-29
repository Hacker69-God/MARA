import androidhelper

def talk(message):
    droid = androidhelper.Android()
    droid.ttsSpeak(message)





print("Hello sir,")
print("i am MARA, your personal assistant 😊")
print("how can i help you 🤗")
def tool():
    command=input("enter any command")
    if "hello" in command:
        message="Hello sir"
        print(message)
        talk(message)
        
    elif "who are you" in command:
        message="i am MARA , sir"
        print(message+"🙃")
        talk(message)
        
    elif "how are you" in command:
        message="if you are fine i also fine sir"
        print(message)
        talk(message)
        
    elif "play song" in command:
        song = command.replace("play song" , "")
        print("playing "+song)
        print(song)
        
    elif "old are you" in command:
        message="i was just born now"
        print(message+"🤭")
        talk(message)
        
    elif "you are so sweet" in command:
        message="hmm... like a robotic candy "
        print(message+"🍬")
        talk(message)
        
    elif "thank you" in command:
        message="it's my pleasure sir "
        print(message+"💗")
        talk(message)
        
    elif "thanks" in command:
        message=" i am happy to help you sir "
        print(message+"🤗")
        talk(message)
        
    else:
        message="sorry i am new , please say again"
        print(message+"😅")
        talk(message)
    
while True:
    tool()

