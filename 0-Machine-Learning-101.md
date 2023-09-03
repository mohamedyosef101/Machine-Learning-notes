## What is Machine Learning?
A subdomain of computer science that focuses on algorithms which help computer learn from data without explicit programming.


### Types of Machine Learning

1. <b> Supervised learning </b> - uses labeled input (input has a corresponding output label) to train models and learn outputs.

2. <b> Unsupervised learning </b> - uses unlabeled data to lean about patterns in data.

<img style="background: #fff" src="https://static.javatpoint.com/tutorial/machine-learning/images/unsupervised-machine-learning-1.png" width="480">

3. <b>Reinforcement learning </b> - agent learning in interacitve environment based on rewards and penalties.

<img src="https://www.guru99.com/images/1/082319_0514_Reinforceme2.png" width="480">

## Supervised Learning
It's called supervised because the process of an algorithm learning from the training dataset can be thought of as a teacher supervising the learning process.

<img src="https://i0.wp.com/neptune.ai/wp-content/uploads/2022/10/Self-Supervised-Learning-and-Its-Applications_2.png" width="480">

<b>Some key characteristics of supervised learning:</b>

* <span style="color: #00a1ff">Requires labeled training data</span> - this means humans must manually label the data before feeding it to the algorithm. This can be expensive and time consuming.

* <span style="color: #00a1ff">Used for classification and regression problems.</span> Common models include linear regression, logistic regression, neural networks, support vector machines.

* <span style="color: #00a1ff">Models learn by examining many examples</span> and attempting to find patterns between the input data and the corresponding labels. The model is iteratively improved until it can accurately predict the label for new unlabeled data.

* <span style="color: #00a1ff">Performance is evaluated by splitting the labeled data into training and test sets.</span> The model only sees the training data during learning. Model accuracy on the test set indicates how well it will perform on new data.

* <span style="color: #00a1ff">Goal is to approximate the mapping function</span> so well that when new input data is fed into the model, it can accurately predict the output variables.

#### <b>ONE-<span style="color: #fc4444;">HOT</span> ENCODING</b>
Transforms categorical features into binary vectors that capture the presence of each possible value. 

##### <b>How it works</b>:

Let's say you have a categorical feature like color which can take on 3 possible values: red, green, or blue.

*For example, if the color is red, it becomes:*

- <span style="color: #fc4444">Red</span>: 1
- <span style="color: #4CAF50">Green</span>: 0
- <span style="color: #00a1ff">Blue</span>: 0

The "one" in the binary vector represents the color being encoded. This encoding allows algorithms like neural networks and logistic regression to work with categorical data.

### <b> <span style="color: #00a1ff">Supervised</span> Learning Tasks</b>

1. <b>Classification</b> - Predict dicrete classes = (Binary or Multiclass)

2. <b>Regression</b> - predict continuous values