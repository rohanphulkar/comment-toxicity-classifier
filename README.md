# README for Toxic Comment Classification using Bidirectional LSTM

## Description
This code uses a Bidirectional LSTM model to classify toxic comments from non-toxic ones. The dataset used is the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle.

## Screenshots

![App Screenshot](https://res.cloudinary.com/rohanphulkar/image/upload/v1681499852/github/Screenshot_2023-04-15_004713_fwwdb4.png)

## Installation
To run this code, you will need to install TensorFlow and Kaggle. You can do this using the following commands:

```python
import tensorflow as tf
!pip install kaggle
```

You will also need to upload your Kaggle API key using the following command:

```python
from google.colab import files
files.upload()
```

## Usage
To use this code, you will need to download the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle and place it in a folder named "train". Then, you can simply run the code in a Jupyter notebook or in Google Colab.

## Examples
Here is an example of how to use the `score_comment` function to classify a comment:

```
score_comment("Hi! I am back again! Last warning! Stop undoing my edits or die!")
```

This will return the following output:
```
toxic: True
severe_toxic: False
obscene: True
threat: False
insult: True
identity_hate: False
```
## Contributing

If you would like to contribute to this code, you can submit bug reports or pull requests on the GitHub repository.

## License

This code is licensed under the MIT license.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://phoenixdev.online/) 

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohanphulkar)

[![instagram](https://img.icons8.com/fluency/48/null/instagram-new.png)](https://www.instagram.com/complex_rohan)
