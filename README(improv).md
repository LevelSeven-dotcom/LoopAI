# LoopAI

LoopAI is an AI-powered web application firewall designed to enhance web server security by analyzing and classifying incoming HTTP requests in real-time. By leveraging machine learning techniques, it detects and mitigates potential security threats, protecting web applications from common attacks such as command injection (CMDi) and cross-site scripting (XSS). LoopAI provides a comprehensive solution for monitoring and securing web server traffic. It intercepts HTTP requests, applies advanced analysis techniques, and utilizes machine learning models for accurate classification, offering proactive protection against malicious activities.

## Features

- **Real-Time Request Analysis:** Intercepts and analyzes HTTP requests in real-time.
- **Machine Learning-Based Classification:** Utilizes machine learning models to accurately classify requests.
- **Proactive Threat Mitigation:** Detects and mitigates potential security threats, ensuring web application integrity and availability.
- **Comprehensive Traffic Monitoring:** Monitors web server traffic for suspicious patterns and behaviors.
- **Protection Against Common Attacks:** Specifically designed to protect against command injection (CMDi) and cross-site scripting (XSS).
- **Data Logging:** All data is logged in MongoDB for easy access and analysis.
- **Admin Panel:**
    **Home Page:** Shows an overview of attacks, total number of attacks, total users, geolocation, and past recent IP addresses.
    **Detection Page:** Displays the total number of blocked requests along with IP address, ISP, and geolocation details.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akashkampili1/loopAi.git
   cd loopAi
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage



## Video Guide



## Frequently Asked Questions (FAQ)

1. **What is LoopAI?**
	LoopAI is an AI-powered web application firewall designed to enhance web server security by analyzing and classifying incoming HTTP requests in real-time.

2. **How does LoopAI work?**
	LoopAI intercepts HTTP requests, applies machine learning-based classification techniques, and detects potential security threats such as command injection (CMDi) and cross-site scripting (XSS). It offers proactive protection by mitigating these threats and ensuring the integrity and availability of web applications.

3. **What are the key features of LoopAI?**
	- Real-time request analysis
	- Machine learning-based classification
	- Proactive threat mitigation
	- Comprehensive traffic monitoring
	- Protection against common attacks like CMDi and XSS
	- Data logging in MongoDB
	- Admin panel for easy monitoring and management

4. **How do I install LoopAI?**
	You can install LoopAI by cloning the repository from GitHub and installing the required dependencies using pip.

5. **Can LoopAI detect and block malicious requests?**
	Yes, LoopAI is capable of detecting and blocking malicious requests by analyzing their patterns and behaviors in real-time.

6. **What programming languages and libraries are used in LoopAI?**
	LoopAI is primarily built using Python. It utilizes libraries such as PyCaret for machine learning, Burp Suite for request parsing, and MongoDB for data logging.

7. **Is LoopAI suitable for all web server environments?**
	LoopAI can be integrated into most web server environments. However, custom configurations may be required based on specific server setups and requirements.

8. **How was LoopAI trained?**
	LoopAI was trained on a dataset of 6,000 HTTP requests, consisting of both good and bad requests. This dataset helps the model accurately classify and detect potential threats.

9. **Is LoopAI suitable for production environments?**
    While LoopAI is designed to enhance web server security, it's important to thoroughly test and validate its performance in your specific production environment before full deployment.

10. **Who can I contact for further questions or support?**
    For further questions or support, you can contact [Akash Kampili](mailto:akashkapili@gmail.com), [Vinyas Leonard Lobo](mailto:leovin.lobo@gmail.com), [Puneet Jain](mailto:puneetjain@gmail.com) or reach out to the project maintainers on the GitHub repository.

## Contributing

We welcome contributions to LoopAI! 
Please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or comments, please contact [Akash Kampili](mailto:akashkapili@gmail.com), [Vinyas Leonard Lobo](mailto:leovin.lobo@gmail.com), [Puneet Jain](mailto:puneetjain@gmail.com).

---

Thank you for using LoopAI! We hope this tool helps enhance the security of your web applications.
