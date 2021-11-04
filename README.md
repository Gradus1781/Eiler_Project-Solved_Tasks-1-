# Eiler_Project-Solved_Tasks-1-
# Trying to solve tasks from Eiler project site :) link: https://projecteuler.net/
def problem_1():
    """
    If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9.
    The sum of these multiples is 23.
    Find the sum of all the multiples of 3 or 5 below 1000.
    """
    sum_of_numbers = 0
    for number in range(1, 999 + 1):
        if number % 3 == 0 or number % 5 == 0:
            sum_of_numbers += number
    print(sum_of_numbers)  # 233_168

if __name__ == "__main__":
  problem_1()
