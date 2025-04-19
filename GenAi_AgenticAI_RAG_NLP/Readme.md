# Setting Up the Environment

Follow these steps to create a Python 3.10 environment using Conda and install the required dependencies:

## 1. Create a Conda Environment

```bash
conda create --name myenv python=3.10
```

## 2. Activate the Conda Environment

```bash
conda activate myenv
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 4. Verify Installation

```bash
python --version
pip list
```

## 5. Reactivate the Conda Environment (if needed)

```bash
conda deactivate
conda activate myenv
```
