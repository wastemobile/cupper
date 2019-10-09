# Cupper

Cupper 不是個單純的 Hugo theme，而是一個用 Hugo 寫文件的工具範例：

- 以 Hugo 製成，很簡單的內容架構與快速的編譯。
- 能夠離線閱讀，意即是一個 [Progressive Web App](https://developers.google.com/web/progressive-web-apps/)（這是指編譯完成後的靜態網站）
- 

**Cupper** is a documentation builder for inclusive designers, and those who want to be inclusive designers. Build accessible pattern libraries and all sorts of other docs.

* [Documentation →](https://thepaciellogroup.github.io/cupper)
* [Contributing →](https://github.com/ThePacielloGroup/cupper/blob/master/CONTRIBUTING.md)

**IMPORTANT NOTE:** **Cupper** was originally named **Infusion**. If you forked this repository before the name change, you may experience update troubles (when using `npm run update`). To remedy this, please manually rename your **themes → infusion** folder to **themes → cupper** and reference `cupper` as the theme in your `config.toml`, before running the command.

## Knowing

- 使用 Node 寫了在本地執行的幾個程序，包含 serve, clean, build & update，還有另一個不知作用的 a11y（會叫用 pa11y-ci），用來進行「無障礙性測試」（但似乎不在例行流程中）。
- 僅安裝了兩個 npm packages
	- sw-precache 用於建立 Service Worker 檔案、完成 precache，讓網站能離線閱讀。
	- pre-commit 在提交前進行某些處理，這裏的前置作業是 `build`。
- 
