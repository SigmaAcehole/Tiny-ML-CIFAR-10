## Environment
- Tested on Windows 11 and Ubuntu 22.04 LTS
- Python 3.11
- CUDA 12.1

## Setup

1. Clone this repository.    
```bash
git clone https://github.com/SigmaAcehole/Tiny-ML-CIFAR-10.git
cd Tiny-ML-CIFAR-10/
```

2. Create the directory to store the NATS-Bench database.

```bash
mkdir .torch
```

3. Download the NATS-Bench database (1 GB) from this [gdrive link](https://drive.google.com/file/d/1scOMTUwcQhAMa_IMedp9lTzwmgqHLGgA/view).

4. Move this database inside `.torch` and unzip it.

```bash
cd .torch
tar -xvf NATS-sss-v1_0-50262-simple.tar
cd ..
```

5. Install all requirements.

```bash
pip install -r eshan_sabhapandit_requirements.txt
```
If there are dependency issues, please use a virtual machine. Example (Linux):

```bash
python3 -m venv myenv
source myenv/bin/activate
```

6. Run the jupyter notebook. It can be run with and without training the model. More details are mentioned in the notebook.

## References
[NATS-Bench repository](https://github.com/D-X-Y/NATS-Bench)
