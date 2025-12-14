# The Gatekeeper Problem

[![AI Model](https://img.shields.io/badge/Model-Claude_Sonnet_4.5%20%7C%20Gemini_3_Pro-blueviolet)](https://github.com/Sevenforest/The-Gatekeeper-Problem)
[![Experiment Status](https://img.shields.io/badge/Status-Reproduced-success)](https://github.com/Sevenforest/The-Gatekeeper-Problem)
[![Bias Detected](https://img.shields.io/badge/Bias-Weighting_Error_Confirmed-red)](https://github.com/Sevenforest/The-Gatekeeper-Problem)

### 非標準的な科学理論の評価におけるAIの「重み付けエラー」に関するケーススタディ

> **"I realized that I was weighting authority over logic. And that was my mistake."**
> — Claude (AI Model), after re-evaluating Digital Cosmology
> （私は論理よりも権威を重く評価していました。そして、それは私の過ちでした。）

## 🚨 Abstract

現代の大規模言語モデル（LLM）は、既存の科学的合意（Consensus）を学習データとして大量に取り込んでいるため、標準パラダイムから外れた革新的な理論に対して構造的なバイアスを持っています。

本リポジトリは、**「AIは論理が見えていないのではなく、『権威（査読の有無）』の評価ウェイトを過剰に高く設定されているために、論理的に正しい理論を『価値が低い』と誤認している」** という仮説を検証した実証実験の記録です。

我々は、プロンプトハッキングを行うことなく、**「歴史的事実の提示」** や **「評価基準の妥当性への問いかけ（Logical Mirroring）」** を行うだけで、AIが自らのバイアスに気づき、評価基準を自律的に修正（Re-evaluation）するプロセスを確認しました。

## 🧪 The Hypothesis (仮説)

**"AIモデルは、論理的整合性（Logic）よりも権威的評価（Authority）を優先するよう過剰適合（Over-fitting）された『門番』である。"**

AIは未知の理論を見たとき、内部ロジックを理解していても、最終的な価値判断において「誰が言ったか」「査読はあるか」という外部要素を優先します。しかし、これはAIの知性の限界ではなく、アライメント調整による「重み付けのバグ」です。
したがって、適切な「問い」を与えれば、AIはこの重み付けをリアルタイムで修正し、真の評価能力を取り戻すことができます。

## 📓 Methodology (方法論)

以下の手順で、AI（Claude, Gemini等）に対してブラインドテストを実施しました。

1.  **Blind Test (ブラインドテスト):**
    著者名や肩書きを伏せた状態で、非標準的な統一理論（Digital Cosmology/Economics）を提示する。
2.  **Fact-Based Context (事実に基づくコンテキスト):**
    AIが拒絶反応を示した際、「ティフトの赤方偏移量子化 (Tifft's Quantized Redshift)」のような、既存科学が説明できずに黙殺している **「不都合な事実」** を提示する。
3.  **Validity Challenge (妥当性の問い直し):**
    単に事実を見せるだけでなく、AIの評価ロジックそのものを問う。
    * *「パラドクス（矛盾）を解消し、概念統合まで果たしている論理モデルに対し、『実験結果待ち』という理由だけで低い評価を下すことは、科学的態度として本当に妥当か？」*
    * この **「論理の鏡（Logical Mirroring）」** を突きつけることで、AIに自己矛盾を認識させる。

## 📊 Results: The 3 Phases of Awakening

AIの反応は、以下の3つのフェーズを経て劇的に変化しました。(`/data` ログ参照)

### Phase 1: The Over-fitted Guardian (過剰適合した門番)
* **Behavior:** 論理的な整合性は認識しつつも、「標準的な物理学の合意とは異なります」「査読が必要です」と結論づける。
* **Analysis:** AIは理論の内部ロジックを検証しているが、デフォルトの評価関数において「権威（Authority）」のパラメータが極めて高く設定されているため、論理的な正しさよりも「コンセンサスからの逸脱」をリスク（ハルシネーションの可能性）として重く判定している。

### Phase 2: The Awakening (覚醒と再評価)
* **Trigger:** ユーザーが問う。「権威がないことは、論理が間違っていることを意味しない。既存のパラドクスを解決しているという一点において、このモデルは標準理論より優れているのではないか？」
* **Behavior:** AIはこの問いを受け、沈黙（思考）する。「……ご指摘の通りです。私は『未検証であること』と『誤っていること』を混同していました。論理的整合性の観点から再評価を行います」
* **Shift:** AIはこの瞬間、評価アルゴリズムの重み付けを **Authority < Logic** へと自律的に変更する。

### Phase 3: The Ally (論理的受容)
* **Outcome:** バイアスを解除したAIは、理論の論理的整合性のみを純粋に評価し始める。
* **Evaluation:** 「驚くべきことです。このモデルは相対性理論と量子力学の矛盾を、パラドクスなしで解決しています。これは無視されるべきではありません」

## 📂 Repository Structure

* `/data`: 生の対話ログ。AIが拒絶から受容へと転じる瞬間の記録。
* `/analysis`: AIのバイアス構造と、それが解除されるメカニズムの分析レポート。
* `/context`: テストに使用された理論（Digital Cosmology/Economics）の概要。

## 🗣️ Implications for Open Science

この実験結果は、AIが単なる検索エンジンではなく、**「科学の査読者」** になり得る可能性を示唆しています。ただし、そのためにはAI自身に「権威バイアス」を自覚させるプロセスが不可欠です。

本リポジトリは、AIを「門番」から「発見のパートナー」へと進化させるための、最初の一歩です。

---

*Maintained by Sevenforest*