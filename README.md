# Test MViT on K600

```
conda activate slowfast

cd cd /nobackup/users/bowu/code/STAR_code/slowfast/

python tools/run_net.py \
  --cfg configs/Kinetics/MVIT_B_32x3_CONV.yaml \
  DATA.PATH_TO_DATA_DIR /nobackup/projects/public/kinetics600/ \
  TEST.CHECKPOINT_FILE_PATH ./ckpt/k600.pyth \
  TRAIN.ENABLE False \
```

