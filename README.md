# movie-recommendation
# This is a program that recommends movies based on the genre you like.

print("Welcome to My Movie Recommender!")
print("You can choose from: Action, Comedy, Drama, Horror, Sci-Fi")

#  list of movies for each genre
action = ["Dhoom", "Body Gaurd", "War"]
comedy = ["Phir Hera Pheri", "Dhamaal", "Step Brothers"]
drama = ["Kapoor and Sons", "Life in a Metro", "The Godfather"]
horror = ["The Conjuring", "1920", "Tumbbad"]
sci_fi = ["Inception", "Interstellar", "The Matrix"]

# Asking user to enter their favorite genre
genre = input("Enter your favorite genre: ")
genre = genre.lower()  # just in case they type in caps

# Checking which list to show
if genre == "action":
    print("You might like these action movies:")
    for movie in action:
        print("-", movie)
elif genre == "comedy":
    print("You might like these comedies:")
    for movie in comedy:
        print("-", movie)
elif genre == "drama":
    print("Here are some good drama movies:")
    for movie in drama:
        print("-", movie)
elif genre == "horror":
    print("Scary movies you might enjoy:")
    for movie in horror:
        print("-", movie)
elif genre == "sci-fi" or genre == "sci fi":
    print("Cool Sci-Fi movies for you:")
    for movie in sci_fi:
        print("-", movie)
else:
    print("Oops! I don't know that genre ")

print("Hope you enjoy the movie marathon!") 
