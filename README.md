# Practicum-2024-UNIQLO-Tagging

The goal of this project is to be able to utilize Google Gemini's API in order to create tags/descriptions for specific clothing images. In addition to generation a general description of the image, we are exploring different applications that these tags can be used. Currently, we are working three main applications - Seasonal/Holiday, Geographic Relevance, and Holiday. Each use case has its onw unique prompt that will allow for specific tags and descriptions to be generated. 

To run the code:
 * Clone the repositiory: git clone https://github.com/TianyuWu-Henry/Practicum-2024-UNIQLO-Tagging.git
 * You will need a Gemini API key:
* Naviagte to https://ai.google.dev/
* You will need to sign in using a google account (Northwestern emails do not work)
* On the left hand side click Get an API Key
* Click Create API Key
* In the Project Search use: Generative Language Client
* Then click Generate API key in existing project
* Copy this key to add to env file in next steps 
 * Navigate to repository in terminal: cd Practicum-2024-UNIQLO-Tagging
 * Create a .env file that is at the same level as the Gemini Integreation Jupyter notebook
 *     vim .env
 *     Change to insert mode: I 
 *     Add in your API key: API_KEY = YOUR_API_KEY
 *     Save and quit: press esc, :wq, enter/return
  
 * Install all required libraries from the requirements.txt: pip install -r requirements.txt
 * Ensure the image you want to use is at the same level (Currently the script is using the ON31.webp
 * Launch Jupyter notebook: jupyter notebook
 * Run all cells in the jupyter notebook 
