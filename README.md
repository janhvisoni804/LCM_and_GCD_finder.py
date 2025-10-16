import math
test_case= int(input("Enter the number of test cases: "))
for i in range(1, test_case + 1):
    num1, num2 = map(int, input(f"Enter num1 and num2 for test case {i} (space separated): ").split())
    gcd = math.gcd(num1, num2)
    lcm = (num1 * num2) // gcd
    print(f"Test case {i}: GCD of {num1} and {num2} is {gcd}, LCM of {num1} and {num2} is {lcm}")
