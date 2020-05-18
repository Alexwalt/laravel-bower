#Laravel Bower 示例项目
## 克隆库
```
git clone https://github.com/Alexwalt/laravel-bower.git
```
## 安装Bower
````bash
npm install -g bower
````
## 安装PHP依赖库
````bash
composer install
````

## 初始化Laravel项目
````bash
cp .env.example .env
php artisan key:generate
````

## 安装前端库
```bash
bower install
```
## 开启本地服务，浏览器访问http://localhost:8000

```bash
php artisan serve
```
