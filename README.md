# new-years-eve-resolution-sha-256

Find output of code and concatenate to “lbgdsc-___”

def lastRemaining(n):
        if n == 1:
            return 1
        return 2 * (n // 2 - lastRemaining(n // 2) + 1)
def main():
    number = 147
    value = lastRemaining(number)
    print(value)
main()

Solution:- The output would get added with "lbgdsc-_____" and that would be the next repo.
