# Installing PyTorch, TensorFlow, and JAX on Apple Silicon

Create a virtual environment and update pip:

```
$ conda create --name jaxmetal python=3.11
$ conda activate jaxmetal
```

Install Torch:

```
$ pip install torch torchvision torchaudio
```

Install TensorFlow:

```
$ pip install tensorflow tensorflow-macos tensorflow-metal
```

Install JAX:

```
$ pip install jax-metal ml_dtypes==0.2.0 jax==0.4.26 jaxlib==0.4.26
```

