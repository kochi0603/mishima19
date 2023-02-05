# mishima19
- conda create -n py39sd2 python=3.9
- conda activate py39sd2
- conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia

# Stable-diffusion v2.1
  # huggingfaceにアカウントを作ってログインしてから、
  - https://huggingface.co/stabilityai/stable-diffusion-2-1
  # v2-1_768-ema-pruned.ckpt をダウンロードする
  # proxy環境の場合、以下も通信可能にしておく
    # https://cdn-lfs.huggingface.co
    # https://huggingface.co
