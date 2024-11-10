# VS-Code-Online---code-server# Run VS Code in Google Colab or Kaggle with Ngrok Tunnel 🚀

This notebook allows you to run **Visual Studio Code (VS Code)** directly in **Google Colab** or **Kaggle** using **ngrok** to tunnel the remote environment to your browser. Whether you're working on a deep learning model, data analysis, or just need an IDE in the cloud, this setup is perfect for you!

## Features 🌟
- Launch **VS Code** from your Google Colab or Kaggle environment.
- Use an **ngrok tunnel** to access VS Code from your browser.
- **No authentication required** for simple access (ideal for testing and personal use).

## Prerequisites ⚙️
- Google Colab or Kaggle Notebook
- **Ngrok token** and **Ngrok Domain** for tunneling
- A stable internet connection

## Quick Start 🚀

### For Google Colab
1. Click on the following link to open the notebook directly in Google Colab:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1khRseXeB-kyibTZIU7cdN8NSY2SUC4dU?usp=sharing)     
2. Run the cells sequentially, and it will automatically set up the ngrok tunnel and launch VS Code on port `8188`.

### For Kaggle
1. Click on the following link to open the notebook directly in Kaggle:
[![Run in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/deephansda/vs-code-online/edit)
   
3. Similarly, execute the cells to set up the ngrok tunnel and run VS Code.

## How It Works 💻

- **Ngrok Setup**: The notebook connects to ngrok using your **ngrok token** and sets up a tunnel on port 8188. The generated URL is used to access the VS Code instance remotely.
  
- **Code Server**: Using `code-server`, we deploy VS Code in your browser. With no authentication required, you can start coding right away from your cloud environment.


