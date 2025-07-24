# AI-Powered Data Analytics Demo

This demo showcases how AI can accelerate and enhance data analysis workflows.

## Setup Instructions

### 1. Environment Setup
```bash
pip install openai pandas numpy matplotlib seaborn plotly python-dotenv jupyter
```

### 2. API Key Configuration
1. Create a `.env` file in this directory
2. Add your API key:
   ```
   OPENAI_API_KEY=your_actual_api_key_here
   ```
3. **Important**: Never commit the `.env` file to version control!

### 3. Getting an API Key

#### Option A: OpenAI API
1. Visit [OpenAI Platform](https://platform.openai.com/)
2. Create an account or sign in
3. Navigate to API Keys section
4. Generate a new API key
5. Add billing information (pay-per-use model)

#### Option B: Azure OpenAI
1. Access through your organization's Azure subscription
2. Request access to Azure OpenAI Service
3. Use provided endpoint and API key
4. Update the demo notebook for Azure configuration

### 4. Running the Demo
```bash
jupyter notebook ai-analytics-demo.ipynb
```

## Demo Content

The demo covers:
- **AI-assisted data cleaning** - Automatic quality issue detection
- **Natural language analysis** - Query data using plain English  
- **Code generation** - Create analysis scripts through prompts
- **Insight extraction** - AI-powered pattern recognition
- **Automated reporting** - Generate executive summaries

## Data Privacy Note

This demo uses synthetic datasets for learning purposes. In production:
- Be cautious about sharing sensitive data with AI services
- Review your organization's AI usage policies
- Consider using anonymized or synthetic data for training

## Troubleshooting

### Common Issues:
1. **API Key errors**: Verify `.env` file format and key validity
2. **Rate limits**: OpenAI has usage limits; wait or upgrade plan
3. **Import errors**: Ensure all packages are installed correctly

### Support:
- Check OpenAI status page for service issues
- Review API documentation for error codes
- Test with simple prompts first before complex analysis

---

**Ready to experience AI-powered analytics? Let's dive in!** 🚀
