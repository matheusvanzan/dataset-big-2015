# Dataset BIG 2015

This repository is meant to automate the creation of multiple datasets from the BIG 2015 dataset.
From the original dataset, you can perform text processing tasks to generate new data.

BIG 2015 dataset consists of malware samples classified into 9 different classes.
It was originally released in the Microsoft Malware Classification Challenge (BIG 2015).
You can download it from the [Kaggle repository](https://www.kaggle.com/c/malware-classification/data).

Disclaimer: this repository doesn't contain the datasets (the original dataset is almost half a terabyte uncompressed), only instructions so you can create them on your own.

## Dataset operations

You can perform multiple tasks to create a new dataset.

Possible Tasks [WIP]:
- Sample Limit
- Character removal
- Opcode instructions

- You can combine multiple tasks in order to create a new dataset.

### Sample Limit

Sample dataset with only first samples of each class.

```
$ python createdt.py --limit 100
```

