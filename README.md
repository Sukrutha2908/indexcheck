vwords = ["apple", "banana", "cherry", "apple", "date"]

# 1. Find the index of the first occurrence
first_index = -1
for i in range(len(vwords)):
    if vwords[i] == "apple":
        first_index = i
        break

# 2. Find all indices
all_indices = []
for i in range(len(vwords)):
    if vwords[i] == "apple":
        all_indices.append(i)

print("First occurrence of 'apple':", first_index)
print("All occurrences of 'apple':", all_indices)
