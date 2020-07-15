# The implementation of encoder decoder with attention
## Model Architecture
This repo, I will implement an Encoder-Decoder with Attention using (Gated) Recurrent Networks,
very closely following the original attention-based neural machine translation paper [Neural Machine Translation by Jointly Learning to Aligh and Translate](https://arxiv.org/abs/1409.0473) by Bahdanau et al. 2014
### How to train 
```
python main.py --epochs 20 --emsize 256 --nhid 256
```

### How to finetune from a pretrained model
``python main.py --epochs 20 --resume=True --ckp=<path_to_save_checkpoints>``