## [ 参数完全一致 ]torch.Tensor.mvlgamma

### [torch.Tensor.mvlgamma](https://pytorch.org/docs/stable/generated/torch.Tensor.mvlgamma.html#torch-tensor-mvlgamma)

```python
torch.Tensor.mvlgamma(p)
```

### [paddle.Tensor.multigammaln](https://github.com/PaddlePaddle/Paddle/blob/be090bd0bc9ac7a8595296c316b3a6ed3dc60ba6/python/paddle/tensor/math.py#L5099)

```python
paddle.Tensor.multigammaln(p, name=None)
```

两者功能一致，参数完全一致，具体如下：

### 参数映射

| PyTorch | PaddlePaddle | 备注                                                 |
| ------- | ------------ | ---------------------------------------------------- |
| p       | p            | 多元伽马函数积分空间的维度。                         |

### 转写示例

```python
# PyTorch 写法
y = x.mvlgamma(p)

# Paddle 写法
y = x.multigammaln(p)
```
