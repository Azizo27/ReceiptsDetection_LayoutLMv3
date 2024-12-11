# ReceiptsDetection_LayoutLMv3

Welcome to the **ReceiptsDetection_LayoutLMv3** repository! This project has been created for a technical interview.
It uses CORD dataset to detect total amount TTC on receipt document with Transforms approach (LayoutLMv3)

## Setup Instructions

### 1. Clone the Repository

```sh
git clone https://github.com/Azizo27/ReceiptsDetection_LayoutLMv3
cd ReceiptsDetection_LayoutLMv3
```

### 2. Set Up the Virtual Environment

On Windows:

```sh
python -m venv env
```

optional: ```Set-ExecutionPolicy Unrestricted -Scope Process```

```sh
.\env\Scripts\activate
```

On Linux

```sh
python3 -m venv env
source env/bin/activate
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
pip3 install torch --index-url https://download.pytorch.org/whl/cu118
```


### 4. Setup Kernel

```sh
python -m ipykernel install --user --name=env --display-name "cuda-layoutlmv3"
```

### 5. Open JupyterNotebook
```sh
jupyter notebook
```