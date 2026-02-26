## Environment
- Tested on Windows 11 and Ubuntu 22.04 LTS
- Python 3.11

## Setup

1. Clone this repository.    
```bash
git clone https://github.com/SigmaAcehole/Tiny-ML-CIFAR-10.git
```

2. Create the directory to store the NATS-Bench database.

```bash
mkdir .torch
```

3. Download the NATS-Bench database (1 GB) from this [gdrive link](https://drive.google.com/file/d/1scOMTUwcQhAMa_IMedp9lTzwmgqHLGgA/view).

4. Move this database inside `.torch` and unzip it.

```bash
tar -xvf NATS-sss-v1_0-50262-simple.tar
```

5. Install all requirements. If there are dependency issues, please use a virtual machine.

```bash
pip install -r requirements.txt
```

6. Run the jupyter notebook. It can be run with and without training the model. More details are mentioned in the notebook.





git clone --recurse-submodules https://github.com/D-X-Y/AutoDL-Projects.git XAutoDL
pip install XAutoDL/
pip install nats_bench
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install onnx onnxruntime onnxruntime-tools