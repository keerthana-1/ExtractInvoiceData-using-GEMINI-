# Extract Invoice data using Google GEMINI

- Dependencies: Installs and imports necessary libraries, including Google Generative AI, IPython for display, PIL for image processing, and standard Python libraries.
- Markdown Formatter: Converts text to a Markdown format, replacing bullet points with asterisks and adding indentation.
- API Key: Sets up the API key for accessing Google Generative AI services.
- Generative Model: Uses the Gemini model to generate a response based on input text, an image, and a prompt.
- Image Preparation: Converts an uploaded image to JPEG format and packages it into the format required for the generative model.
- Input Prompt: Defines the context and instructions for the generative model.
- Image Path: Loads the image from a specified path and prepares it for input.
- Queries: Uses the get_gemini_response function to ask specific questions about the invoice image and print the responses.
