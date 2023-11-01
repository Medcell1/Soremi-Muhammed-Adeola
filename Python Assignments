import re

### Question 1
inputString = "This is a sample string with some numbers like 12345 and 67890."


pattern = r'\d+'


matches = re.findall(pattern, inputString)


if matches:
    print("Matches found:")
    for match in matches:
        print(match)

    replacement = "X"
    modified_string = re.sub(pattern, replacement, inputString)
    print("Modified String:")
    print(modified_string)
else:
    print("No matches found.")


def reverse_string_and_remove_numbers(input_text):
    reversed_string = input_text[::-1]
    reversed_string_without_numbers = ''.join(char for char in reversed_string if not char.isdigit())

    return reversed_string_without_numbers


#######

####question 2


input_string = "Hello12World45"


result = reverse_string_and_remove_numbers(input_string)


print("Reversed string without numbers:", result)
