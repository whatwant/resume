
## Reference
- [bulma-resume-template](https://github.com/mazipan/bulma-resume-template)


## Usability Testing
- Prerequisite
  - node/npm : [Install Guide](https://www.whatwant.com/entry/npm)
  - pnpm

```bash
❯ nvm install 14.7.0

❯ nvm use node 14.7.0

❯ npm install -g pnpm
```

- Template Testing

```bash
❯ git clone https://github.com/mazipan/bulma-resume-template.git

❯ cd bulma-resume-template

❯ pnpm install

❯ pnpm run dev
```

- http://localhost:8080/

![pnpm](samples/pnpm.png)

- output path

```bash
❯ ls -al
합계 768
drwxrwxr-x 7 chani22 chani22   4096  1월  4 20:25 .
drwxr-xr-x 5 chani22 chani22   4096  1월  4 20:13 ..
-rw-rw-r-- 1 chani22 chani22    234  1월  4 20:13 .babelrc
-rw-rw-r-- 1 chani22 chani22    252  1월  4 20:13 .eleventy.js
drwxrwxr-x 8 chani22 chani22   4096  1월  4 20:13 .git
drwxrwxr-x 3 chani22 chani22   4096  1월  4 20:13 .github
-rw-rw-r-- 1 chani22 chani22    950  1월  4 20:13 .gitignore
-rw-rw-r-- 1 chani22 chani22    380  1월  4 20:13 .travis.yml
-rw-rw-r-- 1 chani22 chani22   1070  1월  4 20:13 LICENSE
-rw-rw-r-- 1 chani22 chani22   3120  1월  4 20:13 README.md
drwxrwxr-x 4 chani22 chani22   4096  1월  4 20:25 dist
drwxrwxr-x 5 chani22 chani22   4096  1월  4 20:25 node_modules
-rw-rw-r-- 1 chani22 chani22   1496  1월  4 20:13 package.json
-rw-rw-r-- 1 chani22 chani22 136057  1월  4 20:25 pnpm-lock.yaml
-rw-rw-r-- 1 chani22 chani22    402  1월  4 20:13 publish-demo.js
-rw-rw-r-- 1 chani22 chani22    206  1월  4 20:13 renovate.json
-rw-rw-r-- 1 chani22 chani22 271109  1월  4 20:13 screenshoot-dracula.png
-rw-rw-r-- 1 chani22 chani22 268103  1월  4 20:13 screenshoot-light.png
-rw-rw-r-- 1 chani22 chani22  34892  1월  4 20:13 screenshoot-lighthouse.png
drwxrwxr-x 5 chani22 chani22   4096  1월  4 20:13 src

❯ ls -al ./dist
합계 60
drwxrwxr-x 4 chani22 chani22  4096  1월  4 20:25 .
drwxrwxr-x 7 chani22 chani22  4096  1월  4 20:25 ..
drwxrwxr-x 2 chani22 chani22  4096  1월  4 20:25 css
-rw-rw-r-- 1 chani22 chani22 42784  1월  4 20:25 index.html
drwxrwxr-x 2 chani22 chani22  4096  1월  4 20:25 light
```
