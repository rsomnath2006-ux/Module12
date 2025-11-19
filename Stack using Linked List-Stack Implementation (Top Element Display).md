# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
```
stack = []

a=input("Insert the first element:")
b=input("\nInsert the second element:")
c=input("\nInsert the third element:")
stack.append(a)
stack.append(b)
stack.append(c)
print('\nInitial stack: ' + str(stack))

for i in range(len(stack)):
    print(i,stack[i])
```
## Output

<img width="965" height="450" alt="Screenshot 2025-11-19 135806" src="https://github.com/user-attachments/assets/6f539b25-03b3-4988-970f-3c23148a0534" />

## Result
Thus,the program is executed successfully

