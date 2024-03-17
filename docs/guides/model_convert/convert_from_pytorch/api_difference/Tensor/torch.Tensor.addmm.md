## [ 仅参数名不一致 ]torch.Tensor.addmm

### [torch.Tensor.addmm](https://pytorch.org/docs/stable/generated/torch.Tensor.addmm.html)

```python
torch.Tensor.addmm(mat1, mat2, *, beta=1, alpha=1)
```

### [paddle.Tensor.addmm]()

```python
paddle.Tensor.addmm(x, y, alpha=1.0, beta=1.0)
```

两者功能一致且参数用法一致，仅参数名不一致，具体如下：

### 参数映射

| PyTorch  | PaddlePaddle |               备注               |
| -------- | ------------ | -------------------------------- |
| mat1 |      x       | 表示输入的 Tensor，仅参数名不一致。 |
| mat2 |      y       | 表示输入的 Tensor，仅参数名不一致。 |
| beta  |    beta     | 乘以 input 的标量。|
| alpha |   alpha     | 乘以 x*y 的标量。|