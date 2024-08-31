# Function to perform arithmetic operations
def arithmetic_operations(a, b, is_complex=False):
    print(f"Addition: {a} + {b} = {a + b}")
    print(f"Subtraction: {a} - {b} = {a - b}")
    print(f"Multiplication: {a} * {b} = {a * b}")
    print(f"Division: {a} / {b} = {a / b}")
    if not is_complex:
        print(f"Modulus: {a} % {b} = {a % b}")
    print(f"Exponent: {a} ** {b} = {a ** b}")
    print()  # Blank line for separation

# Integer values
int_a = 10
int_b = 3
print("Integer Operations:")
arithmetic_operations(int_a, int_b)

# Float values
float_a = 10.5
float_b = 3.2
print("Float Operations:")
arithmetic_operations(float_a, float_b)

# Complex values
complex_a = 2 + 3j
complex_b = 1 + 2j
print("Complex Operations:")
arithmetic_operations(complex_a, complex_b, is_complex=True)

