import math
import time

n = int(input("Insert number n: "))

# Start the timer
start_time = time.time()

limit = math.isqrt(n)

print(f"\nFinding factor until √n = {limit:,}")
print("-" * 40)

for i in range(2, limit + 1):

    # Continuous informations
    if i % 100_000_000 == 0:
        print(f"Trying out: {i:,}")

    if n % i == 0:
        p = i
        q = n // i

        print(f"\n✓ Factor found!")
        print(f"p = {p:,}")
        print(f"q = {q:,}")

        # Stop the timer
        end_time = time.time()

        # Rounds the time to two decimals
        duration = round(end_time - start_time, 2)

        print(f"Time: {duration} seconds")

        break
else:
    print("\nThe number got no factor.")
