# SHAREL Dataset
We propose a shadow-removal benchmark dataset (i.e., SHAREL) to explore the mutual influence of shadow removal and facial landmark detection tasks.

The Syn, Attack, Real shadow face data are available in [data](https://drive.google.com/drive/folders/1Ywe26YVfJVwh-XRLY8pZU0rq4Ki35X8h?usp=sharing).

- Syn data

Download data_syn_train.tar.gz and data_syn_test.tar.gz, decompress. Training data includes 1,500 images, testing data includes 689 * 81 images.

Organize data as follow:
```shell
--data_syn
  --train_A  # 300W-shaodw
  --train_B  # 300W-mask
  --train_C  # 300W-Original
  --train_params
  --target # for detection
  --test_A   # 300W-shaodw
  --test_B   # 300W-mask
  --test_C   # 300W-Original
```

- Attack data

Download data_attack.zip, data_attack_h.zip and data_attack_lu.zip, decompress. They are attack data for detectors SAN, HRNet, and LUVLi, respectively. Each is organized the same to Syn data. Training data includes 1,500 images, testing data includes 689 images.

- Real data

Download data_real.zip, decompress. This data is just for testing, which includes 100 images.
