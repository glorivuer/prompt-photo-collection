ChatGPT 官方 app 生成不了这种图了
![image](https://github.com/user-attachments/assets/ffc5e64d-8c96-4b1b-a6c4-42b3b2801014)


developers.googleblog.com/en/generate-images-gemini-2-0-flash-preview/



from google import genai
from google.genai import types
client = genai.Client(api_key="GEMINI_API_KEY")
response = client.models.generate_content(
   model="gemini-2.0-flash-preview-image-generation",
   contents=(
       "Show me how to bake a macaron with images."
   ),
   config=types.GenerateContentConfig(
        response_modalities=["TEXT", "IMAGE"]
   ),
)
