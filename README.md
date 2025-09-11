# mapt - a minimal apt like tool
I am Japanese, so I use a translation tool, and the language in the tool is mainly Japanese.
# どうやって使うの。
```
Usage:
  myapt update                # パッケージリスト取得 (キャッシュ)
  myapt install <pkg>…        # 依存解決 → .deb ダウンロード → dpkg -i
  myapt search <keyword>      # Packages から検索
  myapt list                  # dpkg -l のシンプル表示
  myapt clean                 # ダウンロードキャッシュ削除
  myapt help                  # このヘルプ
```
