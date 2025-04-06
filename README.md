# Iris Flower Dataset Neural Network – Deep Dive into Training

![Top Language](https://img.shields.io/github/languages/top/gpt-null/template)
![Code Size](https://img.shields.io/github/languages/code-size/gpt-null/template)
![Last Commit](https://img.shields.io/github/last-commit/gpt-null/template)
![Issues](https://img.shields.io/github/issues/gpt-null/template)
![Contributors](https://img.shields.io/github/contributors/gpt-null/template)
![License](https://img.shields.io/github/license/gpt-null/template)

**A StatQuest-inspired implementation of a neural network, trained on the Iris dataset, with a focus on understanding cross-entropy loss and backpropagation.**

---

## References

### Core Concepts

- **[Neural Networks Part 6: Cross Entropy](https://www.youtube.com/watch?v=6ArSys5qHAU&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=12)**  
  Introduction to the cross-entropy loss function used in classification.

- **[Neural Networks Part 7: Cross Entropy Derivatives and Backpropagation](https://www.youtube.com/watch?v=xBEh66V9gZo&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=13)**  
  Explains how to derive and implement the gradients of cross-entropy during backpropagation.

### Additional Background on Backpropagation

- **[Neural Networks Part 2: Backpropagation – Main Ideas](https://www.youtube.com/watch?v=IN2XmBhILt4&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=5)**  
  A high-level overview of how backpropagation works in neural networks.

### Technical Deep Dives

- **[Backpropagation Details Part 1: Optimizing Three Parameters Simultaneously](https://www.youtube.com/watch?v=iyn2zdALii8&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=6)**  
  Shows how optimizers update multiple parameters during training.

- **[Backpropagation Details Part 2: Going Bonkers with the Chain Rule](https://www.youtube.com/watch?v=GKZoOHXGcLo&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=7)**  
  A deeper exploration of the chain rule and how it's applied during backpropagation.

---

![Visualization of Iris dataset layers and outputs](assets/iris_dataset_image.png)

---

## To-Do

- [ ] Build a custom optimizer.
- [ ] Refactor and clarify the backpropagation code.
- [ ] Improve the structure and clarity of this README.
- [ ] Clarify the mathematical explanations using example data.
- [ ] Improve the written explanations throughout the codebase.
- [ ] Clean the assets folder
---

### LICENSE

```markdown
MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```