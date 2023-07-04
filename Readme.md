# Struc-Bench
Welcome to Struc-Bench! We employ the same finetune.py and generate.py as used in alpaca-lora. Moreover, we have divided generate.py into three distinct categories: table, html, and latex. The scoring results can be found in the score directory, with scores derived from GPT housed in the gpt_score subdirectory. The remaining evaluations are segregated into table_scores.py, html_scores.py, and latex_scores.py, respectively.

## How to use table_scores.py
You can use the command:
```
python table_scores.py ref_file_path pred_file_path test_type
```
For example:
```
python table_scores.py table_test.json table_test_output.txt ourtest
```

## Our data
You can access our data in the google drive: [data](https://drive.google.com/drive/folders/1XjlwdqdQxPQzTh0vqPsdUmpY5z5aD-v6?usp=drive_link)