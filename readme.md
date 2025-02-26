# CodeAgent with Paper Finder and Time Zone Tools

You can use it in HuggingFace Spaces: [here](https://huggingface.co/spaces/a-zelka/First_agent_template)

This repository contains a **CodeAgent** powered by Hugging Face's SmolAgents framework. It includes various tools such as:

- **Paper Finder**: Fetches the latest papers from arXiv based on specified topics.
- **Time Zone Tool**: Retrieves the current time for a given timezone.
- **Final Answer Tool**: Ensures structured responses from the agent.

## Features

- Searches for **recently published** papers on arXiv based on user-defined topics.
- Retrieves **accurate local time** for any specified timezone.
- Uses an **Qwen/Qwen-2.5-Coder-32B-Instruct** for enhanced reasoning.
- Integrates with **Gradio UI** for easy interaction.

## Notes & Troubleshooting

- If the **paper finder tool** does not return recent papers, check that the **arXiv API sorting** is correctly set to `submittedDate`.
- If you encounter **rate limits**, consider adding delays between API requests.
- Ensure your **secrets are correctly set** in Hugging Face Spaces.

## Future Improvements

- Add **PDF summarization** for retrieved papers.
- Implement **advanced search filters** (e.g., by author, institution).
- Improve **error handling** for API failures.

---

Developed with ❤️ using **SmolAgents, Gradio, and 🤗Hugging Face**.
