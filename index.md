# DSC180A Methodology Assignment 4

**Name**: Sai Sri Lasya Yadlapati

**Email**: syadlapati@ucsd.edu

**Section**: A10

**Mentor**: Alex Warstadt

## Prompts

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic this quarter was comparing how different BabyLM models performed when trained on small datasets.
I was surprised by how much things like tokenization and pretraining settings changed the models' accuracy on language tasks.
It showed me that even with limited data, the way a model is built and trained makes a big difference.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation I would like to pursue for my Quarter 2 Project is to train and evaluate different BabyLM model submissions on
small datasets from different languages to see how language structure could affect performance, generalization, and efficiency.
This could help me understand whether models can learn universal patterns or memorize biases when data size is limited.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

A potential change I would make to the approach taken in my Quarter 1 Project is use a smaller dataset, instead of using a 100 million-token dataset, I would use the 10 million-token dataset instead.
Training on 10M will let us test true data efficiency, run more experiments faster, and make it easier to debug issues like overfitting.

**4. What other techniques would you be interested in using in your project?**
Other techniques I would be interested in using in my project are experimenting with curriculum learning, where the model first trains on simple phoneme sequences and then moves to more complex ones.
This could mimic how humans learn sounds and might improve convergence.
