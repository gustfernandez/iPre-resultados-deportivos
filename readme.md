
# Setup entorno Pytorch
El entorno de desarrollo es de Conda.


# Crear y activar entorno
```bash
conda create --prefix ./env python=3.8
conda activate ./env
```

# Instalar dependencias
```bash
pip3 install torch torchvision torchaudio
```

```bash
conda install jupyter pandas numpy matplotlib scikit-learn tqdm pytorch-tabnet
```

# Ejecutar Jupyter
```bash
jupyter notebook
```