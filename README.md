# 🧠 Practical 2: Neural Networks on MNIST

A university practical exploring the **MNIST handwritten digits dataset** and building a **first neural network classifier** with PyTorch.

## 📚 What I Did

* **Explored the data**: counted how many samples of each digit appear in the training and test sets, to check whether the classes are balanced
* **Built a neural network**: a simple feed forward model with one hidden layer, ReLU activation and optional dropout, mapping 28×28 images (784 inputs) to 10 digit classes
* **Tested my work**: verified each function with doctests and the provided automated tests

## 🎯 Key Takeaways

* Why checking class balance matters before training a model
* How hidden layer size and dropout affect a model's ability to generalise
* Writing small, testable functions with clear expected outputs

## 🛠️ Tech Stack

`Python` `PyTorch` `NumPy` `Matplotlib` `Jupyter Notebook`

## 🚀 Running It

```bash
cd practical2-template-main/practical2-template-main
pip install torch numpy matplotlib opencv-python
python week2.py        # runs the doctests
python week2_test.py   # runs the automated tests
```

The full instructions are in [`Practical Week 02.ipynb`](practical2-template-main/practical2-template-main/Practical%20Week%2002.ipynb).

## 👩‍💻 Author

**Elsa Ngoc Dang**: Bachelor of IT (Business Analysis), Macquarie University · [LinkedIn](https://www.linkedin.com/in/ha-bao-ngoc-dang/)
