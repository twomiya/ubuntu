# ubuntu安装
**安装yarn**
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```

```
sudo apt-get update && sudo apt-get install yarn
```

**把cmdtest卸载**

```
sudo apt-get remove --purge cmdtest
```

**再次安装**

```
sudo apt-get update && sudo apt-get install yarn
```

**运行**

```
yarn install
```

**安装node**

```
sudo apt-get install nodejs-legacy nodejs
```

**安装npm**

```
sudo apt-get install npm
```

**安装n**

```
sudo npm install -g n
```

**稳定版本**

```
sudo n stable
```
