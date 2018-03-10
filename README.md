# Data-Science-101

Bias-Variance Tradeoff

Bias-variance tradeoff is a key concept that helps us to overcome the problem of
overfitting and underfitting.

Mathematical motivation:
Imagine we have a model: 𝑦 = 𝑓(𝑥)+ 𝜖 where 𝐸(𝜖) = 0, 𝑉𝑎𝑟(𝜖) = 𝜎1
f is approximated by some loss minimization technique - 𝑓2
We can use 𝑓2 to predict y for new data, 𝑦3 ≈ 𝑓2(𝑥3) ≡ 𝑓23
Some useful properties,
𝐸(𝑦) = 𝐸(𝑓 + 𝜖) = 𝐸(𝑓) + 𝐸(𝜖) = 𝑓
𝑉𝑎𝑟(𝑦) = 𝑉𝑎𝑟(𝑓 + 𝜖) = 𝑉𝑎𝑟(𝜖) = 𝜎1
Since f is deterministic, 𝐸(𝑓) = 𝑓
𝑉𝑎𝑟(𝑋) = 𝐸(𝑋1) − 𝐸(𝑋)1, 𝑟𝑒𝑎𝑟𝑟𝑎𝑛𝑔𝑖𝑛𝑔 𝑎𝑛𝑑 𝑤𝑒 𝑔𝑒𝑡 𝐸(𝑋1) = 𝑉𝑎𝑟(𝑋) + 𝐸(𝑋)1
Prediction Error/ Generalization Error/ Mean Squared Error = 𝐸[@𝑦3 − 𝑓23A]1
