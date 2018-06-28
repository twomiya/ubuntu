# ubuntu安装
** 安装yarn **
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```

```
sudo apt-get update && sudo apt-get install yarn
```

** 把cmdtest卸载 **
`sudo apt-get remove --purge cmdtest`
** 再次安装 **
`sudo apt-get update && sudo apt-get install yarn`
`yarn install`
