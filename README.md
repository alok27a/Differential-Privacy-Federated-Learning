<p align="center">
<img src="https://user-images.githubusercontent.com/73957024/229306822-1e4dca90-067b-41ad-97e2-b13df128370f.png" alt="Logo" width="700">
</p>
</br>


<!-- PROJECT LOGO -->
<p align="center">
  <h1 align="center">PrivacyFed 🔏</h1>

  <p align="center">
    Differential Privacy in Federated Learning 
    <br />
    <a href="https://github.com/alok27a/Differential-Privacy-Federated-Learning"><strong>Explore the docs »</strong></a> 
    <br />
    •
    <a href="https://github.com/alok27a//Differential-Privacy-Federated-Learning/issues">Report Bug</a> 
    •
    <a href="https://github.com/alok27a//Differential-Privacy-Federated-Learning/issues">Request Feature</a> 
    •
  </p>
</p>

<!-- BADGES -->
<p align="center">
  <a href="https://github.com/alok27a/Differential-Privacy-Federated-Learning/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/alok27a/Differential-Privacy-Federated-Learning.svg?style=for-the-badge">
  </a>
  <a href="https://github.com/alok27a/Differential-Privacy-Federated-Learning/network/members">
    <img src="https://img.shields.io/github/forks/alok27a/Differential-Privacy-Federated-Learning?style=for-the-badge">
  </a>  
  <a href="https://github.com/alok27a/Differential-Privacy-Federated-Learning/stargazers">
    <img src="https://img.shields.io/github/stars/alok27a/Differential-Privacy-Federated-Learning?style=for-the-badge">
  </a>
  <a href="https://github.com/alok27a/Differential-Privacy-Federated-Learning/issues">
    <img src="https://img.shields.io/github/issues/alok27a/Differential-Privacy-Federated-Learning?style=for-the-badge">
  </a>
</p>


## 💡 Inspiration

Federated learning is a distributed machine learning approach that enables training of models on data collected from multiple devices without the need for centralizing data storage. Despite its advantages, federated learning raises concerns regarding data privacy and security. Differential privacy is a well-known technique that can be used to enhance privacy in federated learning. This technique involves the addition of random noise to the data before the model training process, which helps to conceal sensitive information about individual devices while maintaining the overall accuracy of the model. This paper discusses the application of differential privacy in federated learning to improve privacy and security. The paper explores the effectiveness of differential privacy techniques in enhancing privacy and the impact of the privacy budget parameter on model accuracy. The results demonstrate that differential privacy can significantly improve privacy in federated learning without sacrificing the accuracy of the model. Overall, the findings of this study provide a basis for improving privacy in federated learning by using differential privacy techniques.

## 📌 About the Product

* The proposed software for differential privacy in federated learning designed to implement differential privacy techniques in federated learning environments. The software includes algorithms for adding random noise to the data before model training, as well as mechanisms for managing the privacy budget parameter to balance privacy protection and model accuracy. The software would be designed to work seamlessly with existing federated learning frameworks, making it easy for organizations to adopt differential privacy techniques to enhance privacy and security in their machine learning systems.
* The software includes features for monitoring and evaluating privacy and security risks in federated learning environments. This would include tools for detecting potential privacy breaches and identifying vulnerabilities in the system. The software would provide real-time feedback on the effectiveness of differential privacy techniques in preserving privacy while maintaining model accuracy.
* Overall, the proposed software for differential privacy in federated learning is a critical tool for enhancing privacy and security in decentralized machine learning systems. Its use can help organizations leverage the collective intelligence of distributed devices while preserving the privacy and security of the data being used. The software has the potential to unlock new opportunities for machine learning while building trust among participants and ensuring the privacy and security of their data.

## ⚒️ How we built it ?

* Used the Tensorflow Federated to simulate a Federated Learning environment. Created a CNN Model using the Keras Sequential.
* Dataset used is MNIST Dataset which is images of handwritten text.

## 🧑‍💻 How it works ?

### Dividing the dataset among various clients

![image](https://user-images.githubusercontent.com/73957024/229307944-e5eccb7a-702f-42cb-9f4c-daecc54b1edf.png)

### Variying the noise multiplier and training for 50 rounds

![image](https://user-images.githubusercontent.com/73957024/229308010-712fa773-14bf-4dbd-8e2b-a87e03ed383c.png)

### Calculated noise multiplier using dp\_accounting for 50 rounds

![image](https://user-images.githubusercontent.com/73957024/229308051-a41a1580-5daa-4d5a-a535-d71e66cde7fd.png)

## 💪 Challenges we ran into

* The rounds associated to each noise multiplier took a lot of time to train because of which only 50 rounds were possible.
* Accuracy can be increased by increasing the number of rounds associated to each noise multiplier.


### Installation

Open the terminal in the folder in which you wish to clone the repository and enter the following command:

```
git clone https://github.com/alok27a/Differential-Privacy-Federated-Learning.git
cd Differential-Privacy-Federated-Learning
```
Can run the python notebook using Jupyter notebook or can be also run on Google Collab. 

## <img src="https://hpe-developer-portal.s3.amazonaws.com/uploads/media/2020/3/git-icon-1788c-1590702885345.png" width="32" height="32"> Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourAmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some YourAmazingFeature'`)
4. Push to the Branch (`git push origin feature/YourAmazingFeature`)
5. Open a Pull Request

## 👾 Contributors

### Alok Mathur

[`E-Mail`](mailto:alok27a@gmail.com)
[`LinkedIn`](https://www.linkedin.com/in/alok-mathur-5aab4534/)
