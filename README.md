# 安装项目依赖
```npm install```

# 项目启动
```npm run serve```

# 如果项目启动失败

可能由于种种版本更新的原因需要执行```npm install```重新安装一次  
如果还是不可以的话，在把之前装的都清空
```
rm -rf node_modules
rm package-lock.json
npm cache clear --force
npm install
```
    
# 项目打包
```npm run build```

## 菜单项数据加载成功之后，在前端有几个可以存放的地方：

1. sessionStorage
2. localStorage
3. **vuex**
