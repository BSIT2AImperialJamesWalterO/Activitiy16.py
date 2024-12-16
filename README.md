# Activitiy16.py
for r in range(1, 6):
  for s in range(1, r + 1):
    print(" ", end="")
  for t in range(1, r - 1):
    print("*", end="")
  for u in range(1, r + 1):
    print("*", end="")
  print()
