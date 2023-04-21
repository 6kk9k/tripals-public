# TRIPALS 專案說明

### npm install

因為使用 create-react-app 建立專案時有許多的相依套件在 node_modules 資料夾內，.gitignore 預設不會將 node_modules 一同推送，從 GitHub Clone 下來後，需要在 cmd 內輸入 npm install 抓取 package 內的套件。

### 專案結構

```
📦 TRIPALS
├─ public
└─ src
   ├─ components (共用元件資料夾-Navbar、footer等)
   ├─ pages (頁面資料夾)
   │  ├─ Home
   │  │  ├─ components
   │  │  │  └─ 這邊放各頁的元件，如老師說，後面來不及放整頁
   │  │  ├─ Home.jsx
   │  │  └─ Home.css
   │  └─ Login
   │     ├─ components
   │     │  └─ 這邊放各頁的元件，如老師說，後面來不及放整頁
   │     ├─ Login.jsx
   │     └─ Login.css
   ├─ index.js (react程式進入點)
   └─ index.css
```

©generated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)
