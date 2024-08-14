### Pseudocode
Here’s the pseudocode for the C++ program:

1. **Start**
2. Display "Welcome to the Calculator!"
3. Input the first number and store it in `result`
4. **Loop** until the user decides to stop:
   - Input an operation (`+`, `-`, `*`, `/`)
   - Input the next number
   - **If** operation is `+`:
     - `result = result + num`
   - **If** operation is `-`:
     - `result = result - num`
   - **If** operation is `*`:
     - `result = result * num`
   - **If** operation is `/`:
     - **If** `num` is not zero:
       - `result = result / num`
     - **Else**:
       - Display "Error: Division by zero!"
       - **Exit**
   - Display the current `result`
   - Ask the user if they want to continue (Yes/No)
   - **If** the user chooses "No":
     - **Exit Loop**
5. Display the final result
6. **End**
