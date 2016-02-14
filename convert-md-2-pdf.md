### how to convert [user-manual](https://github.com/Dataman-Cloud/shurenyun-user-manual) to pdf

1. install gitbook-cli

```bash
cnpm install gitbook-cli -g
```

2. git clone manual

```bash
git clone git@github.com:Dataman-Cloud/shurenyun-user-manual.git
```

3. install [calibre](http://calibre-ebook.com/)

4. 

```bash
ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin
```

5. converting

```bash
gitbook pdf ./shurenyun-user-manual ~/Downloads/shurenyun-user-manual.pdf
```
