<div align="center">
	<img src=" https://raw.githubusercontent.com/CHeAT-C23-PS312/.github/main/profile/logo_cheat.png" width="192" />
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

## Introduction 👋
**Team ID: C23-PS312**

Hi everyone! We are from C23-PS312. We consist of 6 people and these are my team members:

|Name|Bangkit ID|Learning Path|LinkedIn
|--|--|--|--
|Pranarendra Dwikurnia|A304DSX1178|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranarendra08/)|
|Muhammad Nadhif Nabhan|A151DKX4177|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-nadhif-nabhan-651972198/)|
|Tedja Diah Rani Octavia|M304DSY0048|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tedjadiahrani/)|
|Amalia Hasanah|M304DSY1327|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amalia-hasanah-233a161a2/)|
|Destri Putri Natalia|C322DKY3820|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/destri-putri-natalia-50a10a21b/)|
|Firly Nuraulia Rahmah|C062DSY2956|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/firlynuraulia/)|

## Theme 🌾
Human Healthcare and Living Wellbeings



## Features
- **Recipe Reccomender**: In this feature, it will display recommendations for the top 5 recipes based on ingredients, with a chat interface.


## Architecture
The Coffee Leaf Detection App follows a client-server architecture. The client-side, implemented on Android, handles the user interface, image capturing, and displays the results. The server-side consists of the AI algorithms responsible for leaf detection and analysis.
The communication between the client and server occurs via RESTful APIs. The client sends leaf images to the server for processing, and the server returns the analysis results. The app utilizes machine learning models trained on a dataset of coffee leaf images to achieve accurate leaf detection and health assessment.

## Libraries Used
### Android
- **Jetpack Compose**: Jetpack Compose is a modern UI toolkit for building native Android user interfaces. It provides a declarative approach to UI development, making it easier to build dynamic and interactive user interfaces.
- **CameraX**: CameraX is an Android Jetpack library that provides a simple and consistent API for accessing camera functionality across different Android devices.
- **Coil**: Coil is an image loading library for Android that provides easy-to-use APIs for loading and displaying images efficiently.
- **DataStore**: DataStore is a data storage solution from the Jetpack libraries that offers a modern, reactive, and easy-to-use approach for persisting data in Android applications.
- **Room**: Room is an Android Jetpack library that provides an abstraction layer over SQLite, making it easier to work with a SQLite database in an Android app.
- **Retrofit**: Retrofit is a widely-used HTTP client library for Android that simplifies the process of making RESTful API requests to the server.
- **Paging 3**: Paging 3 is a Jetpack library that helps in loading and displaying large datasets from a data source incrementally, improving app performance and user experience.
- **Dagger Hilt**: Dagger Hilt is a dependency injection library for Android that simplifies the management of dependencies in an application.

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
- **Cloud Run**: Cloud Run is a serverless compute platform provided by Google Cloud. It allows you to run stateless containers in a fully managed environment, providing scalability and ease of deployment.
- **Firestore**: Firestore is a flexible, scalable, and fully managed NoSQL document database provided by Google Cloud. It enables real-time synchronization and offline support for data storage.
- **Cloud Storage**: Cloud Storage is a scalable and secure object storage service provided by Google Cloud. It allows you to store and retrieve large amounts of data, including images and other files.
- **App Engine**: App Engine is a fully managed serverless platform provided by Google Cloud. It enables you to build and deploy applications without managing infrastructure, providing auto-scaling and high availability.
- **Cloud Functions**: Cloud Functions is a serverless compute platform provided by Google Cloud. It allows you to write and deploy lightweight, event-driven functions that respond to cloud events and execute custom logic.
- **GoLang**: GoLang is a programming language developed by Google. It is known for its simplicity, efficiency, and strong support for concurrent programming.
- **Node.js**: Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. It allows you to build scalable and fast network applications, making it a popular choice for backend development.

Note: This list includes some of the major libraries used in the Recofferry App. It may not include all the libraries and dependencies used in the project.

