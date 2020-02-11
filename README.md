# Super Resolution 

```
usage: main.py [-h] --upscale_factor UPSCALE_FACTOR [--batchSize BATCHSIZE]
               [--testBatchSize TESTBATCHSIZE] [--nEpochs NEPOCHS] [--lr LR]
               [--cuda] [--threads THREADS] [--seed SEED]
```
### Train

`python3 main.py --upscale_factor 3 --batchSize 4 --testBatchSize 100 --nEpochs 500 --lr 0.001`

### Super Resolve
`python3 super_resolve.py --input_image nst.jpg --model model_epoch_500.pth --output_filename nst.png`
