# **Gemini APPs Showcase by AILab**

Welcome to the AILab showcase of creative and useful applications built with the Google Gemini API. This repository serves as a collection of our projects and a source of inspiration for other developers.

## **1: Image-to-Prompt Generator**

Our first featured application is a powerful tool for artists, designers, and AI enthusiasts.

* **Function**: Upload an image and the app will generate high-quality, tailored prompts for various AI image and video generation platforms.  
* **Supported Models**: Includes presets for Midjourney, Stable Diffusion, Nano Banana, Sora, Veo, WAN and more.  
* **Live Demo**: [Image-to-Prompt Generator](https://gemini.google.com/share/4b65455e5922)

## **Getting Started & Local Development**

You can explore our apps via the live demo links. If you wish to run them on your local machine, follow these steps.

### **1\. Clone the Repository**
```
git clone https://github.com/1038lab/Gemini-APPs.git  
cd Gemini-APPs
```
### **2\. API Key Setup (For Local Use)**

Our applications are designed to work seamlessly in environments where the API key is automatically provided. However, for local development, you must provide your own Gemini API key. **Do not hardcode your key directly into the .html file.**

The recommended approach is to use a .env file and a simple backend proxy.

**A. Create a .env file:**

* In the root of the project, create a file named .env.  
* Add your API key to this file like so:  
  GEMINI\_API\_KEY="your\_actual\_api\_key\_here"

**B. Use a Server-Side Proxy:**

* The frontend JavaScript should **NOT** access the .env file directly.  
* You will need to set up a simple backend (e.g., using Node.js with Express) that reads the API key from the .env file and makes the call to the Google Gemini API on behalf of the frontend. This keeps your API key secure.

## **Contributing**

We welcome contributions\! If you've built an interesting app using the Gemini API, feel free to submit a pull request to have it featured in our showcase. Please ensure your submission includes a brief description and a live demo link.

## **License**

This project is licensed under the GPL 3.0 License.
