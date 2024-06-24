# 💬 Chat with LLaMA LLMs

![Demo](https://github.com/misbahiradat/Testing/blob/0cc871c25ad4b703a75f474d30ac19889c135a0f/pic1.png)

## Project Description
This project provides an interactive chat interface using state-of-the-art LLaMA large language models (LLMs). The app leverages models such as `Llama3-8b-8192`, `Llama3-70b-8192`, `Mixtral-8x7b-32768`, and `Gemma-7b-It` to deliver high-quality language understanding and generation. The application supports various token limits and configurations for optimal performance and accuracy.

## Features
- Choose from multiple LLaMA models for varied capabilities.
- Persistent chat history for easy reference to past interactions.
- User-friendly interface built with Streamlit.
- Secure API key management using environment variables.

## Demo
Check out the live demo [here](https://github.com/misbahiradat/Testing/blob/78b64f63331cce7e67513677084cc551c59a6e50/pic2.png).

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/yourrepo.git
    cd yourrepo
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    - Create a `.env` file in the root directory.
    - Add your API key in the `.env` file:
      ```env
      groq_api_key=your_api_key
      ```

## Usage

1. **Run the application**:
    ```bash
    streamlit run app.py
    ```

2. **Interact with the chat interface**:
    - Open your browser and go to `http://localhost:8501`.
    - Select a LLaMA model from the sidebar.
    - Enter your query in the input box and hit "Submit".
    - View the response and chat history.

## Screenshots

![Chat Interface](https://github.com/misbahiradat/Testing/blob/78b64f63331cce7e67513677084cc551c59a6e50/pic2.png)

## Contributing
Feel free to submit issues or pull requests. We welcome all contributions to enhance the functionality and user experience of this project.

## License
This project is licensed under the MIT License.

## Contact
For questions or support, please reach out to [misbahiradat99@gmail.com](mailto:misbahiradat99@gmail.com).
