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
