# CNN Classifier for Capuchin Calls

## Key Achievements

- Designed and trained a Convolutional Neural Network to identify Capuchin Calls, achieving 98% weighted-F1 score and 7.67 ms mean inference time.
- Applied model optimisation techniques to allow model to run on edge devices, reducing model size from 150 MB to 4 MB.
- Sucessfully handled severe class imbalance using audio augmentation techniques.

## Summary

This is a custom-trained CNN model that is used to identify Capuchin bird calls. It has been trained on a small dataset obtained from [Kaggle](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbElFU1J1VmVBWGdHYXNoZGFUSGhTRlI0ajJuQXxBQ3Jtc0tra1p4NEFfaGZQSXBMd29OWUhpajl0X1g0ZUJQZVBIOGZ1Y0lDQWh1RUVTZ1RhUGRkaXd5dGFmdFUtUnhWMldObkh6OHR0d251Qi00VjgwV1RvYW11YmhZdk8wWmo0Y1UtYjlPOFhObDJud2QtZ1dLcw&q=https%3A%2F%2Fwww.kaggle.com%2Fkenjee%2Fz-by-hp-unlocked-challenge-3-signal-processing&v=ZLIPkmmDJAc),

As dependencies, we have:

- tensorflow==2.19.0
- numpy
- matplotlib
- pandas
- scikit-learn
