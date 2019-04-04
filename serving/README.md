# Environments
Ubuntu : 18.04.2<br>
Python : 3.6.7<br>
Tensorflow : 1.13.1<br>
TensorFlow ModelServer : 1.13.0-rc1+dev.sha.f16e777<br>
```shell
# 'tensorflow_model_server' command installation :

echo "deb [arch=amd64] http://storage.googleapis.com/tensorflow-serving-apt stable tensorflow-model-server tensorflow-model-server-universal" | sudo tee /etc/apt/sources.list.d/tensorflow-serving.list && \
curl https://storage.googleapis.com/tensorflow-serving-apt/tensorflow-serving.release.pub.gpg | sudo apt-key add -
apt-get update && apt-get install tensorflow-model-server
```

# Training
```shell
python train.py
```
### Saved model path
/tmp/1

# Serving
```shell
python train.py
```
