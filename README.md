# QuantumCodeSnippets

量子コンピューティングの基礎的な概念を学ぶためのコードスニペット集です。

## 概要

このリポジトリには、量子コンピューティングの基本的なアルゴリズムと概念を実装したJupyter Notebookが含まれています。Qiskitを使用して、量子回路の作成、シミュレーション、測定を行います。

## 含まれるノートブック

### 1. 1量子ビットのHゲート → 50% 確率を確認するコード
- Hadamardゲートの基本動作を学習
- 量子重ね合わせ状態の生成
- 測定による確率分布の確認（|0⟩と|1⟩が50%ずつ）

### 2. Bell状態を作成して測定するコード
- 量子エンタングルメント（量子もつれ）の実装
- Bell状態（最大エンタングル状態）の生成
- 2量子ビット間の相関関係の確認

### 3. 量子テレポーテーションを実装＆結果確認
- 量子テレポーテーションプロトコルの実装
- エンタングルメントと古典通信を使った量子状態の転送
- 測定と条件付きゲート操作による状態の再構築

## 必要な環境

```bash
pip install qiskit qiskit-aer matplotlib numpy
```

## 使い方

1. リポジトリをクローン：
```bash
git clone https://github.com/code4oyama/QuantumCodeSnippets.git
cd QuantumCodeSnippets
```

2. 必要なパッケージをインストール：
```bash
pip install -r requirements.txt
```

3. Jupyter Notebookを起動して、各ノートブックを実行：
```bash
jupyter notebook
```

## 学習の順序

量子コンピューティングを初めて学ぶ場合は、以下の順序で進めることをお勧めします：

1. **1量子ビットのHゲート** - 量子重ね合わせの基本
2. **Bell状態** - 量子エンタングルメントの理解
3. **量子テレポーテーション** - 複雑な量子プロトコルの実装

## 参考資料

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [Qiskit Textbook](https://qiskit.org/textbook/)
- [IBM Quantum Experience](https://quantum-computing.ibm.com/)

## ここのサンプルコードの転記元

- [Grok共有コンテンツ](https://grok.com/share/bGVnYWN5LWNvcHk_97d863c1-25c2-4849-ac3b-3d1b7fac29e1)

## ライセンス

MIT License

## 貢献

プルリクエストを歓迎します。大きな変更の場合は、まずissueを開いて変更内容を議論してください。