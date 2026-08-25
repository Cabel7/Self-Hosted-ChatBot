<b>How to Deploy:</b>
1. Download the repository with git clone
2. Open terminal terminal and direct it to the repository
3. run "streamlit run app.py". if not streamlit not installed run "pip install streamlit"

<b>Deploy your chatbot model:<b><br>
-> Setup ngrok account.
   1. get auth token from ngrok
   2. paste the auth token in ipynb file in place of <authtoken>
<br>

-> Depoy model on private server or cloud. <br>
   1. Select your best model from huggingface. <br>
   2. Paste url of model like this in ipynb file at last
      hf.co/<username>/<repository>:<quantization>  example: hf.co/DavidAU/Gemma-The-Writer-N-Restless-Quill-10B-Uncensored-GGUF:Q5_K_M
<br>

-> Run the .ipynb file on google colab or any gpu server. <br>

-> copy api URL from log or ngrok website. <br>

-> Open chat bot app and paste model name eg. "hf.co/DavidAU/Gemma-The-Writer-N-Restless-Quill-10B-Uncensored-GGUF:Q5_K_M and press enter". Then paste ngrok url in app eg. "https://b675-34-143-222-18.ngrok-free.app". <br>


<img width="1913" height="867" alt="Screenshot 2026-08-25 100914" src="https://github.com/user-attachments/assets/6f4e456d-1107-4100-8b29-81eb8d3b69bb" />


