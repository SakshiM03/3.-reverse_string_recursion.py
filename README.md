# 3.-reverse_string_recursion.py
def reverse_string(s):
    # Base case
    if len(s) == 0:
        return s

    # Recursive case
    return reverse_string(s[1:]) + s[0]


text = "HELLO"

result = reverse_string(text)

print("Original string:", text)
print("Reversed string:", result)

Output:

Original string: HELLO
Reversed string: OLLEH
