docker run -p 8502:8501 --name=fafa -v YOUR_PATH/image-classification-web-app/saved_model/:/models/horse-vs-human/1 -e MODEL_NAME=horse-vs-human tensorflow/serving
