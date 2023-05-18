# Quartz

Host your second brain and [digital garden](https://jzhao.xyz/posts/networked-thought) for free. Quartz features

1. Extremely fast natural-language search
2. Customizable and hackable design based on Hugo
3. Automatically generated backlinks, link previews, and local graph
4. Built-in CJK + Latex Support and Admonition-style callouts
5. Support for both Markdown Links and Wikilinks

Check out some of the [amazing gardens that community members](https://quartz.jzhao.xyz/notes/showcase/) have published with Quartz!

> “[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important.” — Richard Hamming

🔗 Get Started: https://quartz.jzhao.xyz/

![Quartz Example Screenshot](./screenshot.png)*Quartz Example Screenshot*

[Join the Discord Community](https://discord.gg/cRFFHYye7t)

# 網站發布到github pages或cloudflare pages差異
## 發布到github pages照上面Get Started說明網站發布
## 發布到cloudflare pages參考 [這篇](https://immmmm.com/hi-cloudflare/)設定
最重要的是
1. 生產分支:master
2. 框架 Hugo
3. 建構命令 none，留空不寫
4. 根目錄也是留空不寫
5. 環境變數(進階)：變數名稱填HUGO_VERSION，值填0.92.0

---
# auto add the title (yaml) to all existing pages without one
目前有人試做，需手動修改YAML屈，我目前尚未測試部屬
[Quartz 中的邊欄](https://simons.dev/notes/Sidebar-in-Quartz/)
