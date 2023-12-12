FROM tensorflow/serving:latest

ARG SAVED_MODEL_PATH

WORKDIR /models/$SAVED_MODEL_PATH

COPY saved_model.pb .
