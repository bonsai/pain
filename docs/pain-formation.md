# Pain Formation

## Painは最初から与えられるとは限らない

Painには形成経路がある。

Explicit
  「困っている」 → Pain

Recalled
  過去の経験を再提示
  → 「そういえば困っていた」
  → Pain

Pattern
  行動・イベント・ログの反復
  → 異常 / 摩擦 / 回避 / 再作業
  → Pain candidate
  → 問い
  → Pain

Gap
  現在状態 → 望ましい状態
  → Gap
  → Pain candidate

Consequence
  行動 → 時間・費用・失敗・機会損失
  → Pain candidate

## 気づいていないPainを思い出す

中心となる機能は **Pain Recall**。

Agentは「困っていますか？」だけを尋ねない。

過去のExperienceを再提示し、次のパターンを示す。

- 繰り返し
- やり直し
- 中断
- 回避
- 待ち時間
- 手作業
- 失敗
- 不一致
- 感情の変化
- 他者への依存

問いはPainを断定するためではなく、本人が認識を更新するために使う。

例:

Agent:
「先週、同じ作業を3回やり直しています。この作業は面倒でしたか？」

User:
「そういえば毎回面倒だった。」

Agent:
「ではPain候補として記録しますか？」

User:
「はい。」

## Formation stages

experience
    ↓
observation
    ↓
pattern
    ↓
candidate
    ↓
question
    ↓
acknowledgement
    ↓
pain
    ↓
issue

## 原則

### 1. 推測と確定を分ける
Agentが発見しただけではPainを確定しない。

### 2. 根拠を残す
Painは元になったExperience / Observationへ辿れるようにする。

### 3. 解決策を混ぜない
「自動化すべき」はPainではなくIssue / Hypothesis側の記述。

### 4. Painを消さない
解決済みになっても、元のPainはHistoryとして残す。

### 5. 複数Agentで発見できる
Pain候補の発見・反証・再解釈もAgent Competitionの対象にできる。
