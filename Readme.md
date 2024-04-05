# BakeyBear


![i miss her..](banner.png)

### For you with love, Zuha
Have you ever found yourself pondering over a bunch of ingredients, unsure of what to make for a meal? This project is perfect for providing you with some ideas or guidance!

Welcome to the charming world of BakeyBear, where the gentle paw of a furry friend leads you on a culinary adventure filled with laughter, love, and the aroma of freshly baked goodies!

This is the readme for BakeyBear, a project that helps you reduce food waste and discover new recipes based on the ingredients you have on hand.

## What BakeyBear Does

BakeyBear utilizes the power of OpenAI's GPT-3.5 turbo model to generate recipes based on a list of ingredients you provide. It doesn't stop there! BakeyBear also uses DALL-E 3 to create a photorealistic image of the generated dish, giving you a visual representation of your culinary creation.

Here's how it works:

1. **Input your ingredients:** Provide a list of the ingredients you have available.
2. **Recipe Generation:** BakeyBear uses GPT-3.5 turbo to craft a detailed recipe using your ingredients. This includes the dish title, ingredients list, and step-by-step instructions.
3. **Food Visualization:** Leveraging DALL-E 3, BakeyBear generates a photorealistic image of the final dish, allowing you to see what your creation will look like before you cook it.

## Installation (Optional)

Note: This section is optional if you plan to run the code directly. You can skip this section if you're just browsing the functionalities of BakeyBear.

To run BakeyBear, you'll need to have Python and the necessary libraries installed. These include:

- `openai`
- `requests`
- `shutil`
- `PIL` (for image processing)

You can install these libraries using pip:

```bash
pip install openai requests shutil pillow
```
## Usage (Optional)

Note: This section is optional and provides a basic idea of how the code runs. You can skip this section if you're not interested in the technical details.

1. **Set your OpenAI API key:** Store your OpenAI API key as an environment variable or directly within the code (not recommended for security reasons).
2. **Create a list of ingredients:** Create a Python list containing the ingredients you have available.
3. **Run the BakeyBear script:** Execute the Python script that utilizes the `openai` library to interact with GPT-3.5 turbo and DALL-E 3. The script will process your ingredient list, generate a recipe, and create an image of the dish.

## Note on OpenAI API Usage

This project utilizes OpenAI's GPT-3.5 turbo and DALL-E 3 models, both of which have associated costs. Make sure you familiarize yourself with OpenAI's pricing structure before extensive use. You can find the pricing details here: [OpenAI Pricing](https://openai.com/pricing).

## DALL-E 3 Prompting Tips

To get the most out of your DALL-E 3 generated images, consider using these resources for crafting effective prompts:

- [A beginner’s guide to image generation with DALL-E 3  ](https://medium.com/centerforcooperativemedia/a-beginners-guide-to-image-generation-with-dall-e-3-4efd969ab8fb)
- [MLQ - DALL-E Prompts](https://www.mlq.ai/dalle-prompts/) 

## License

BakeyBear is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
