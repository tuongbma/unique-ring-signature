# Unique Ring Signature

##Before you run
Install SageMath v9.2 from [here](https://www.sagemath.org/download.html)


## Follow these step to run the code:
**Step 1:** Open git folder by SageMath Notetbook
**Step 2:** Set up ring signature:
- `n`: number of bits
- `N`: number of members in the ring (N=2^n)
- `q`: base on security parameter, default is 2048 bits

These parameters can be set up in `main()` function in `main.ipynb`

**Step 3:** Run `main.ipynb` for full functions
- After running for the first time, result will be written to `result.txt` directory
- Next times, the program reads last result from the file in order to save time, because running process takes a lot of time (tricky)
- If you want to running again, please delete `mark.txt` file in the same directory

**Note**: `fz12.ipynb` and `urs.ipynb` represent for each scheme which are combined in `main.ipynb`
