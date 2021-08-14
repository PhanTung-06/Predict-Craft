## CRAFT
## Getting started
### Install dependencies
#### Requirements
- PyTorch>=0.4.1
- torchvision>=0.2.1
- opencv-python>=3.4.2
- check requiremtns.txt
```
pip install -r requirements.txt
```

### Test instruction using pretrained model
- Download the trained models
 
* Run with  model
``` (with python 3.7)
python test.py --trained_model=[weightfile] --test_folder=[folder path to test images]
```

The result image and socre maps will be saved to `./result` by default.  
The file `submisstion.txt` will be saved to `./submiss` (Tempo Run - AI CLUB)
