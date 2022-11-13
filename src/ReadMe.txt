> Open the source code in Jupyter notebook to see the execution done.
> The code should be present in the same path as the dataset
for example - C:\Users\Sharukh\Desktop\Project\Sharukh Project\chest_xray
All dataset and code must be in same solder as 'chest_xray'
>install wandb and other libraries and create account if not present in wandb.
>Be careful with paths. Specify local path approriately for the following:
ModelCheckpoint(filepath='/Users/panka/Sharukh Project/chest_xray/checkpoint/{epoch:02d}-{accuracy:.5f}.h5',
                        save_weights_only=True, 
                        save_best_only = True,
                        verbose=1, 
                        mode='min', 
                        monitor='loss'
                        )
