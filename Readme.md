# My Blog in Github Page

- URL: [Haley0116.github.io](https://Haley0116.github.io/)
- Image Base: [Pasteboard](https://pasteboard.co/)
- Testing URL: [loaclhost](http://localhost:4000/)

## Requirement

- [nvm - Node Version Manager](https://github.com/nvm-sh/nvm/releases)
- Node.js: v20.3.1
  ```bash
  nvm install 20.3.1
  nvm use 20.3.1
  ```

## Wittering Environment Build

1.  ```bash
    git clone git@github.com:Haley0116/markdown-blog.git
    ```
2.  ```bash
    git submodule add git@github.com:volantis-x/hexo-theme-volantis.git themes/volantis
    ```
    or
    ```bash
    git clone git@github.com:volantis-x/hexo-theme-volantis.git themes/volantis
    ```
3.  ```bash
    npm build
    ```

## Testing Server

```bash
hexo server
```

## Deploy to GitHub Page

```bash
hexo clean && hexo deploy
```
