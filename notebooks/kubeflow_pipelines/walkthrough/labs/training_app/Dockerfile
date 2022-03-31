
FROM gcr.io/deeplearning-platform-release/base-cpu
RUN pip install -U fire cloudml-hypertune scikit-learn==0.20.4 pandas==0.24.2

# TODO
#WORKDIR {TRAINING_APP_FOLDER}
ADD train.py /app
