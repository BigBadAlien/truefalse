## Installation

```bash
hexo init foobar.com;
cd foobar.com;
npm install;
npm install hexo-renderer-sass hexo-renderer-jade --save;
cd themes;
git clone https://github.com/BigBadAlien/truefalse-hexo-theme.git truefalse;
cd ..;
sed -i -e 's/landscape/truefalse/g' _config.yml;
hexo server;
```
