# Neural_Network_Charity_Analysis

Overview of the analysis:
Beks has come a long way since her first day at that boot camp five years ago—and since learning about neural networks earlier this week! She's now ready to put her abilities to use by assisting the foundation in predicting where to spend. With my background in machine learning and neural networks, I'll utilise the attributes in the dataset to assist Beks in developing a binary classifier that can predict whether applications would be successful if they are financed by Alphabet Soup. Beks got a CSV containing more than 34,000 groups that have received financing from Alphabet Soup throughout the years from Alphabet Soup's business team.

Results:

What variable(s) are considered the target(s) for your model?

The "IS SUCCESSFUL" column is used as the model's aim.

What variable(s) are considered to be the features for your model?

Below are variables considered to be the features of the optimized model:

-“APPLICATION_TYPE”

-“CLASSIFICATION”

-“AFFILIATION”

-“ORGANIZATION”

-“STATUS”

-“INCOME_AMT”

-“ASK_AMT”

What variable(s) are neither targets nor features, and should be removed from the input data?

Below are variables that are neither targets nor features, and should be removed from the input data:

- "EIN"

- "NAME"

- "USE_CASE"

- "SPECIAL CONSIDERATIONS"


How many neurons, layers, and activation functions did you select for your neural network model, and why?

I chose the following neurons, layers, and activation functions.

Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs

In order to boost the predicted accuracy to 75%, I chose each of them at random using the trial-and-error approach. Initially, I just raised the number of neurons to test whether a simple solution would result in a higher degree of prediction accuracy, but the problem was not simple enough to be linearly separated, as was thought.As a result, in each successive effort, I decided to increase the layers, nodes, and epochs, based on the principle of "going for depth," which claims that "Empirically, more depth does tend to result in better generalisation for a wide range of tasks."

Were you able to achieve the target model performance?

I was unable to meet the 75 percent model performance goal.

In hindsight, or possibly on a subsequent try, I would have raised the number of layers to incorporate greater depth, since this would allow the model to build more shapes and samples for categorization, improving predicted accuracy.
What steps did you take to try and increase model performance?

To improve the model's performance, I did the following steps:

For all subsequent model setups, remove any extra features (noisy variables).

Increase the number of layers

Increase or reduce the number of neurons in the extra layers

Each effort may be broken down into the following categories.

Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs

Below are screenshots of the code used to increase model performance.

<img width="810" alt="Screenshot 2022-03-25 082855" src="https://user-images.githubusercontent.com/92246505/160121420-d2bbe686-b805-49a0-984c-b557239c2861.png">

<img width="774" alt="Screenshot 2022-03-25 083422" src="https://user-images.githubusercontent.com/92246505/160121677-cca37c83-4870-4037-936f-c0c411667442.png">

<img width="792" alt="Screenshot 2022-03-25 083629" src="https://user-images.githubusercontent.com/92246505/160121980-f8d047e7-17a3-432a-a709-258d3fa8d43d.png">

<img width="784" alt="Screenshot 2022-03-25 083918" src="https://user-images.githubusercontent.com/92246505/160122324-84e2a614-6376-45c2-ac40-1eaf79314143.png">

<img width="960" alt="Screenshot 2022-03-25 090127" src="https://user-images.githubusercontent.com/92246505/160125544-f682427b-f85b-407b-883b-cf319a4cfe11.png">

<img width="885" alt="Screenshot 2022-03-25 090324" src="https://user-images.githubusercontent.com/92246505/160125874-6875fd54-60b6-4686-ad8f-aa8993e393ff.png">

<img width="904" alt="Screenshot 2022-03-25 090439" src="https://user-images.githubusercontent.com/92246505/160126060-1b7f53c6-88d0-4077-b3f3-365f58fc4cf5.png">

<img width="884" alt="Screenshot 2022-03-25 090647" src="https://user-images.githubusercontent.com/92246505/160127033-2f65826b-cee0-416d-8209-fef70009ffbe.png">

<img width="908" alt="Screenshot 2022-03-25 091421" src="https://user-images.githubusercontent.com/92246505/160127465-c682fbec-5d06-471d-99da-c20448161325.png">

<img width="885" alt="Screenshot 2022-03-25 090324" src="https://user-images.githubusercontent.com/92246505/160128259-6fb40f50-433e-41ef-9c1d-18b82cf190c3.png">

<img width="913" alt="Screenshot 2022-03-25 091850" src="https://user-images.githubusercontent.com/92246505/160128279-6ddc4e2a-fdf9-4e6a-b337-07a499b5240d.png">



<img width="884" alt="Screenshot 2022-03-25 090647" src="https://user-images.githubusercontent.com/92246505/160128598-36883907-7b0d-4da9-a0eb-579cb7e77e77.png">




Summary:

Attempt 1: Predictive Accuracy Percentage: 72% Loss Metric: 56%

Attempt 2: Predictive Accuracy Percentage: 72% Loss Metric: 56%

Attempt 3: Predictive Accuracy Percentage: 72% Loss Metric: 57%
Recommendation:

While none of these models attained a predicted accuracy of 75%, I would propose increasing the amount of hidden layers to add more depth in the model to tackle the categorization problem in future tries. Increasing the depth (layers) of the model would allow for a greater creation of predictability shapes and patterns; increasing the layers by a large margin may create an upper bound, from which I could fine tune the model by varying the number of nodes, or by decreasing the number of layers from the upper bound, using a trial-and-error method, to achieve a predictive accuracy of 75%.
