## Create conda environment

```bash
 conda create --prefix ./venv python=3.11.0
```

## Activate the environment

```bash
conda activate venv/
```

## Load requirements

```bash
pip install -r requirements.txt
```

## Install tensorflow

### GPU

```bash
pip install tensorflow'[and-cuda]'
 ```

 ### CPU
 ```bash
 pip install tensorflow
 ```

 ## Validate Tensorflow

 ### GPU

 ```bash
 python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
 ```

 ## References

1. https://www.tensorflow.org/install/pip