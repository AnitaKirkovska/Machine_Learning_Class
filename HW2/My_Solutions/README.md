# HW2 Solutions
In the homework I used 50 and 100 epochs tests, varying my learning rate between lr=0,0003 and lr=0.0005 using:
```
*   Different 'Naked' models
*   1xDropout
*   2xDropout
*   Data Augmentation
*   L2 Normalization
*   Batch Normalization
*   All combined 
```
# Results

## Simple hold-out validation

**With 50 epochs:**
```
*   Accuracy wit 'Naked' model = 71.54%
*   Accuracy with Dropout = 75.55%
*   Accuracy with 2 Dropouts = 75.79%
*   Accuracy with Data Aug = 78.84 %
*   Accuracy with L2 and Batch Normalization = 66.94 %
*   Accuracy with all = 62.71%
```
**With 100 epochs:**

```
*   Accuracy with all = 62.71 %
*   Accuracy with Data Aug = 75.94 % 
```

**Test with the best validation accuracy model:**
```
*   Accuracy with Data Aug = 73.06 %
```

## K-fold hold-out validation
```
