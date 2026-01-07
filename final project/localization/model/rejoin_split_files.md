To rejoin the split files back into the original 162MB file, you can use the `cat` command in Unix-like systems. Assuming the split files are named `split_model-partaa`, `split_model-partab`, `split_model-partac`, and so on, you can use the following command:

```bash
cat split_model-part* > final_best_model.pth
```

This command will concatenate all split files (`split_model-partaa`, `split_model-partab`, `split_model-partac`, etc.) and save the result into a new file named `final_best_model.pth`.

Once the command is executed, you should have your original 162MB file restored.


Files are split due to GitHub's 100MB file limit.
