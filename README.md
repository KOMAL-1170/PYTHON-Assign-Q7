# PYTHON-Assign-Q7
# Define the dictionary
D = {1: "One", 2: "Two", 3: "Three", 4: "Four", 5: "Five"}

# Open a file to write
with open("dictionary_output.txt", "w") as file:
    for key, value in D.items():
        file.write(f"{key}, {value}\n")

print("Dictionary written to 'dictionary_output.txt' successfully.")

