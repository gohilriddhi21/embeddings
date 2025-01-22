# Embeddings

## What Are Embeddings?

Machine learning algorithms require numerical input, but many data types (like text, sound, images or videos) are not naturally numerical. One-hot encoding was a way to convert this non-numeric data into a numerical format that algorithms could process.

## Why to use Embeddings?

One-hot encoding is one way in which you convert non-numeric data into numeric data. 
Embeddings are a way of representing complex unstructured data (like images, text, videos, or even songs) in the form of vectors (arrays of floating point numbers). These vectors are designed to capture the meaning of the text, images, and videos. Simply put, these vectors capture the underlying features and relationships within the data. The magic happens when similar data points (e.g., songs, images, or products) are represented by vectors that are closer together in a multi-dimensional space. Think of it as mapping your favourite songs or products to a "vector galaxy," where everything with a similar vibe gravitates toward each other.


For example:

#### One Hot encoding:

<img src="https://github.com/gohilriddhi21/embeddings/blob/main/images/one_hot_encoding.png">

As you can see, one-hot encoding doesn’t provide any semantic relationship between the words. For example, “cat” and “dog” are treated as entirely unrelated.


#### Word Embedding:

<img src="https://github.com/gohilriddhi21/embeddings/blob/main/images/embeddings.png">

In this case, "cat" and "dog" will have similar embeddings because they are related. Their embeddings will reflect this semantic relationship. The system can understand that they are related, unlike one-hot encoding, where they are treated as completely distinct.


## Use Case:
Let’s say you search for “pizza with olives” on the platform. The system will first analyze your search term and compare it to the image embeddings of all available pizzas to find those that visually contain olives. Additionally, it will use text embeddings to ensure the descriptions of those pizzas mention olives as a topping.

If you have a history of ordering vegan dishes, the platform may recognize this preference and suggest Vegan Pizza with olives. This recommendation would be based on both your past orders (which are encoded as embeddings) and the system's understanding of the current search query, combining both the visual and textual data.

In essence, the system doesn’t just match your query to a list of pizzas with olives. It smartly blends your past preferences, the visual features of the dish, and its description to provide a more personalized and relevant recommendation.
