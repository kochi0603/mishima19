# mishima19
 - git clone https://github.com/gmichalo/UmlsBERT.git
 - cd UmlsBERT
 - conda create -n py37umlsbert python=3.7
 - conda activate py37umlsbert 
 - pip install -r requirements.txt


 - git clone https://github.com/cambridgeltl/sapbert.git
 - cd sapbert
 - conda create -n py38sapbert python=3.8
 - conda activate py38sapbert
 - pip install -r requirements.txt
 - conda install faiss-gpu -c pytorch
 - conda install wandb
 - cd train
 - ./pretrain.sh 0,1



- conda create -n py39sd2 python=3.9
- conda activate py39sd2
- conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
- pip install diffusers transformers ftfy accelerate

# Stable-diffusion v2.1
  # huggingfaceにアカウントを作ってログインしてから、
  - https://huggingface.co/stabilityai/stable-diffusion-2-1
  # v2-1_768-ema-pruned.ckpt をダウンロードする
  # proxy環境の場合、以下も通信可能にしておく
    # https://cdn-lfs.huggingface.co
    # https://huggingface.co
