# **Pistachio Classification using CNN**  

Dataset: https://www.kaggle.com/datasets/muratkokludataset/pistachio-image-dataset

This project uses a **Convolutional Neural Network (CNN)** to classify two types of pistachios:  
- **Kirmizi Pistachio**  
- **Siirt Pistachio**  

## **📌 Libraries Used**  
- `TensorFlow` – for deep learning  
- `NumPy` – for numerical operations  
- `Matplotlib` – for visualization  
- `OpenCV` – for image processing  
- `Pillow (PIL)` – for loading images  

## **📂 Dataset Structure**  
```
Pistachio_Image_Dataset/
│── Kirmizi_Pistachio/
│── Siirt_Pistachio/
│── Examples/  (for prediction)
```

## **🚀 How It Works**  
1. **Train the Model** using CNN on the dataset.  
2. **Load the Model** and predict new images.  
3. **Preprocess Images** (resize, normalize) before passing to the model.  
4. **Make Predictions** on new images from the **Examples/** folder.  

## **💻 Running the Project**  
1. **Train the model**  
   ```python
   model.fit(train_generator, epochs=10)
   model.save("pistachio_model.h5")
   ```
2. **Predict new images**  
   ```python
   model = load_model("pistachio_model.h5")
   prediction = model.predict(img_array)
   ```

## **📊 Accuracy**  
- Training Accuracy: **XX%**  
- Validation Accuracy: **YY%**  

✅ The model can successfully classify pistachios.  

⭐ *Star this repo if you found it useful!* 🚀
