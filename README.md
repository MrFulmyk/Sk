def start_game():
    print("Welcome to the Adventure Game!")
    print("In this game, you'll make choices that determine the outcome of the story.")
    print("Let's begin...\n")

    first_choice()

def first_choice():
    print("You find yourself in a dark forest. There are two paths ahead.")
    print("1. Take the left path")
    print("2. Take the right path")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        left_path()
    elif choice == "2":
        right_path()
    else:
        print("Invalid choice. Please try again.")
        first_choice()

def left_path():
    print("\nYou take the left path and encounter a wise old man.")
    print("He offers you two books: one on philosophy and one on literature.")
    print("1. Choose the book on philosophy")
    print("2. Choose the book on literature")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        philosophy_book()
    elif choice == "2":
        literature_book()
    else:
        print("Invalid choice. Please try again.")
        left_path()

def right_path():
    print("\nYou take the right path and find a magical mirror.")
    print("The mirror shows you two possible futures.")
    print("1. A future where you become a famous author")
    print("2. A future where you live a quiet, happy life")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        famous_author()
    elif choice == "2":
        quiet_life()
    else:
        print("Invalid choice. Please try again.")
        right_path()

def philosophy_book():
    print("\nYou start reading the book on philosophy and get lost in deep thoughts.")
    print("You ponder the nature of free will and determinism.")
    print("Do you believe in free will?")
    print("1. Yes, I believe in free will")
    print("2. No, I believe everything is predetermined")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou continue your journey with a strong belief in free will. Your choices matter, and they shape your path.")
        philosophy_path()
    elif choice == "2":
        print("\nYou continue your journey with the understanding that everything is predetermined. You feel a sense of peace, knowing that everything happens for a reason.")
        determinism_path()
    else:
        print("Invalid choice. Please try again.")
        philosophy_book()

def literature_book():
    print("\nYou start reading the book on literature and immerse yourself in the stories.")
    print("You see the characters making choices and facing consequences.")
    print("Do you think the characters have free will?")
    print("1. Yes, the characters make their own choices")
    print("2. No, the author controls everything")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou realize that, like the characters, you also have the power to make your own choices. Your journey continues with this newfound understanding.")
        character_path()
    elif choice == "2":
        print("\nYou realize that, like the characters, your life may also be controlled by some higher power. You continue your journey with this perspective.")
        author_path()
    else:
        print("Invalid choice. Please try again.")
        literature_book()

def famous_author():
    print("\nYou become a famous author, writing stories that captivate the world.")
    print("You realize that through your writing, you can explore the themes of free will and determinism.")
    print("Do you use your stories to promote the idea of free will?")
    print("1. Yes, I write stories that emphasize free will")
    print("2. No, I write stories that emphasize determinism")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYour stories inspire people to believe in their own power to shape their destinies. You leave a lasting impact on the world.")
        end_game()
    elif choice == "2":
        print("\nYour stories make people reflect on the nature of fate and destiny. You leave a lasting impact on the world.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        famous_author()

def quiet_life():
    print("\nYou live a quiet, happy life, finding contentment in the simple things.")
    print("You have time to reflect on your beliefs about free will and determinism.")
    print("Do you believe your happiness is a result of your choices?")
    print("1. Yes, my choices led to my happiness")
    print("2. No, my happiness was destined")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou continue to make choices that bring you joy and fulfillment. Your life is a testament to the power of free will.")
        end_game()
    elif choice == "2":
        print("\nYou find peace in the belief that your happiness was destined. Your life is a testament to the beauty of fate.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        quiet_life()

def philosophy_path():
    print("\nAs you journey with your belief in free will, you encounter various challenges.")
    print("You meet a traveler who questions your beliefs and presents you with a dilemma.")
    print("1. Help the traveler and prove your belief in free will")
    print("2. Ignore the traveler and continue on your path")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou help the traveler and find that your actions have a significant impact on their life. Your belief in free will is strengthened.")
        end_game()
    elif choice == "2":
        print("\nYou ignore the traveler and continue on your path, but you wonder if your choice mattered. Your belief in free will is challenged.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        philosophy_path()

def determinism_path():
    print("\nAs you journey with the belief that everything is predetermined, you find peace in the events that unfold.")
    print("You encounter a wise sage who shares a secret about destiny.")
    print("1. Listen to the sage and embrace your destiny")
    print("2. Challenge the sage's views and seek your own path")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou listen to the sage and embrace your destiny, finding peace in the knowledge that everything happens for a reason.")
        end_game()
    elif choice == "2":
        print("\nYou challenge the sage's views and seek your own path, but you continue to ponder the nature of destiny.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        determinism_path()

def character_path():
    print("\nAs you continue your journey, you encounter characters from classic literature.")
    print("You meet Hamlet, who is struggling with his own choices.")
    print("1. Help Hamlet make a decision")
    print("2. Leave Hamlet to his own devices")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou help Hamlet and realize that your guidance can change the course of his story. Your belief in free will is reinforced.")
        end_game()
    elif choice == "2":
        print("\nYou leave Hamlet to his own devices and reflect on the power of choice in literature. Your belief in free will remains strong.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        character_path()

def author_path():
    print("\nAs you continue your journey, you meet great authors who control the fates of their characters.")
    print("You have the opportunity to ask them about their views on free will and destiny.")
    print("1. Ask about free will")
    print("2. Ask about destiny")

    choice = input("Enter the number of your choice: ")

    if choice == "1":
        print("\nYou learn that even authors struggle with the concept of free will, and their stories often reflect this struggle. Your understanding deepens.")
        end_game()
    elif choice == "2":
        print("\nYou learn that authors often weave destiny into their stories, creating a sense of inevitability. Your understanding deepens.")
        end_game()
    else:
        print("Invalid choice. Please try again.")
        author_path()

def end_game():
    print("\nThank you for playing the Adventure Game!")
    print("I hope you enjoyed exploring the theme of free will through this story.")
    print("Goodbye!")

# Start the game
start_game()
