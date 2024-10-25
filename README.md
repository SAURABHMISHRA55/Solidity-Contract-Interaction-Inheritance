## **Solidity Contract Interaction & Inheritance**

Welcome to the **Simple Storage Project** repository! This project demonstrates essential Solidity concepts, including deploying multiple contracts, contract interaction, inheritance, and overrides.

---

## **Getting Started**

To try out the code, follow these steps:

1. **Go to [Remix](https://remix.ethereum.org/):**  
   Remix is an online IDE for Solidity smart contracts.

2. **Create New Files:**  
   Create three new files in the same folder:
   - `SimpleStorage.sol`
   - `StorageFactory.sol`
   - `ExtraStorage.sol`

3. **Copy the Code:**  
   Paste the respective code into each new file in Remix.

4. **Compile the Contracts:**  
   In Remix, click the **"Compile"** button for each contract.

5. **Deploy a Contract:**  
   Select the contract you want to deploy and hit **"Deploy"**.

You are now ready to interact with the contracts and explore how they work!

---

## **What I Learned**

### **1. Importing Contracts into Other Contracts**
- **Composability:** Helps break down and organize code by reusing contracts across multiple files.

### **2. The `new` Keyword in Solidity**
- Used to **deploy new contract instances** from within other contracts.

### **3. Importing Code in Solidity**
- The `import` statement allows developers to **reuse and maintain consistency** across contracts.

### **4. Interacting with Other Contracts**
- **Interacting with contracts requires two key things:**
  1. **ABI (Application Binary Interface):** Defines the functions accessible in a contract.
  2. **Address:** Specifies where the contract is deployed on the blockchain.

### **5. Inheritance and Overrides in Solidity**
- **Inheritance:** One contract can inherit and reuse logic from another.
- **`virtual` and `override` Keywords:**
  - **`virtual`:** Marks a function as overridable.
  - **`override`:** Modifies an inherited function in a child contract.

---

## **Reference**

This project is based on lessons from the **freeCodeCamp Solidity and Blockchain Development Course**.  
Watch the full tutorial here:  
[Solidity, Blockchain, and Smart Contract Development Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ)

---

Feel free to modify the code and experiment with your own ideas to deepen your understanding of **Solidity and smart contracts**. Happy coding! 🎉

---

## **License**

This project is **MIT licensed**, meaning you are free to use, modify, and distribute the code as you see fit.