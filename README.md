# NER-tagging-using-hidden-markov-model

## Installed packages
```
pip install pandas numpy
```

1. Run through notebook, the first 80% of data would be use as traning, rest 20% would be use as gold standards.
2. the result would be written in result_file.txt , 20% of data would be written in golden_ans_file.txt
3. Evaluate by running 
```
python evalNER.py golden_ans_file.txt result_file.txt
```

