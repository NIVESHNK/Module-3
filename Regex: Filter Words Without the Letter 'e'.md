# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```

## Output

<img width="527" height="178" alt="517996877-83789f2b-6760-48e1-b547-cddb8d564e94" src="https://github.com/user-attachments/assets/a0436fef-1ff5-47d2-b326-83a52f1be69f" />

## Result
Thus the program executed successfully.
