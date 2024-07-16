# Myntra Hackerramp
This is team `WE3` submission for `Myntra Hackerramp 2024`

# TryOn 
It is a virtual clothing try on tool. Given a profile image and a source image containing cloth, it applies the cloth to your profile image and let you see how does it look on you as if you were actually wearing it.

# How does it work ?
It works by extractng cloth from source image and fitting into your profile image.
Under the hood, it uses two separate deep learning models:
Cloth segmentation model: Custom Deeplab model to extract cloth from source image.
Pose estimator model: Pretrained Openpose body_25 model used to locate shoulder points.
Extracted cloth is blended into profile image based on shoulder location.

# Screenshots
![Screenshot 2024-07-13 123808](https://github.com/user-attachments/assets/3ce73007-6301-4f29-b355-9ee4553abcac) 
![resize-17211520291617883774Screenshot20240713132308](https://github.com/user-attachments/assets/a8deed05-3919-4480-a56e-efe44e957bfe)




# Key Features
- Supports all kinds of upper wear clothes for both men and women.
- Accurate cloth extraction and fitting.
- Simple, elegent and easy to use web app.

# Future Scope
- **Enhanced Personalization**: Implementing machine learning algorithms to offer more personalized fashion recommendations.
- **Expanded Collaboration Features**: Allowing users to collaborate on fashion projects, create challenges, and vote on outfit ideas.
- **Sustainability Insights**: Offering insights into the sustainability of users’ wardrobe choices and suggesting eco-friendly alternatives.

