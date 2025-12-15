Link to the website: https://cloth-tryon.onrender.com/final1.html

Cloth-TryOn: Virtual Cloth Studio & Body Swap for Clothing Brands

Problem Statement

Clothing brands and e-commerce businesses face significant challenges in creating high-quality product images for their online catalogs. Traditional photoshoots require hiring models, photographers, studios, and logistics, which are expensive, time-consuming, and resource-intensive. This process can cost thousands per session, delay product launches, and limit the ability to showcase garments on diverse models or in varied poses. Additionally, updating catalogs or swapping models in existing images often demands new shoots or manual editing, further increasing costs and waste.

Solution

Cloth-TryOn provides an AI-powered web tool specifically designed for clothing brands to generate professional product images without physical photoshoots. By uploading clothing images and selecting or providing models, brands can quickly create realistic visuals of garments being worn. The body swap feature allows seamless replacement of models in existing images, enabling rapid customization. This reduces production costs dramatically (up to 90% in similar AI tools), speeds up time-to-market, and promotes efficiency—perfect for scaling e-commerce catalogs.

Project Explanation

Cloth-TryOn is a lightweight, browser-based application built with HTML for structure, CSS for styling and responsive design, and JavaScript for interactive functionality, file handling, and API calls. The heavy lifting—realistic image generation for try-ons and body swaps—is handled by the Gemini API (Google's multimodal AI), which processes uploaded images to produce high-quality, photorealistic results.

Key Features:

1.Virtual Cloth Try-On: Upload a clothing item image (e.g., flat lay or on hanger) and a model photo; the AI generates the model wearing the garment realistically, accounting for fit, draping, and lighting.

2.Body Swap: Upload an existing photoshoot image and a new model/body image; the AI swaps the original model while maintaining pose, background, and composition.

3.Intuitive web interface for easy uploads, previews, and downloads.

How It Works:

1.Users select a mode (Try-On or Body Swap) via the HTML interface.

2.JavaScript manages file uploads and constructs prompts/data for the Gemini API.

3.The API generates the output image using advanced generative capabilities.

Results are displayed instantly in the browser for review and download.
This approach makes it accessible and cost-effective for brands to produce studio-quality images on demand.        

Examples of AI-powered outputs:

Flat clothing → Model in outfit

Existing shoot → Swapped model

<img width="1278" height="529" alt="Screenshot 2025-12-15 150753" src="https://github.com/user-attachments/assets/85296250-ff9e-4f3b-a1ee-c74e5ed03971" />

<img width="1322" height="529" alt="Screenshot 2025-12-15 145951" src="https://github.com/user-attachments/assets/bb3560d6-351d-4b5d-9f07-47f9b8122e48" />


For deployment, host on Render or rvercel.

The llm model used for this was gemini 2.5 flash image.

Technologies Used

HTML5, CSS3, JavaScript (vanilla/ES6+)

Gemini API (for AI image generation and manipulation)

Inspired by the growing use of AI in fashion to streamline content creation (e.g., tools reducing photoshoot costs by 90%).
