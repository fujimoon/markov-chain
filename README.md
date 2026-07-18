# markov-chain

マルコフ過程（マルコフ連鎖）を「見て」直感的に理解するためのJupyterノートブックです。

「晴れ・曇り・雨」の3状態からなる天気モデルを題材に、以下を段階的に学びます。

1. 状態と遷移確率の基本
2. 遷移確率行列のヒートマップ可視化
3. 状態遷移図（グラフ）による可視化
4. ランダムシミュレーション
5. 確率分布が時間とともに変化する様子のアニメーション
6. 定常分布（Stationary Distribution）の計算と検証
7. 初期状態によらず同じ定常分布に収束することの確認

## 使い方

```bash
jupyter notebook markov_chain_visual_intro.ipynb
```

---

A Jupyter notebook for building an intuitive, visual understanding of Markov processes (Markov chains).

Using a simple 3-state weather model (Sunny / Cloudy / Rainy), it walks through:

1. States and transition probabilities basics
2. Visualizing the transition matrix as a heatmap
3. Visualizing state transitions as a graph
4. Running random simulations
5. Animating how the probability distribution evolves over time
6. Computing and verifying the stationary distribution
7. Confirming convergence to the same stationary distribution regardless of the initial state

## Usage

```bash
jupyter notebook markov_chain_visual_intro.ipynb
```
