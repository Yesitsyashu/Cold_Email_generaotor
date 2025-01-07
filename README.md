# Cold_Email_generaotor
This is Llama 3.1 Powered Cold Email Generator for Companies as well as Job Seekers to Reach out for services.

## 📋 About the Project
Imagine being able to send personalized cold emails without spending hours crafting them! This AI-powered tool helps software service companies streamline their outreach by automatically generating cold emails from job postings found online. It’s like having a personal assistant who understands job descriptions and writes tailored emails for you.

## 🛠 What's Inside
Here’s a quick look at the technologies that make this tool work:
- **Llama 3.1**: Think of it as your smart assistant, crafting human-like emails.
- **ChromaDB**: Helps the tool remember and match job skills with relevant portfolios.
- **Langchain**: Connects all the pieces – web scraping, data handling, and more.
- **Streamlit**: Makes everything easy to use with a simple, interactive interface.

## 🚀 How It Works
1. **Input a Job URL**: Paste a job posting link into the tool.
2. **Scrape Job Details**: The tool grabs important information like skills and job descriptions.
3. **Store and Match Data**: It saves the data in ChromaDB and finds matching portfolio entries.
4. **Generate Email**: Llama 3.1 crafts a personalized email using the job info and portfolio.
5. **View Your Email**: The final email appears in the user-friendly Streamlit interface.

## 📦 How to Get Started
Want to try it out? Here’s how:
```bash
# Clone the repository
git clone https://github.com/yourusername/cold-email-generator.git
cd cold-email-generator

# Install dependencies
still pending to add
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## 🤝 Contributing
Have ideas to improve the tool? We'd love your input! Feel free to open an issue or submit a pull request.
