## Flickr Datasets

This repository contains Flickr image-to-text pair datasets (8k and 30k). Each image contains 5 captions.

#### Flick8k
To download flickr8k dataset, run following code,

```shell
wget "https://github.com/sorohere/flickr-dataset/releases/download/v0.1.0/flickr8k-dataset.zip"

unzip -q flickr8k-dataset.zip -d ./dataset
rm flickr8k-dataset.zip

echo "Downloaded Flickr8k dataset successfully."
```

#### Flickr30k
To download flickr30k dataset run following code,

```shell
wget "https://github.com/sorohere/flickr-dataset/releases/download/v0.1.0/flickr30k-dataset-part_00"
wget "https://github.com/sorohere/flickr-dataset/releases/download/v0.1.0/flickr30k-dataset-part_01"
wget "https://github.com/sorohere/flickr-dataset/releases/download/v0.1.0/flickr30k-dataset-part_02"

cat flickr30k-dataset-part_* > flickr30k-dataset.zip
unzip -q flickr30k-dataset.zip -d ./dataset

rm flickr30k-dataset-part_00 flickr30k-dataset-part_01 flickr30k-dataset-part_02
rm flickr30k-dataset.zip

echo "Downloaded Flickr30k dataset successfully."
```
