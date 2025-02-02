# FlowTest

[![Release Notes](https://img.shields.io/github/release/FlowTestAI/FlowTest)](https://github.com/FlowTestAI/FlowTest/releases)
[![Linkedin](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/flowtestai)
[![Twitter Follow](https://img.shields.io/twitter/follow/FlowTestAI?style=social)](https://twitter.com/FlowTestAI)
[![Chat on Discord](https://img.shields.io/badge/chat-Discord-7289DA?logo=discord)](https://discord.gg/Pf9tdSjPeF)

Leverage GenAI to convert your customer's interactions with your product into runnable flows all via natural language and simple drag and drop. Generated flows not only test the functional correctness of your product but also the time it takes your customers to perform these actions together.

- Step 1: Import your openAPI spec and describe your prodcut flow in natural language to our AI.
- Step 2: Add an evaluate node at the end via simple drag and drop to check the final output.
- Step 3: Run the created flow for a success/falure and observe the generated logs and timing info.
- Step 4: Save and Export these runnable chains in json format and share with others.
- Step 5: Have a beer! 🍺

![alt text](public/flowtest_1.gif)

## 👨‍💻 Developers
FlowTest has 2 major components -
-   `server`: Node backend to serve API requests
-   `src`: React frontend

### Prerequisite
-   Install npm
    ```bash
    npm install -g npm
    ```
-   NodeJS >= 18.0.0

### Setup
1. Clone the repository
    ```bash
    git clone https://github.com/FlowTestAI/FlowTest.git
    ```
2. Go into repository folder
    ```bash
    cd FlowTest
    ```
3. Install all dependencies of all modules:
    ```bash
    npm install
    ```
4. Rename `.env.example` to `.env` and enter your cerdentials, for instance
    ```bash
    OPENAI_API_KEY={API_KEY_VALUE}
    PORT=3500
    ...
    ```
5. Start the app:
    ```bash
    npm start
    ```
    You can now access the app on [http://localhost:3500](http://localhost:3500)

## 🙋 Support

Feel free to ask any questions, raise problems, and request new features in [discussion](https://github.com/FlowTestAI/FlowTest/discussions)

## 📄 License
Source code in this repository is made available under the [MIT License](LICENSE.md).
