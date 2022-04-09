# release package  

## 通过 `GitHub Actions` 自动发布到`github release`和`npm`

## Usage  

1. 复制`.github/workflows/release.yml`文件到项目中.  
2. 将`npm token`配置到`secrets`.  
3. 复制`package.json`中的`scripts`, 执行`npm run release`，将会自动生成版本号和`git tag`，并将并将`tag`push到仓库，`github action`会生`github release`并上传到`npm`.  
