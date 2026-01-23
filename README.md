# journal
## learning journal
# January 22:
>>study how to use basic github instruct
# January 23:
>>watch:https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
>>> ## note:
>>>>Forward pass,backward pass,the loss function, and epochs are closely related concepts in training a neural network.
>>>>**Loss function**: Define the loss funtion and the model first; it specifies what "error" means and what the model should minimize.
>>>>**Forward pass**: Using the current weights and biases, the model maps inputs to outputs,computes the loss value, and sotres intermediate results needed for backpropagation.
>>>>**backward pass**: Starting from  the loss,backpropagation applies the chain rule to compute gradients with respect to each parameter. Gradients may be accumulated if needed.
>>>>1. **Forward pass**：用目前的權重/偏置把輸入算到輸出，計算 **loss 的數值**，並保留計算圖與中間結果。
>>>>2. **Backward pass**：從 loss 開始沿計算圖反向套用鏈鎖律，算出 **每個參數的梯度**（必要時累加），再用梯度下降更新參數。
>>>>>>>>3. **Iteration vs Epoch**：forward/backward/update 是每個 batch 重複做；epoch 是訓練集完整走過一次。



