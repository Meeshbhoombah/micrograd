# micrograd
A miniature Autograd engine

## Getting Started
### Prerequisites
#### Graphviz
```
brew install graphviz
```

### Installation
1. Clone this repository
```
git@github.com:4x50urc3/x.git
```

2. `cd` into the repository
```
cd micrograd/
```

3. Create a virtual environment
```
python3 -m venv micrograd
```

4. Start the virtual envrionment
```
source micrograd/bin/activate
```

5. Install the packages from `requirements.txt` in the environment
```
pip3 install -r requirements.txt
```

6. Create a kernel in the environment
```
python3 -m ipykernel install --user --name=micrograd
```

### Development
If using `micrograd` in a root-level Jupyter Notebook, access it via `src`:
```
from src.engine import Value
```

