<div align="center">
	<img src="https://raw.githubusercontent.com/CHeAT-C23-PS312/.github/main/profile/logo_cheat.webp" width="300" height="300"/>
	<h3 align="center">CHeAT</h3>
	<p align="center">
		CHeAT is an Android application that utilizes artificial intelligence to recommend food recipes by inputting food ingredients available at home, which makes this application easier for users because this application is chat-based.
		<br />
		<!-- <a href="#how-to-use-the-app-"><strong>How to Use The App »</strong></a> -->
	</p>
</div>

## Screenshots
<!-- <--<div>
	<img src="" width="200" />
	<img src="" width="200" />
	<img src="" width="200" />
	<img src="" width="200" />
</div>--> 

## Team Member
**Team ID: C23-PS312**

|Name|Bangkit ID|Learning Path|LinkedIn
|--|--|--|--
|Pranarendra Dwikurnia|A304DSX1178|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranarendra08/)|
|Muhammad Nadhif Nabhan|A151DKX4177|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-nadhif-nabhan-651972198/)|
|Tedja Diah Rani Octavia|M304DSY0048|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tedjadiahrani/)|
|Amalia Hasanah|M304DSY1327|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amalia-hasanah-233a161a2/)|
|Destri Putri Natalia|C322DKY3820|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/destri-putri-natalia-50a10a21b/)|
|Firly Nuraulia Rahmah|C062DSY2956|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/firlynuraulia/)|

## Theme
Human Healthcare and Living Wellbeings


## Features
- **Recipe Recommender**: In this feature, it will display recommendations for the top 5 recipes based on ingredients, with a chat interface.
- **Recipe Recommender Detail**: In this feature, it will display each recipe recommendation in detail based on ingredients. With this feature, the user can see the details of ingredients, total calories and instructions of the recipe.

## Architecture
The CHeAT application follows a client-server architecture. The client-side, which is implemented on Android, handles registering, logging in, and sending the ingredients entered by the user to the server-side stage of the chatbot.Communication between the client and server occurs through a RESTful API. The server-side manages user requests, communicates with the database, and interacts with the machine learning model (chatbot) to provide recipe recommendations. The client application displays the information received from the server-side to the user.

## Libraries Used
### Android
- **Library1**: sksksksksksk
- **Library2**: hayoapahayo


### Machine Learning
- **NumPy**: It is a fundamental library for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently.
- **TensorFlow**: TensorFlow is an open-source machine learning framework used for training and deploying deep learning models. It provides a rich ecosystem of tools and libraries for building and deploying machine learning applications.
- **Keras**: Keras is a high-level neural networks API written in Python. It provides a user-friendly interface for building and training deep learning models on top of TensorFlow.
- **Sys**: Sys is a library module in Python provides various functions and variables that are used to manipulate different parts of the Python runtime environment.
- **io**: This library provides core tools for working with input and output operations, such as reading and writing data.
- **Json**: This library enables the encoding and decoding of JSON (JavaScript Object Notation) data. It provides functions for working with JSON-formatted data, which is commonly used for exchanging data between a server and a web application.
- **String**: It provides various functions and constants for working with strings in Python. This library includes utility functions for string manipulation, such as formatting, searching, and modifying strings.
- **Tokenizer** : It is a class provided by Keras for tokenizing text data. Tokenization is the process of breaking text into individual words or subwords, which are often used as input for natural language processing models.
- **Pad_sequences** : It is a function provided by Keras for padding sequences. In natural language processing tasks, sequences of variable lengths (such as sentences) need to be transformed into fixed-length sequences to be processed by neural networks. The pad_sequences function adds padding (usually zeros) to the sequences to make them of equal length.
 

### Cloud Computing/Backend
- **Axios**: Axios is a  JavaScript library that allows you to make HTTP requests from both the browser and Node.js. It provides an easy-to-use and consistent API for performing asynchronous operations and handling responses.
- **Bcrypt**: bcrypt is a password-hashing function/library commonly used in software development for securely storing and verifying passwords. It is designed to be slow and computationally expensive, which makes it resistant to brute-force attacks.
- **MySQL**: MySQL is an open-source relational database management system (RDBMS) that uses Structured Query Language (SQL) for managing and manipulating databases. It is one of the most popular and widely used databases in the world.
- **App Engine**: App Engine is a fully managed serverless platform provided by Google Cloud. It enables you to build and deploy applications without managing infrastructure, providing auto-scaling and high availability.
- **Node.js**: Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. It allows you to build scalable and fast network applications, making it a popular choice for backend development.

Note: This list includes some of the major libraries used in the CHeAT App. It may not include all the libraries and dependencies used in the project.

