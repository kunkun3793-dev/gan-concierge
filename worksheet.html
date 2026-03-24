[worksheet_full.html](https://github.com/user-attachments/files/26207678/worksheet_full.html)
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>脳力開発ワークシート</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@300;400;700&family=Noto+Sans+JP:wght@300;400;500&display=swap');

  :root {
    --ink: #1a1410;
    --paper: #f7f4ef;
    --paper-dark: #ede9e1;
    --accent: #8b4513;
    --accent-light: #c4956a;
    --border: #c8bfb0;
    --saved: #2d6a4f;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Noto Sans JP', sans-serif;
    background: var(--paper);
    color: var(--ink);
    min-height: 100vh;
    padding-bottom: 80px;
  }

  .header {
    background: var(--ink);
    color: var(--paper);
    padding: 14px 20px;
    position: sticky;
    top: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .header-title {
    font-family: 'Noto Serif JP', serif;
    font-size: 13px;
    letter-spacing: 0.15em;
    opacity: 0.85;
  }
  .header-date { font-size: 11px; opacity: 0.55; }

  .sheet-nav {
    display: flex;
    overflow-x: auto;
    gap: 6px;
    padding: 10px 14px;
    background: var(--paper-dark);
    border-bottom: 1px solid var(--border);
    scrollbar-width: none;
  }
  .sheet-nav::-webkit-scrollbar { display: none; }

  .nav-btn {
    flex-shrink: 0;
    padding: 5px 12px;
    border: 1px solid var(--border);
    border-radius: 20px;
    background: var(--paper);
    font-size: 11px;
    font-family: 'Noto Sans JP', sans-serif;
    color: var(--ink);
    cursor: pointer;
    transition: all 0.2s;
    white-space: nowrap;
  }
  .nav-btn.active { background: var(--accent); color: white; border-color: var(--accent); }
  .nav-btn.done::after { content: ' ✓'; color: var(--saved); font-weight: bold; }
  .nav-btn.active.done::after { color: #a0ffcc; }

  .sheet-container {
    display: none;
    padding: 20px 16px;
    max-width: 640px;
    margin: 0 auto;
    animation: fadeIn 0.22s ease;
  }
  .sheet-container.active { display: block; }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(6px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .sheet-number {
    font-size: 10px;
    letter-spacing: 0.2em;
    color: var(--accent);
    margin-bottom: 4px;
  }
  .sheet-title {
    font-family: 'Noto Serif JP', serif;
    font-size: 17px;
    font-weight: 700;
    line-height: 1.5;
    margin-bottom: 22px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--accent);
  }

  .field-group { margin-bottom: 18px; }
  .field-label {
    font-size: 12px;
    font-weight: 500;
    color: var(--accent);
    margin-bottom: 6px;
    display: block;
    letter-spacing: 0.04em;
    line-height: 1.5;
  }

  textarea, input[type="text"] {
    width: 100%;
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 9px 11px;
    font-family: 'Noto Sans JP', sans-serif;
    font-size: 14px;
    color: var(--ink);
    background: white;
    transition: border-color 0.2s;
    -webkit-appearance: none;
  }
  textarea:focus, input[type="text"]:focus { outline: none; border-color: var(--accent); }
  textarea { resize: vertical; min-height: 76px; line-height: 1.7; }

  .three-col { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 8px; }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; }
  .sub-label { font-size: 10px; color: #888; margin-bottom: 3px; text-align: center; }

  /* Table */
  .ws-table { width: 100%; border-collapse: collapse; margin-top: 6px; font-size: 13px; }
  .ws-table th { background: var(--ink); color: var(--paper); padding: 7px 8px; text-align: center; font-size: 11px; font-weight: 500; }
  .ws-table td { border: 1px solid var(--border); padding: 2px; }
  .ws-table td input { border: none; padding: 6px 8px; font-size: 13px; width: 100%; background: transparent; font-family: 'Noto Sans JP', sans-serif; }
  .ws-table td input:focus { outline: none; background: #fffdf8; }
  .ws-table tr:nth-child(odd) td { background: white; }
  .ws-table tr:nth-child(even) td { background: var(--paper); }

  /* Score table */
  .score-table { width: 100%; border-collapse: collapse; font-size: 12px; }
  .score-table th { background: var(--ink); color: var(--paper); padding: 6px 4px; text-align: center; font-size: 11px; }
  .score-table td { border: 1px solid var(--border); padding: 6px 8px; font-size: 12px; line-height: 1.4; }
  .score-table td:last-child, .score-table td:nth-last-child(2), .score-table td:nth-last-child(3) {
    text-align: center; width: 44px;
  }
  .score-table tr.section-header td { background: var(--paper-dark); font-weight: 500; font-size: 11px; }

  /* Checklist */
  .check-table { width: 100%; border-collapse: collapse; font-size: 12px; }
  .check-table th { background: var(--ink); color: var(--paper); padding: 6px; text-align: center; font-size: 11px; }
  .check-table td { border: 1px solid var(--border); padding: 5px 8px; font-size: 12px; line-height: 1.4; }
  .check-table td.check-col { text-align: center; width: 36px; }
  .check-table tr.cat-header td { background: var(--paper-dark); font-weight: 500; font-size: 11px; }
  .check-table input[type="checkbox"] { width: 16px; height: 16px; cursor: pointer; }

  .save-btn {
    width: 100%;
    padding: 13px;
    background: var(--accent);
    color: white;
    border: none;
    border-radius: 6px;
    font-family: 'Noto Sans JP', sans-serif;
    font-size: 15px;
    font-weight: 500;
    cursor: pointer;
    margin-top: 22px;
    letter-spacing: 0.1em;
    transition: background 0.2s;
  }
  .save-btn:active { background: #6b3410; }

  .toast {
    position: fixed;
    bottom: 24px;
    left: 50%;
    transform: translateX(-50%) translateY(80px);
    background: var(--saved);
    color: white;
    padding: 11px 24px;
    border-radius: 40px;
    font-size: 13px;
    transition: transform 0.3s ease;
    z-index: 999;
    pointer-events: none;
  }
  .toast.show { transform: translateX(-50%) translateY(0); }

  .history-section { margin-top: 28px; padding-top: 18px; border-top: 1px solid var(--border); }
  .history-title { font-size: 11px; color: #999; letter-spacing: 0.1em; margin-bottom: 10px; }
  .history-item {
    background: white;
    border: 1px solid var(--border);
    border-radius: 5px;
    padding: 10px 12px;
    margin-bottom: 6px;
    cursor: pointer;
  }
  .history-date { font-size: 10px; color: var(--accent); margin-bottom: 3px; }
  .history-preview { font-size: 12px; color: #555; overflow: hidden; display: -webkit-box; -webkit-line-clamp: 2; -webkit-box-orient: vertical; }
  .no-history { font-size: 12px; color: #aaa; text-align: center; padding: 16px; }

  .section-divider { border: none; border-top: 1px dashed var(--border); margin: 16px 0; }
</style>
</head>
<body>

<div class="header">
  <div class="header-title">脳力開発ワークシート</div>
  <div class="header-date" id="todayDate"></div>
</div>
<div class="sheet-nav" id="sheetNav"></div>

<!-- ===== SHEET 1 ===== -->
<div class="sheet-container" id="sheet-1">
  <div class="sheet-number">SHEET 01</div>
  <div class="sheet-title">社会的成功の具体的<br>長期（最終）目標設定</div>
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標は</label>
    <textarea id="s1_goal" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s1_year" placeholder="例：2028年"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s1_mday" placeholder="例：3月15日"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s1_place"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 私が長期目標を達成する目的は</label>
    <textarea id="s1_purpose" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成すると、自分以外の誰の為になるか？どのような好影響を与えられるか？</label>
    <textarea id="s1_impact" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 長期目標を達成することによって、自分自身にどのような好影響が与えられるか？</label>
    <textarea id="s1_self" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(1)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-1"></div></div>
</div>

<!-- ===== SHEET 2 ===== -->
<div class="sheet-container" id="sheet-2">
  <div class="sheet-number">SHEET 02</div>
  <div class="sheet-title">人間的成功の具体的<br>長期（最終）目標設定</div>
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標は</label>
    <textarea id="s2_goal" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s2_year"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s2_mday"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s2_place"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 私が長期目標を達成する目的は</label>
    <textarea id="s2_purpose" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成すると、自分以外の誰の為になるか？どのような好影響を与えられるか？</label>
    <textarea id="s2_impact" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 長期目標を達成することによって、自分自身にどのような好影響が与えられるか？</label>
    <textarea id="s2_self" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(2)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-2"></div></div>
</div>

<!-- ===== SHEET 3 ===== -->
<div class="sheet-container" id="sheet-3">
  <div class="sheet-number">SHEET 03</div>
  <div class="sheet-title">社会的成功の具体的<br>短期・中期目標設定</div>
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標の短期目標は</label>
    <textarea id="s3_short_goal" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 短期目標の達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s3_sy"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s3_sm"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s3_sp"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのための必要条件は（経済面、知識、教養、人間性などの新しい能力）</label>
    <textarea id="s3_short_req" rows="3"></textarea>
  </div>
  <hr class="section-divider">
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標の中期目標は</label>
    <textarea id="s3_mid_goal" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 中期目標の達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s3_my"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s3_mm"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s3_mp"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのための必要条件は（経済面、知識、教養、人間性などの新しい能力）</label>
    <textarea id="s3_mid_req" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(3)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-3"></div></div>
</div>

<!-- ===== SHEET 4 ===== -->
<div class="sheet-container" id="sheet-4">
  <div class="sheet-number">SHEET 04</div>
  <div class="sheet-title">人間的成功の具体的<br>短期・中期目標設定</div>
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標の短期目標は</label>
    <textarea id="s4_short_goal" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 短期目標の達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s4_sy"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s4_sm"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s4_sp"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのための必要条件は（経済面、知識、教養、人間性などの新しい能力）</label>
    <textarea id="s4_short_req" rows="3"></textarea>
  </div>
  <hr class="section-divider">
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標の中期目標は</label>
    <textarea id="s4_mid_goal" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 中期目標の達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s4_my"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s4_mm"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s4_mp"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのための必要条件は（経済面、知識、教養、人間性などの新しい能力）</label>
    <textarea id="s4_mid_req" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(4)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-4"></div></div>
</div>

<!-- ===== SHEET 5 ===== -->
<div class="sheet-container" id="sheet-5">
  <div class="sheet-number">SHEET 05</div>
  <div class="sheet-title">マイナス言葉から<br>プラス言葉への置き換え</div>
  <table class="ws-table">
    <thead><tr><th>■ マイナス感情が条件付けられている言葉</th><th>■ プラス感情が条件付けられている言葉</th></tr></thead>
    <tbody id="s5_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(5)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-5"></div></div>
</div>

<!-- ===== SHEET 6 ===== -->
<div class="sheet-container" id="sheet-6">
  <div class="sheet-number">SHEET 06</div>
  <div class="sheet-title">サイキングアップ＆<br>カームダウンの言葉</div>
  <div class="field-group">
    <label class="field-label">① 弱気になった自分に、語りかけたい決意は</label>
    <textarea id="s6_up" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 強気になる決意をキーワードにすると</label>
    <input type="text" id="s6_up_key">
  </div>
  <hr class="section-divider">
  <div class="field-group">
    <label class="field-label">② 図に乗った自分に、語りかけたい決意は</label>
    <textarea id="s6_down" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 冷静になる決意をキーワードにすると</label>
    <input type="text" id="s6_down_key">
  </div>
  <button class="save-btn" onclick="saveSheet(6)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-6"></div></div>
</div>

<!-- ===== SHEET 7 ===== -->
<div class="sheet-container" id="sheet-7">
  <div class="sheet-number">SHEET 07</div>
  <div class="sheet-title">プラスのボディランゲージ</div>
  <table class="ws-table">
    <thead><tr><th>■ 感情</th><th>■ 動作、表情、態度</th></tr></thead>
    <tbody id="s7_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(7)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-7"></div></div>
</div>

<!-- ===== SHEET 8 ===== -->
<div class="sheet-container" id="sheet-8">
  <div class="sheet-number">SHEET 08</div>
  <div class="sheet-title">ピグマリオン<br>ミーティングの言葉</div>
  <div class="field-group">
    <label class="field-label">■ 強さと自信の言葉</label>
    <textarea id="s8_strong" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 愛情と優しさの言葉</label>
    <textarea id="s8_love" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 感謝と運とツキの言葉</label>
    <textarea id="s8_thanks" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">② 私は __ で、__ で、__ だ。（毎日自分自身に語りかけよう）</label>
    <textarea id="s8_daily" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(8)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-8"></div></div>
</div>

<!-- ===== SHEET 9 ===== -->
<div class="sheet-container" id="sheet-9">
  <div class="sheet-number">SHEET 09</div>
  <div class="sheet-title">ツキのネットワークづくり</div>
  <div class="field-group">
    <label class="field-label">■ 会社で最高にツイていると思われる人は</label>
    <input type="text" id="s9_co_name">
  </div>
  <div class="field-group">
    <label class="field-label">■ その人の長所、またはその人があなたにどのような良い影響を与えてくれると思うか</label>
    <textarea id="s9_co_merit" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 友人知人、親戚で最高にツイていると思われる人は</label>
    <input type="text" id="s9_fr_name">
  </div>
  <div class="field-group">
    <label class="field-label">■ その人の長所、またはその人があなたにどのような良い影響を与えてくれると思うか</label>
    <textarea id="s9_fr_merit" rows="3"></textarea>
  </div>
  <hr class="section-divider">
  <div class="field-group">
    <label class="field-label">■ 取引先で反面教師がいたら、今後その人とどのように上手に接するか</label>
    <textarea id="s9_client" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 社員や社員の家族で反面教師がいたら、今後その人とどのように上手に接するか</label>
    <textarea id="s9_staff" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ お客様で反面教師がいたら、今後その人とどのように上手に接するか</label>
    <textarea id="s9_cust" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(9)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-9"></div></div>
</div>

<!-- ===== SHEET 10 ===== -->
<div class="sheet-container" id="sheet-10">
  <div class="sheet-number">SHEET 10</div>
  <div class="sheet-title">従業員から見た<br>あなたのイメージチェック</div>
  <table class="score-table" id="s10_table">
    <thead><tr><th style="text-align:left">■ 能力・信用・信頼度のイメージ</th><th>強い(2)</th><th>普通(1)</th><th>弱い(0)</th></tr></thead>
    <tbody id="s10_rows1"></tbody>
  </table>
  <br>
  <table class="score-table">
    <thead><tr><th style="text-align:left">■ 性格と人間性に対する信用・信頼度のイメージ</th><th>強い(2)</th><th>普通(1)</th><th>弱い(0)</th></tr></thead>
    <tbody id="s10_rows2"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(10)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-10"></div></div>
</div>

<!-- ===== SHEET 11 ===== -->
<div class="sheet-container" id="sheet-11">
  <div class="sheet-number">SHEET 11</div>
  <div class="sheet-title">社会/人間から見た<br>あなたのイメージチェック</div>
  <table class="score-table">
    <thead><tr><th style="text-align:left">■ 社会的なイメージ評価</th><th>強い(2)</th><th>普通(1)</th><th>弱い(0)</th></tr></thead>
    <tbody id="s11_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(11)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-11"></div></div>
</div>

<!-- ===== SHEET 12 ===== -->
<div class="sheet-container" id="sheet-12">
  <div class="sheet-number">SHEET 12</div>
  <div class="sheet-title">自己実現に向けた<br>習慣チェック</div>
  <div class="field-group">
    <label class="field-label">■ 私が自己実現するために身につける習慣は</label>
    <textarea id="s12_habit" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ なぜその習慣が必要か</label>
    <textarea id="s12_why" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ その習慣をどのように身につけるか</label>
    <textarea id="s12_how" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ チャレンジメッセージ</label>
    <input type="text" id="s12_msg">
  </div>
  <button class="save-btn" onclick="saveSheet(12)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-12"></div></div>
</div>

<!-- ===== SHEET 13 ===== -->
<div class="sheet-container" id="sheet-13">
  <div class="sheet-number">SHEET 13</div>
  <div class="sheet-title">組書きを贈る</div>
  <div class="field-group">
    <label class="field-label">■ あなたの周りにいる人を書き出しましょう</label>
    <textarea id="s13_people" rows="4" placeholder="名前や関係を記入"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ その人に、あなたはどのように接するか</label>
    <textarea id="s13_how" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 現在、あなたはその環境をどのように活かしているか</label>
    <textarea id="s13_now" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 大切な友人、知人上位3件、今後は何月か活動するか</label>
    <textarea id="s13_top3" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(13)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-13"></div></div>
</div>

<!-- ===== SHEET 14 ===== -->
<div class="sheet-container" id="sheet-14">
  <div class="sheet-number">SHEET 14</div>
  <div class="sheet-title">全自的な長期目標の<br>ビジョン設計</div>
  <table class="ws-table">
    <thead><tr><th>分野</th><th>中期目標</th><th>長期</th></tr></thead>
    <tbody id="s14_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(14)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-14"></div></div>
</div>

<!-- ===== SHEET 15 ===== -->
<div class="sheet-container" id="sheet-15">
  <div class="sheet-number">SHEET 15</div>
  <div class="sheet-title">家族から見た<br>あなたのイメージチェック</div>
  <table class="score-table">
    <thead><tr><th style="text-align:left">■ 家族からのイメージ評価</th><th>強い(2)</th><th>普通(1)</th><th>弱い(0)</th></tr></thead>
    <tbody id="s15_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(15)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-15"></div></div>
</div>

<!-- ===== SHEET 16 ===== -->
<div class="sheet-container" id="sheet-16">
  <div class="sheet-number">SHEET 16</div>
  <div class="sheet-title">絶縁の祝い言葉確認</div>
  <div class="field-group">
    <label class="field-label">■ 達成日</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s16_y"></div>
      <div><div class="sub-label">月</div><input type="text" id="s16_m"></div>
      <div><div class="sub-label">日</div><input type="text" id="s16_d"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 私が長期目標を達成した</label>
    <textarea id="s16_achv" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 祝福をどのように受けたか</label>
    <textarea id="s16_recv" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのときの私の心理的状態は</label>
    <textarea id="s16_mind" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 名前の由来を大切に、どのようなメッセージを贈りたい</label>
    <textarea id="s16_msg" rows="4"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(16)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-16"></div></div>
</div>

<!-- ===== SHEET 17 ===== -->
<div class="sheet-container" id="sheet-17">
  <div class="sheet-number">SHEET 17</div>
  <div class="sheet-title">未来の朝の確認</div>
  <div class="field-group">
    <label class="field-label">■ そのときの状況や生活はどのようになっているか</label>
    <textarea id="s17_life" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ その夢の実現をするところをどのようにイメージするか</label>
    <textarea id="s17_image" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ チャレンジメッセージ</label>
    <input type="text" id="s17_msg">
  </div>
  <button class="save-btn" onclick="saveSheet(17)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-17"></div></div>
</div>

<!-- ===== SHEET 18 ===== -->
<div class="sheet-container" id="sheet-18">
  <div class="sheet-number">SHEET 18</div>
  <div class="sheet-title">過去を行で気になう確認</div>
  <div class="field-group">
    <label class="field-label">■ 私が自分の目標をどのくらい達成できるか</label>
    <textarea id="s18_achieve" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 私が自分の目標を達成するよう、自分以外の誰の助けになるか？どのような対影響を与えられるか？</label>
    <textarea id="s18_others" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 長期目標を達成することによって、自分自身にどのような好影響が与えられるか？</label>
    <textarea id="s18_self" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ チャレンジメッセージ</label>
    <input type="text" id="s18_msg">
  </div>
  <button class="save-btn" onclick="saveSheet(18)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-18"></div></div>
</div>

<!-- ===== SHEET 19 ===== -->
<div class="sheet-container" id="sheet-19">
  <div class="sheet-number">SHEET 19</div>
  <div class="sheet-title">長期子どもの確認</div>
  <div class="field-group">
    <label class="field-label">■ 私がチャレンジし続ける長期目標は</label>
    <textarea id="s19_goal" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成年月日・時間・場所</label>
    <div class="three-col">
      <div><div class="sub-label">年</div><input type="text" id="s19_y"></div>
      <div><div class="sub-label">月日</div><input type="text" id="s19_m"></div>
      <div><div class="sub-label">場所</div><input type="text" id="s19_p"></div>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 私が長期目標を達成する目的は</label>
    <textarea id="s19_purpose" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 達成すると、自分以外の誰の為になるか？どのような好影響を与えられるか？</label>
    <textarea id="s19_impact" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 長期目標を達成することによって、自分自身にどのような好影響が与えられるか？</label>
    <textarea id="s19_self" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(19)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-19"></div></div>
</div>

<!-- ===== SHEET 20 ===== -->
<div class="sheet-container" id="sheet-20">
  <div class="sheet-number">SHEET 20</div>
  <div class="sheet-title">年後のあなたの<br>イメージ設計</div>
  <div class="field-group">
    <label class="field-label">■ 今までの仕事から見えるあなたのイメージは？</label>
    <textarea id="s20_work" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 今までのスキルから見えるあなたのイメージは？</label>
    <textarea id="s20_skill" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 今までの意識から見えるあなたのイメージは？</label>
    <textarea id="s20_mind" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ ローカル的な全てのあなたのイメージは？</label>
    <textarea id="s20_local" rows="3"></textarea>
  </div>
  <hr class="section-divider">
  <div class="field-group">
    <label class="field-label">■ 新しい今後のあなたの具体的なイメージデザインは？</label>
    <textarea id="s20_new" rows="4"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 何をするか</label>
    <input type="text" id="s20_what">
  </div>
  <div class="field-group">
    <label class="field-label">■ どのように行なうか</label>
    <textarea id="s20_how" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ そのための今年の行動変容は？</label>
    <textarea id="s20_action" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet(20)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-20"></div></div>
</div>

<!-- ===== SHEET 21 ===== -->
<div class="sheet-container" id="sheet-21">
  <div class="sheet-number">SHEET 21</div>
  <div class="sheet-title">モチベーションCグループ</div>
  <table class="ws-table">
    <thead><tr><th>氏名</th><th>期待する責任</th><th>現在とのギャップ</th></tr></thead>
    <tbody id="s21_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(21)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-21"></div></div>
</div>

<!-- ===== SHEET 25 ===== -->
<div class="sheet-container" id="sheet-25">
  <div class="sheet-number">SHEET 25</div>
  <div class="sheet-title">営業マンの訪問業務<br>行動チェックリスト</div>
  <table class="check-table">
    <thead><tr><th style="text-align:left">チェック項目</th><th>完璧</th><th>十分</th><th>不備</th></tr></thead>
    <tbody id="s25_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(25)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-25"></div></div>
</div>

<!-- ===== SHEET 26 ===== -->
<div class="sheet-container" id="sheet-26">
  <div class="sheet-number">SHEET 26</div>
  <div class="sheet-title">内部社員行動<br>チェックリスト</div>
  <table class="check-table">
    <thead><tr><th style="text-align:left">チェック項目</th><th>完璧</th><th>十分</th><th>不備</th></tr></thead>
    <tbody id="s26_rows"></tbody>
  </table>
  <button class="save-btn" onclick="saveSheet(26)">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-26"></div></div>
</div>

<!-- ===== SHEET A: 今日の気分・体調 ===== -->
<div class="sheet-container active" id="sheet-A">
  <div class="sheet-number">DAILY 01</div>
  <div class="sheet-title">今日の気分・体調メモ</div>
  <div class="field-group">
    <label class="field-label">■ 今日の日付</label>
    <input type="text" id="sA_date" placeholder="例：3月24日（月）">
  </div>
  <div class="field-group">
    <label class="field-label">■ 気分（今の気持ちを一言で）</label>
    <input type="text" id="sA_mood" placeholder="例：スッキリ、少し重い、ワクワク…">
  </div>
  <div class="field-group">
    <label class="field-label">■ 体調（10点満点で）</label>
    <div style="display:flex;align-items:center;gap:12px;">
      <input type="range" id="sA_score" min="1" max="10" value="7" style="flex:1;" oninput="document.getElementById('sA_score_val').textContent=this.value">
      <span id="sA_score_val" style="font-size:20px;font-weight:700;color:var(--accent);min-width:32px;">7</span><span style="font-size:12px;color:#888;">/ 10</span>
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 気になっていること・心にひっかかっていること</label>
    <textarea id="sA_concern" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 今日を一言で表すなら</label>
    <input type="text" id="sA_word" placeholder="例：挑戦の日、丁寧にいく日…">
  </div>
  <button class="save-btn" onclick="saveSheet('A')">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-A"></div></div>
</div>

<!-- ===== SHEET B: 今日の感謝3つ ===== -->
<div class="sheet-container" id="sheet-B">
  <div class="sheet-number">DAILY 02</div>
  <div class="sheet-title">今日の感謝3つ</div>
  <div class="field-group">
    <label class="field-label">■ 今日の日付</label>
    <input type="text" id="sB_date" placeholder="例：3月24日（月）">
  </div>
  <div class="field-group">
    <label class="field-label">① 感謝すること</label>
    <textarea id="sB_t1" rows="2" placeholder="どんな小さなことでもOK"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">② 感謝すること</label>
    <textarea id="sB_t2" rows="2"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">③ 感謝すること</label>
    <textarea id="sB_t3" rows="2"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 今日、一番大切にしたい人・こと</label>
    <input type="text" id="sB_care">
  </div>
  <button class="save-btn" onclick="saveSheet('B')">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-B"></div></div>
</div>

<!-- ===== SHEET C: 研修メモ ===== -->
<div class="sheet-container" id="sheet-C">
  <div class="sheet-number">MEMO 01</div>
  <div class="sheet-title">研修メモ・最新情報</div>
  <div class="field-group">
    <label class="field-label">■ 日付・研修名・場所</label>
    <div class="two-col">
      <input type="text" id="sC_date" placeholder="日付">
      <input type="text" id="sC_name" placeholder="研修名・場所">
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 今日学んだこと・気づいたこと</label>
    <textarea id="sC_learn" rows="5"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ すぐに実践できること</label>
    <textarea id="sC_action" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 最新情報・アップデート</label>
    <textarea id="sC_info" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 次回までの課題</label>
    <textarea id="sC_next" rows="3"></textarea>
  </div>
  <button class="save-btn" onclick="saveSheet('C')">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-C"></div></div>
</div>

<!-- ===== SHEET D: 閃いたこと ===== -->
<div class="sheet-container" id="sheet-D">
  <div class="sheet-number">MEMO 02</div>
  <div class="sheet-title">閃いたこと・アイデアメモ</div>
  <div class="field-group">
    <label class="field-label">■ 日付・時間</label>
    <div class="two-col">
      <input type="text" id="sD_date" placeholder="日付">
      <input type="text" id="sD_time" placeholder="時間（例：朝7時）">
    </div>
  </div>
  <div class="field-group">
    <label class="field-label">■ 閃いたこと・アイデア（思ったままに！）</label>
    <textarea id="sD_idea" rows="6"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ これを活かすとしたら？</label>
    <textarea id="sD_use" rows="3"></textarea>
  </div>
  <div class="field-group">
    <label class="field-label">■ 関連するシートやテーマ</label>
    <input type="text" id="sD_link" placeholder="例：シート8、営業トーク、研修内容…">
  </div>
  <button class="save-btn" onclick="saveSheet('D')">保存する</button>
  <div class="history-section"><div class="history-title">▼ 過去の記録</div><div id="history-D"></div></div>
</div>

<!-- ===== SHEET E: やることリスト ===== -->
<div class="sheet-container" id="sheet-E">
  <div class="sheet-number">TODO</div>
  <div class="sheet-title">やることリスト</div>

  <div style="display:flex;gap:8px;margin-bottom:16px;flex-wrap:wrap;">
    <input type="text" id="sE_new_task" placeholder="やること" style="flex:1;min-width:140px;">
    <input type="text" id="sE_new_limit" placeholder="期限（例：3/25）" style="width:110px;">
    <button onclick="addTodo()" style="padding:9px 14px;background:var(--accent);color:white;border:none;border-radius:4px;font-family:'Noto Sans JP',sans-serif;font-size:13px;cursor:pointer;white-space:nowrap;">＋追加</button>
  </div>

  <div id="sE_todo_list"></div>

  <div style="margin-top:16px;display:flex;gap:8px;">
    <button onclick="saveSheet('E')" class="save-btn" style="margin-top:0;">保存する</button>
    <button onclick="clearDone()" style="padding:13px;background:var(--paper-dark);color:var(--ink);border:1px solid var(--border);border-radius:6px;font-family:'Noto Sans JP',sans-serif;font-size:13px;cursor:pointer;flex-shrink:0;">完了済みを削除</button>
  </div>
  <div class="history-section"><div class="history-title">▼ 過去の保存記録</div><div id="history-E"></div></div>
</div>

<div class="toast" id="toast">✓ 保存しました</div>

<script>
// ===== Sheet definitions =====
const sheetDefs = [
  {id:'A', label:'🌤 気分・体調'},
  {id:'B', label:'🙏 感謝3つ'},
  {id:1,  label:'1 社会的長期目標'},
  {id:2,  label:'2 人間的長期目標'},
  {id:3,  label:'3 社会的短中期目標'},
  {id:4,  label:'4 人間的短中期目標'},
  {id:5,  label:'5 マイナス→プラス'},
  {id:6,  label:'6 サイキング'},
  {id:7,  label:'7 ボディランゲージ'},
  {id:8,  label:'8 ピグマリオン'},
  {id:9,  label:'9 ツキのネットワーク'},
  {id:10, label:'10 従業員イメージ'},
  {id:11, label:'11 社会/人間イメージ'},
  {id:12, label:'12 自己実現習慣'},
  {id:13, label:'13 組書き'},
  {id:14, label:'14 ビジョン設計'},
  {id:15, label:'15 家族イメージ'},
  {id:16, label:'16 絶縁の言葉'},
  {id:17, label:'17 未来の朝'},
  {id:18, label:'18 過去の確認'},
  {id:19, label:'19 長期目標確認'},
  {id:20, label:'20 年後のイメージ'},
  {id:21, label:'21 モチベC'},
  {id:25, label:'25 営業チェック'},
  {id:26, label:'26 内部チェック'},
  {id:'C', label:'📝 研修メモ'},
  {id:'D', label:'💡 閃きメモ'},
  {id:'E', label:'✅ やることリスト'},
];

// Today
const today = new Date();
document.getElementById('todayDate').textContent =
  `${today.getFullYear()}/${today.getMonth()+1}/${today.getDate()}`;

// Nav
const nav = document.getElementById('sheetNav');
sheetDefs.forEach(s => {
  const btn = document.createElement('button');
  btn.className = 'nav-btn';
  btn.textContent = s.label;
  btn.id = `nav-${s.id}`;
  if (s.id === 'A') btn.classList.add('active');
  if (localStorage.getItem(`sheet_${s.id}_latest`)) btn.classList.add('done');
  btn.onclick = () => switchSheet(s.id);
  nav.appendChild(btn);
});

function switchSheet(id) {
  document.querySelectorAll('.sheet-container').forEach(e=>e.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(e=>e.classList.remove('active'));
  document.getElementById(`sheet-${id}`).classList.add('active');
  document.getElementById(`nav-${id}`).classList.add('active');
  if(id==='E') renderTodos();
  loadHistory(id);
}

// ===== Dynamic table initialization =====

// Sheet 5: マイナス→プラス
const s5Examples = [
  ['例：会社（学校）に行く','世の中で一番面白い場所に行く'],
  ['例：勉強（仕事）をする','今日も徹底的に楽しもう'],
  ['例：面倒な仕事をする','自分の能力をアップするチャンス'],
  ['例：頑固な取引先（お客様）','自分を鍛えてくれる魅力的な人'],
  ['例：ケチな友人・知人','自己管理のできる優秀な人'],
  ['',''],['',''],['',''],['',''],['',''],
];
(function(){
  const tb = document.getElementById('s5_rows');
  s5Examples.forEach((r,i)=>{
    const tr=document.createElement('tr');
    tr.innerHTML=`<td><input type="text" id="s5m${i}" placeholder="${r[0]}"></td><td><input type="text" id="s5p${i}" placeholder="${r[1]}"></td>`;
    tb.appendChild(tr);
  });
})();

// Sheet 7: ボディランゲージ
const s7Emotions = ['目標を達成できる','悪いことは忘れる','絶好調になれる','リラックスする','集中する','自信満々で強気な','ライバルを思う','サポーターを思う'];
(function(){
  const tb=document.getElementById('s7_rows');
  s7Emotions.forEach((e,i)=>{
    const tr=document.createElement('tr');
    tr.innerHTML=`<td style="padding:6px 10px;font-size:13px;">${e}</td><td><input type="text" id="s7b${i}" placeholder="動作・表情・態度"></td>`;
    tb.appendChild(tr);
  });
})();

// Sheet 10: 従業員イメージ
const s10Items1=[
  '従業員から見て良いリーダーであると思われていると思う',
  '従業員から見てビジネス展開に積極的なリーダーだと思われていると思う',
  '従業員から見て厳しい事にも耐えられるリーダーだと思われていると思う',
  '従業員が我が身を安心して任せられるリーダーだと思われていると思う',
  '従業員に対して存分にリーダーシップを発揮していると思われていると思う',
  '従業員から見て行動力のあるリーダーだと思われていると思う',
  '従業員がビジネスに取り組む姿勢と実績で信用があり、信頼していると思う',
];
const s10Items2=[
  '従業員から見て社外でもリーダーシップを取れる人だと思われていると思う',
  '従業員とのコミュニケーションは良い人だと思われていると思う',
  '従業員から見て仕事の不平、不満は絶対言わない人だと思われていると思う',
  '従業員や周囲の人の悪口は絶対言わない人だと思われていると思う',
  '従業員から見て言動にマナーのある人だと思われていると思う',
  '従業員から見て優しく包容力のある人だと思われていると思う',
  '従業員から見て人間的な魅力がある人だと思われていると思う',
];
function buildScoreRows(tbId, items, prefix){
  const tb=document.getElementById(tbId);
  items.forEach((item,i)=>{
    const tr=document.createElement('tr');
    tr.innerHTML=`<td style="font-size:12px;padding:6px 8px;line-height:1.4">${item}</td>
      <td class="check-col"><input type="radio" name="${prefix}${i}" value="2"></td>
      <td class="check-col"><input type="radio" name="${prefix}${i}" value="1"></td>
      <td class="check-col"><input type="radio" name="${prefix}${i}" value="0"></td>`;
    tb.appendChild(tr);
  });
}
buildScoreRows('s10_rows1', s10Items1, 's10a_');
buildScoreRows('s10_rows2', s10Items2, 's10b_');

// Sheet 11
const s11Items=[
  '社会から見て正直で誠実な人だと思われていると思う',
  '社会から見て約束を守る人だと思われていると思う',
  '社会から見て感謝の心がある人だと思われていると思う',
  '社会から見て思いやりのある人だと思われていると思う',
  '社会から見て前向きで明るい人だと思われていると思う',
  '社会から見て常に成長しようとしている人だと思われていると思う',
  '社会から見て夢を持ち行動している人だと思われていると思う',
];
buildScoreRows('s11_rows', s11Items, 's11_');

// Sheet 14: ビジョン設計
const s14Fields=['仕事・キャリア','家族・人間関係','健康・体力','財務・経済','学び・成長','趣味・余暇','社会貢献','精神・心'];
(function(){
  const tb=document.getElementById('s14_rows');
  s14Fields.forEach((f,i)=>{
    const tr=document.createElement('tr');
    tr.innerHTML=`<td style="padding:6px 8px;font-size:12px;font-weight:500">${f}</td><td><input type="text" id="s14m${i}"></td><td><input type="text" id="s14l${i}"></td>`;
    tb.appendChild(tr);
  });
})();

// Sheet 15: 家族イメージ
const s15Items=[
  '家族から見て良いリーダーである人だと思われていると思う',
  '家族から見てビジネス展開に積極的な人だと思われていると思う',
  '家族から見て厳しい事にも耐えられる人だと思われていると思う',
  '家族から見て我が身を安心して任せられる人だと思われていると思う',
  '家族から見て行動力のある人だと思われていると思う',
  '家族のやや中まで付き合いのあるリーダー的と思われていると思う',
  '家族から見て夢を持ち行動している人と思われていると思う',
  '家族から見て社外でもリーダーシップを取れる人だと思われていると思う',
  '家族とのコミュニケーションは良い人だと思われていると思う',
  '家族に対して仕事の不平・不満のない人だと思われていると思う',
  '家族外での人の悪口を言わない人だと思われていると思う',
  '家族外での言動マナーのある人だと思われていると思う',
  '家族から見て優しく包容力のある人だと思われていると思う',
  '家族から見て人間的な魅力がある人だと思われていると思う',
];
buildScoreRows('s15_rows', s15Items, 's15_');

// Sheet 21: モチベーションC
(function(){
  const tb=document.getElementById('s21_rows');
  for(let i=0;i<8;i++){
    const tr=document.createElement('tr');
    tr.innerHTML=`<td><input type="text" id="s21n${i}"></td><td><input type="text" id="s21r${i}"></td><td><input type="text" id="s21g${i}"></td>`;
    tb.appendChild(tr);
  }
})();

// Sheet 25: 営業チェック
const s25Cats = [
  { cat:'①事前準備', items:[
    '訪問先の事前調査はしたか（シェアその他）',
    '他社製品の競合品についての知識は十分か',
    '商品トークや商談成立のイメージはあるか',
    '商品に対する自信は充分で職務は決まっているか',
    '訪問計算アポイントはしっかりやったか',
    '訪問のタイミングは良かったか',
  ]},
  { cat:'②アプローチ', items:[
    '服装・身だしなみは完璧だったか',
    '礼儀にお詫びはなかったか',
    '切り出しの話法は完璧だったか',
    '顧客を書い気分にさせたか',
    '紹介を書いたか',
  ]},
  { cat:'③ヒアリング', items:[
    'お客様の注意を引くことにひいたか',
    '自分を売り込んだか',
    'お客様をちょうどかけたか',
    'お客様のニーズをかけられたいたか',
    'お客様の性格（タイプ）を掴んでいたか',
  ]},
  { cat:'④プレゼン', items:[
    '商談のステップを正しく踏んだか',
    '自己流にような話術ができたか',
    'カタログをタイミングよく催促ができたか',
    '競合商品との比較に勝っていたか',
    '商品に触れさせたか',
    '比較話法は適切であったか',
    '商談中のステークロージングは適切であったか',
  ]},
  { cat:'⑤クロージング', items:[
    '担当者を味方に売り込んだか',
    '基準話法は完璧にしたか',
    'クロージングは完璧に行なったか',
    'クロージングのタイミングはよかったか',
    'クロージングは3回行なったか',
    'お客様の獲得意思をかきたてたか',
  ]},
];
(function(){
  const tb=document.getElementById('s25_rows');
  s25Cats.forEach(cat=>{
    const htr=document.createElement('tr');
    htr.className='cat-header';
    htr.innerHTML=`<td colspan="4">${cat.cat}</td>`;
    tb.appendChild(htr);
    cat.items.forEach((item,i)=>{
      const id=`s25_${cat.cat}_${i}`;
      const tr=document.createElement('tr');
      tr.innerHTML=`<td>${item}</td>
        <td class="check-col"><input type="radio" name="${id}" value="完璧"></td>
        <td class="check-col"><input type="radio" name="${id}" value="十分"></td>
        <td class="check-col"><input type="radio" name="${id}" value="不備"></td>`;
      tb.appendChild(tr);
    });
  });
})();

// Sheet 26: 内部チェック
const s26Cats=[
  {cat:'①接客', items:[
    'アポなしに関係する',
    '挨拶の笑顔をつくっていたか',
    '接待ラインはよろしか、清潔に仲いたか',
    '丁寧に行動を伴うか',
    '丁寧にお辞儀をするか（略礼）',
    'お客様が帰った「いってらっしゃいませ」と言う',
    '心の中で「ありがとうございました」と言う',
  ]},
  {cat:'②接客応対', items:[
    'お客様がはいってきたのを速報なく迎える',
    '出かけるに際して、積極的に迎えに行く',
    '先分く相手子を積極したと確認する',
    '連絡する',
    '7 先達てもらえているかを考えと思う',
    '7 お客様に仕事を手伝ってもらえることがありがたいと思う',
    '8 7対処もしてしまった人相だのの話が出ない',
  ]},
  {cat:'③商品知識', items:[
    '在庫では下手な言葉は使わない',
    '方位的な言葉は使わない',
    '電話を取ったら必ず実証して呼ぶ',
    '電話は先とく早い適した言葉で答える',
    '何が勤務を行なう3時は・制度・根拠を報告する',
    '何か購入する場合は・適・適・報を報告する',
  ]},
];
(function(){
  const tb=document.getElementById('s26_rows');
  s26Cats.forEach(cat=>{
    const htr=document.createElement('tr');
    htr.className='cat-header';
    htr.innerHTML=`<td colspan="4">${cat.cat}</td>`;
    tb.appendChild(htr);
    cat.items.forEach((item,i)=>{
      const id=`s26_${cat.cat}_${i}`;
      const tr=document.createElement('tr');
      tr.innerHTML=`<td>${item}</td>
        <td class="check-col"><input type="radio" name="${id}" value="完璧"></td>
        <td class="check-col"><input type="radio" name="${id}" value="十分"></td>
        <td class="check-col"><input type="radio" name="${id}" value="不備"></td>`;
      tb.appendChild(tr);
    });
  });
})();

// ===== Save logic =====
function getRadioValues(prefix, count){
  const vals={};
  for(let i=0;i<count;i++){
    const el=document.querySelector(`input[name="${prefix}${i}"]:checked`);
    vals[i]=el?el.value:'';
  }
  return vals;
}

function getAllRadiosByCat(cats, sheetId){
  const vals={};
  cats.forEach(cat=>{
    cat.items.forEach((item,i)=>{
      const id=`${sheetId}_${cat.cat}_${i}`;
      const el=document.querySelector(`input[name="${id}"]:checked`);
      vals[`${cat.cat}_${i}`]=el?el.value:'';
    });
  });
  return vals;
}

function g(id){ const el=document.getElementById(id); return el?el.value:''; }

function saveSheet(id){
  const dateStr = today.toLocaleDateString('ja-JP');
  let data={};

  if(id===1) data={goal:g('s1_goal'),year:g('s1_year'),mday:g('s1_mday'),place:g('s1_place'),purpose:g('s1_purpose'),impact:g('s1_impact'),self:g('s1_self')};
  else if(id===2) data={goal:g('s2_goal'),year:g('s2_year'),mday:g('s2_mday'),place:g('s2_place'),purpose:g('s2_purpose'),impact:g('s2_impact'),self:g('s2_self')};
  else if(id===3) data={short_goal:g('s3_short_goal'),sy:g('s3_sy'),sm:g('s3_sm'),sp:g('s3_sp'),short_req:g('s3_short_req'),mid_goal:g('s3_mid_goal'),my:g('s3_my'),mm:g('s3_mm'),mp:g('s3_mp'),mid_req:g('s3_mid_req')};
  else if(id===4) data={short_goal:g('s4_short_goal'),sy:g('s4_sy'),sm:g('s4_sm'),sp:g('s4_sp'),short_req:g('s4_short_req'),mid_goal:g('s4_mid_goal'),my:g('s4_my'),mm:g('s4_mm'),mp:g('s4_mp'),mid_req:g('s4_mid_req')};
  else if(id===5){
    const rows=[];
    for(let i=0;i<10;i++){
      const m=g(`s5m${i}`), p=g(`s5p${i}`);
      rows.push({minus:m,plus:p});
    }
    data={rows};
  }
  else if(id===6) data={up:g('s6_up'),up_key:g('s6_up_key'),down:g('s6_down'),down_key:g('s6_down_key')};
  else if(id===7){
    const rows={};
    s7Emotions.forEach((_,i)=>rows[i]=g(`s7b${i}`));
    data={rows};
  }
  else if(id===8) data={strong:g('s8_strong'),love:g('s8_love'),thanks:g('s8_thanks'),daily:g('s8_daily')};
  else if(id===9) data={co_name:g('s9_co_name'),co_merit:g('s9_co_merit'),fr_name:g('s9_fr_name'),fr_merit:g('s9_fr_merit'),client:g('s9_client'),staff:g('s9_staff'),cust:g('s9_cust')};
  else if(id===10) data={a:getRadioValues('s10a_',7),b:getRadioValues('s10b_',7)};
  else if(id===11) data={vals:getRadioValues('s11_',7)};
  else if(id===12) data={habit:g('s12_habit'),why:g('s12_why'),how:g('s12_how'),msg:g('s12_msg')};
  else if(id===13) data={people:g('s13_people'),how:g('s13_how'),now:g('s13_now'),top3:g('s13_top3')};
  else if(id===14){
    const rows={};
    s14Fields.forEach((_,i)=>rows[i]={mid:g(`s14m${i}`),lng:g(`s14l${i}`)});
    data={rows};
  }
  else if(id===15) data={vals:getRadioValues('s15_',14)};
  else if(id===16) data={y:g('s16_y'),m:g('s16_m'),d:g('s16_d'),achv:g('s16_achv'),recv:g('s16_recv'),mind:g('s16_mind'),msg:g('s16_msg')};
  else if(id===17) data={life:g('s17_life'),image:g('s17_image'),msg:g('s17_msg')};
  else if(id===18) data={achieve:g('s18_achieve'),others:g('s18_others'),self:g('s18_self'),msg:g('s18_msg')};
  else if(id===19) data={goal:g('s19_goal'),y:g('s19_y'),m:g('s19_m'),p:g('s19_p'),purpose:g('s19_purpose'),impact:g('s19_impact'),self:g('s19_self')};
  else if(id===20) data={work:g('s20_work'),skill:g('s20_skill'),mind:g('s20_mind'),local:g('s20_local'),new:g('s20_new'),what:g('s20_what'),how:g('s20_how'),action:g('s20_action')};
  else if(id===21){
    const rows=[];
    for(let i=0;i<8;i++) rows.push({name:g(`s21n${i}`),resp:g(`s21r${i}`),gap:g(`s21g${i}`)});
    data={rows};
  }
  else if(id===25) data={vals:getAllRadiosByCat(s25Cats,'s25')};
  else if(id===26) data={vals:getAllRadiosByCat(s26Cats,'s26')};
  else if(id==='A') data={date:g('sA_date'),mood:g('sA_mood'),score:document.getElementById('sA_score').value,concern:g('sA_concern'),word:g('sA_word')};
  else if(id==='B') data={date:g('sB_date'),t1:g('sB_t1'),t2:g('sB_t2'),t3:g('sB_t3'),care:g('sB_care')};
  else if(id==='C') data={date:g('sC_date'),name:g('sC_name'),learn:g('sC_learn'),action:g('sC_action'),info:g('sC_info'),next:g('sC_next')};
  else if(id==='D') data={date:g('sD_date'),time:g('sD_time'),idea:g('sD_idea'),use:g('sD_use'),link:g('sD_link')};
  else if(id==='E'){
    const todos=JSON.parse(localStorage.getItem('todos')||'[]');
    data={todos};
  }

  const entry={date:dateStr,data};
  const key=`sheet_${id}_history`;
  const hist=JSON.parse(localStorage.getItem(key)||'[]');
  hist.unshift(entry);
  localStorage.setItem(key, JSON.stringify(hist.slice(0,30)));
  localStorage.setItem(`sheet_${id}_latest`, dateStr);
  document.getElementById(`nav-${id}`).classList.add('done');
  showToast();
  loadHistory(id);
}

function showToast(){
  const t=document.getElementById('toast');
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),2000);
}

function getPreview(id, data){
  if([1,2,19].includes(id)) return data.goal||'（未記入）';
  if([3,4].includes(id)) return data.short_goal||'（未記入）';
  if(id===5) return data.rows?.filter(r=>r.minus).slice(0,2).map(r=>`${r.minus}→${r.plus}`).join(' / ')||'（未記入）';
  if(id===6) return data.up_key?`UP：${data.up_key} / DOWN：${data.down_key}`:'（未記入）';
  if(id===7) return Object.values(data.rows||{}).filter(Boolean).slice(0,2).join('、')||'（未記入）';
  if(id===8) return data.daily||'（未記入）';
  if(id===9) return data.co_name?`ツキの人：${data.co_name}`:'（未記入）';
  if([10,11,15].includes(id)) return '採点済み';
  if(id===12) return data.habit||'（未記入）';
  if(id===13) return data.people||'（未記入）';
  if(id===14) return '記入済み';
  if(id===16) return data.achv||'（未記入）';
  if(id===17) return data.life||'（未記入）';
  if(id===18) return data.achieve||'（未記入）';
  if(id===20) return data.new||'（未記入）';
  if(id===21) return data.rows?.filter(r=>r.name).map(r=>r.name).join('、')||'（未記入）';
  if([25,26].includes(id)) return 'チェック済み';
  if(id==='A') return data.mood?`気分：${data.mood}　体調：${data.score}/10`:'（未記入）';
  if(id==='B') return data.t1||'（未記入）';
  if(id==='C') return data.learn||'（未記入）';
  if(id==='D') return data.idea||'（未記入）';
  if(id==='E') return data.todos?.filter(t=>!t.done).length+'件 未完了' || '（未記入）';
  return '';
}

function loadHistory(id){
  const el=document.getElementById(`history-${id}`);
  if(!el) return;
  const hist=JSON.parse(localStorage.getItem(`sheet_${id}_history`)||'[]');
  if(hist.length===0){
    el.innerHTML='<div class="no-history">まだ記録がありません</div>';
    return;
  }
  el.innerHTML=hist.slice(0,5).map(h=>`
    <div class="history-item">
      <div class="history-date">${h.date}</div>
      <div class="history-preview">${getPreview(id,h.data)}</div>
    </div>`).join('');
}

// Initial history load
loadHistory('A');
renderTodos();

// ===== TODO functions =====
let todos = JSON.parse(localStorage.getItem('todos')||'[]');

function renderTodos(){
  const el=document.getElementById('sE_todo_list');
  if(!el) return;
  if(todos.length===0){
    el.innerHTML='<div class="no-history">やることを追加してください</div>';
    return;
  }
  el.innerHTML=todos.map((t,i)=>{
    const overdue = t.limit && !t.done && isOverdue(t.limit);
    return `<div style="display:flex;align-items:flex-start;gap:10px;padding:10px 12px;background:${t.done?'#f0f0f0':'white'};border:1px solid var(--border);border-radius:5px;margin-bottom:6px;${overdue?'border-left:3px solid #c0392b':''}">
      <input type="checkbox" ${t.done?'checked':''} onchange="toggleTodo(${i})" style="margin-top:3px;width:16px;height:16px;cursor:pointer;flex-shrink:0;">
      <div style="flex:1;">
        <div style="font-size:14px;${t.done?'text-decoration:line-through;color:#aaa':''}">${t.task}</div>
        ${t.limit?`<div style="font-size:11px;color:${overdue&&!t.done?'#c0392b':'#888'};margin-top:2px;">⏰ ${t.limit}${overdue&&!t.done?' 期限切れ':''}</div>`:''}
      </div>
      <button onclick="deleteTodo(${i})" style="background:none;border:none;color:#ccc;font-size:16px;cursor:pointer;padding:0;line-height:1;">✕</button>
    </div>`;
  }).join('');
}

function isOverdue(limitStr){
  try{
    const parts=limitStr.replace(/[年月\/]/g,'-').replace('日','').split('-');
    if(parts.length<2) return false;
    const m=parseInt(parts[0])-1, d=parseInt(parts[1]);
    const y=new Date().getFullYear();
    const limit=new Date(y,m,d);
    return limit < new Date(new Date().toDateString());
  }catch(e){return false;}
}

function addTodo(){
  const task=document.getElementById('sE_new_task').value.trim();
  const limit=document.getElementById('sE_new_limit').value.trim();
  if(!task) return;
  todos.unshift({task,limit,done:false,created:new Date().toLocaleDateString('ja-JP')});
  localStorage.setItem('todos',JSON.stringify(todos));
  document.getElementById('sE_new_task').value='';
  document.getElementById('sE_new_limit').value='';
  renderTodos();
}

function toggleTodo(i){
  todos[i].done=!todos[i].done;
  localStorage.setItem('todos',JSON.stringify(todos));
  renderTodos();
}

function deleteTodo(i){
  todos.splice(i,1);
  localStorage.setItem('todos',JSON.stringify(todos));
  renderTodos();
}

function clearDone(){
  todos=todos.filter(t=>!t.done);
  localStorage.setItem('todos',JSON.stringify(todos));
  renderTodos();
}
</script>
</body>
</html>
