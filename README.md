<p align="center">
  <img src="./assets/icon.png" alt="js-torch" height="135">
</p>

<p align="center">
    <a href="https://github.com/eduardoleao052/js-torch/actions/workflows/test.yml/badge.svg" alt="Unit Tests">
        <img src="https://github.com/eduardoleao052/js-torch/actions/workflows/test.yml/badge.svg" /></a>
    <a href="https://github.com/eduardoleao052/js-torch/pulse" alt="Activity">
        <img src="https://img.shields.io/github/commit-activity/m/eduardoleao052/js-torch" /></a>
    <a href="https://github.com/eduardoleao052/js-torch/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/contributors/eduardoleao052/js-torch" /></a>
    <a href="https://github.com/eduardoleao052/js-torch">
        <img src="https://img.shields.io/badge/language-JavaScript-yellow">
    </a>
    <a href="mailto:eduardoleao052@usp.br">
        <img src="https://img.shields.io/badge/-Email-red?style=flat-square&logo=gmail&logoColor=white">
    </a>
    <a href="https://www.linkedin.com/in/eduardoleao052/">
        <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
    </a>
</p>

# PyTorch in JavaScript
- JS-Torch is a Deep Learning __JavaScript library__ built from scratch, to closely follow PyTorch's syntax. 
- It contains a fully functional [Tensor](src/tensor.js) object, which can track gradients, Deep Learning [Layers](src/layers.js) and functions, and an __Automatic Differentiation__ engine.
- Feel free to try out a <a href="https://eduardoleao052.github.io/js-torch/assets/demo/demo.html" target="blank">Web Demo</a>!

<br>

<details>
<summary> Implemented Tensor <b>Operations</b>: </summary>


<br/>


- [Add](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L346-L401)
- [Subtract](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L404-L438)
- [Multiply](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L441-L496)
- [Divide](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L498-L557)
- [Matrix Multiply](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L560-L621)
- [Power](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L625-L663)
- [Square Root](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L666-L704)
- [Exponentiate](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#706-L744)
- [Log](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L746-L785)
- [Sum](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L790-L842)
- [Mean](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L844-L894)
- [Variance](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L896-L949)
- [Transpose](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L953-L1008)
- [At](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L1010-L1060)
- [MaskedFill](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L1062-L1095)
- [Reshape](https://github.com/eduardoleao052/js-torch/blob/07c1286867b952f32c0e904033214253e8812090/src/tensor.js#L1097-L1129)


</details>

<details>
<summary> Implemented Deep Learning <b>Layers</b>: </summary>


<br/>


- [nn.Linear](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L60-L88)
- [nn.MultiHeadSelfAttention](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L90-L163)
- [nn.FullyConnected](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L165-L194)
- [nn.Block](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L196-L226)
- [nn.Embedding](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L231-L260)
- [nn.PositionalEmbedding](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L262-L291)
- [nn.ReLU](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L296-L325)
- [nn.Softmax](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L327-L346)
- [nn.Dropout](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L351-L376)
- [nn.LayerNorm](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L378-L397)
- [nn.CrossEntropyLoss](https://github.com/eduardoleao052/js-torch/blob/a158c91db9775a88fae6ed2d0f76d6d8ee6f9d23/src/layers.js#L400-L441)

</details>
<br/>

## 1. Project Structure
- `assets/` : Folder to store images and the Demo.
  - `assets/demo/` : JS-Torch's [Web Demo](https://eduardoleao052.github.io/js-torch/assets/demo/demo.html).
- `src/` : Framework with JavaScript files.
  - `src/tensor.js`:  File with the `Tensor` class and all of the tensor `Operations`.
  - `src/utils.js`: File with operations and helper functions.
  - `src/layers.js`: Submodule of the framework. Contains full layers.
  - `src/optim.js`: Submodule of the framework. Contains Adam Optimizer.
- `tests/`: Folder with unit tests. Contains `test.js`.

## 2. Running it Yourself
### Simple Autograd Example: 
```javascript
const torch = require("js-pytorch");

// Instantiate Tensors:
x = torch.randn([8,4,5]);
w = torch.randn([8,5,4], requires_grad = true);
b = torch.tensor([0.2, 0.5, 0.1, 0.0], requires_grad = true);

// Make calculations:
out = torch.matmul(x, w);
out = torch.add(out, b);

// Compute gradients on whole graph:
out.backward();

// Get gradients from specific Tensors:
console.log(w.grad);
console.log(b.grad);

```

### Complex Autograd Example (Transformer): 
```python
import neuralforge as forge
import neuralforge.nn as nn

# Implement Transformer class inheriting from forge.nn.Module:
class Transformer(nn.Module):
    def __init__(self, vocab_size: int, hidden_size: int, n_timesteps: int, n_heads: int, p: float):
        super().__init__()
        # Instantiate Transformer's Layers:
        self.embed = nn.Embedding(vocab_size, hidden_size)
        self.pos_embed = nn.PositionalEmbedding(n_timesteps, hidden_size)
        self.b1 = nn.Block(hidden_size, hidden_size, n_heads, n_timesteps, dropout_prob=p) 
        self.b2 = nn.Block(hidden_size, hidden_size, n_heads, n_timesteps, dropout_prob=p)
        self.ln = nn.LayerNorm(hidden_size)
        self.linear = nn.Linear(hidden_size, vocab_size)

    def forward(self, x):
        z = self.embed(x) + self.pos_embed(x)
        z = self.b1(z)
        z = self.b2(z)
        z = self.ln(z)
        z = self.linear(z)

        return z

# Get tiny Shakespeare test data:
text = load_text_data(f'{PATH}/data/shakespeare.txt')

# Create Transformer instance:
model = Transformer(vocab_size, hidden_size, n_timesteps, n_heads, dropout_p)

# Define loss function and optimizer:
loss_func = nn.CrossEntropyLoss()
optimizer = optim.Adam(model.parameters(), lr=0.01, reg=0)
        
# Training Loop:
for _ in range(n_iters):
    x, y = get_batch(test_data, n_timesteps, batch_size)

    z = model.forward(x)

    # Get loss:
    loss = loss_func(z, y)

    # Backpropagate the loss using forge.tensor's backward() method:
    loss.backward()

    # Update the weights:
    optimizer.step()

    # Reset the gradients to zero after each training step:
    optimizer.zero_grad()
```
> **Note:** You can install the framework locally with: `pip install neuralforge`
<details>
<summary> <b> Requirements </b> </summary>

<br/>
<br/>


</details>
<br/>
