# face-segmentation.Pytorch
![1](https://user-images.githubusercontent.com/92161283/214219180-64441ea6-1da5-456f-9ea4-0acb4094ecb3.png)

# Training
+ 1.Prepare training data: -- download [CelebAMask-HQ dataset](https://github.com/switchablenorms/CelebAMask-HQ)

   -- change file path in the prepropess_data.py and run
> python prepropess_data.py

If you do not wish to train the model, you can download [pre-trained model](https://drive.google.com/file/d/154JgKpzCPW82qINcVieuPH3fZ2e0P812/view) and save it in res/cp.

# evaluate using GPU
python test.py
## Results
