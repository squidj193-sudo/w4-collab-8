# 組員貢獻紀錄

> 每位組員完成自己的分支後，把自己的名字和任務填進來，送出 PR。
> 這個檔案是刻意設計成「大家都要修改」，會產生 Merge Conflict，練習解決！

---

## 第 X 組

| 角色 | 姓名 | 負責分支 | 任務 | 狀態 |
|------|------|---------|------|------|
| 組長 | （填名字）| `main` | 修改標題 & header 顏色 | ⬜ |
| 組員 A | 黃元稜| `feature/member-a` | 修改使用者訊息顏色 & 加計數器 | ⬜ |
| 組員 B | 葉書愷 | `feature/member-b` | 修改按鈕樣式 & 加 footer 名單 | ⬜ |
| 組員 C | 吳東霖| `feature/member-c` | 加入歡迎訊息 & 自訂回覆邏輯 | ✅ |
| 組員 D | （填名字）| `feature/member-d` | 加入深色模式切換按鈕 | ⬜ |
| 組員 E | （填名字）| `feature/member-e` | 加入清除對話功能 | ⬜ |

狀態：⬜ 未開始 / 🔄 進行中 / ✅ 已完成 / 🔀 PR 已開 / ✔️ 已 Merge

---

## 各組員任務說明

### 組長（`main` branch）
- [ ] 把 `index.html` 裡的「第 X 組」改成你們組的實際名稱
- [ ] 修改 `style.css` 裡 `header` 的背景顏色
- [ ] 在這個檔案填入所有組員姓名
- [ ] 最後負責 review 所有 PR 並 merge

### 組員 A（`feature/member-a` branch）
- [ ] 修改 `style.css` 裡 `.message.user` 的 `background` 顏色
- [ ] 在 `index.html` 加上訊息計數顯示（取消那行 comment）
- [ ] 在 `sendMessage()` 函數中加上更新計數的邏輯
- [ ] 開 PR，請組長 review

### 組員 B（`feature/member-b` branch）
- [ ] 修改 `.input-area button` 的顏色和 `border-radius`
- [ ] 在 `index.html` 的 `<footer>` 加入組員名單
- [ ] 在 `style.css` 加上 footer 的樣式
- [ ] 開 PR，請組長 review

### 組員 C（`feature/member-c` branch）
- [ ] 在 `#chat-box` 加一則更個性化的歡迎訊息
- [ ] 修改 `sendMessage()` 裡 bot 的回覆邏輯（例如：根據關鍵字給不同回覆）
- [ ] 開 PR，請組長 review

### 組員 D（`feature/member-d` branch）
- [ ] 在 `index.html` 的 header 加入深色模式切換按鈕
- [ ] 在 `style.css` 加入 `body.dark` 的相關樣式（背景、文字、訊息框顏色）
- [ ] 開 PR，請組長 review

### 組員 E（`feature/member-e` branch）
- [ ] 在 `index.html` 的 input-area 加入「清除對話」按鈕
- [ ] 在 `<script>` 中加入 `clearChat()` 函數，清空 `#chat-box` 的內容
- [ ] 在 `style.css` 為清除按鈕加上樣式（建議用不同顏色與 main 按鈕區分）
- [ ] 開 PR，請組長 review

---

## 預期會出現的 Conflict

組員 A、B、D、E 都會修改 `style.css`，
組員 A、C、D、E 都會修改 `index.html`。

合併時會出現 conflict ── 這是**刻意設計的**，練習解決！
