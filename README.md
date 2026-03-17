# W4 多人協作練習 Repo

這是第四週的小組協作練習，模擬真實的多人開發流程。
每位組員有自己的任務和分支，最終合併成一個完整的 Chatbot。

---

## 組長：Fork 並建立你們組的 Repo

> 每組只有組長需要做這個步驟，組員等組長完成後再 clone

**Step 1：Fork 老師的模板**
1. 到老師的模板 repo 頁面
2. 右上角點 **Fork**
3. Owner 選你自己的帳號，名稱改成 `w4-collab-第X組`
4. 點 **Create fork**

（圖片描述：GitHub Fork 按鈕位置，以及 Fork 設定頁面，顯示 Owner 下拉選單與 Repository name 欄位）

**Step 2：邀請組員為 Collaborator**
1. 到你的 fork repo → **Settings** → **Collaborators** → **Add people**
2. 輸入每位組員的 GitHub 帳號，送出邀請
3. 組員收到 email 後點擊接受

**Step 3：把 repo URL 告訴組員**
```
我們組的 repo：https://github.com/組長帳號/w4-collab-第X組
```

---

## 組員：加入協作

> 等組長完成上方步驟、並接受邀請後再開始

```bash
# 1. Clone 組長 fork 的 repo（用組長給你的 URL）
git clone https://github.com/組長帳號/w4-collab-第X組.git
cd w4-collab-第X組

# 2. 根據你的角色建立自己的分支
git checkout -b feature/member-a   # 組員 A
git checkout -b feature/member-b   # 組員 B
git checkout -b feature/member-c   # 組員 C
```

---

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | Chatbot 主頁面（每個人都要修改）|
| `style.css` | 樣式（每個人都要修改）|
| `CONTRIBUTORS.md` | 組員任務清單（每個人都要填）|

---

## 完整協作流程

```
老師提供模板 repo（w4-collab-template）
  ↓
組長：Fork 到自己帳號 → Settings → 邀請組員為 Collaborator
  ↓
各組員：接受邀請 → clone 組長的 repo → 建立自己的 branch → 完成任務
  ↓
各組員：push 分支 → 在 GitHub 對組長的 repo 開 Pull Request
  ↓
組長：Review PR → 解決 Conflict → Merge
  ↓
全組：git pull origin main → 確認最終成果
```

---

## 驗收標準

- [ ] 組長的 GitHub 帳號下有 fork 出來的 repo
- [ ] 所有組員都有自己的 commit 紀錄
- [ ] 至少開過一個 PR 並被 merge
- [ ] 有處理過至少一個 Merge Conflict
- [ ] `CONTRIBUTORS.md` 全部填完
- [ ] 用瀏覽器打開 `index.html`，功能正常
