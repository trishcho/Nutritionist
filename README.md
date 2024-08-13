
## Authors

- [@Trishul](https://www.github.com/trishcho)


# Health Management App

![200w](https://github.com/user-attachments/assets/829da11e-d9c0-48b7-a164-ee2b844763af)


The Health Management App is a Streamlit-based application that integrates the Google Gemini Pro Vision API to analyze images of food and calculate the total calorie content. This application allows users to upload food images, upon which it provides detailed nutritional information, including calorie counts for each food item.


## Features



- Image Upload: Users can upload images of food items in JPG, JPEG, or PNG formats.
- Calorie Calculation: After image analysis, the app calculates the total calories of the food items and provides detailed nutritional information.
- Responsive Interface: Built using Streamlit, the interface is user-friendly and responsive, suitable for various devices.
## Setup

Clone the repository:

```bash
git clone https://github.com/trishcho/Nutritionist.git
cd Nutritionist
```

Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

```

Install the required packages:

```bash
pip install -r requirements.txt

```

Set up environment variables:

Create a .env file in the root of your project and add your Google API key:

```bash
GOOGLE_API_KEY=your_google_api_key_here


```

Run the application:
```bash
streamlit run app.py


```
