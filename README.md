# Meeting-Minutes-Maker  
(From Ed Donner's Udemy course)
A tool that creates meeting minutes and action items from audio using both open- and closed-source LLMs.  
For converting audio to text (transcribing audio), OpenAI's open source Speech Recognition model 'Whisper' (whisper-medium.en) has been used (along with Huggingface pipelines API). Also, the use of closed source 'gpt-4o-mini-transcribe' model has been shown (OpenAI API key needs to be purchased and included in the .env file, or added to Google Colab's 'secrets' field)  


- Download the following mp3 file (or any other):  
  https://www.google.com/url?q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1N_kpSojRR5RYzupz6nqM8hMSoEF_R7pU%2Fview%3Fusp%3Dsharing
- Create a Huggingface token and add it to .env file/Google colab secrets (key-value pair). The key name should be 'HF_TOKEN'
- For using the Llama 3.1 model, navigate to this webpage and agree with all the necessary terms and conditions:
  https://www.google.com/url?q=https%3A%2F%2Fhuggingface.co%2Fmeta-llama%2FMeta-Llama-3.1-8B




