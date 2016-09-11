# composer

## 由于composer被墙推荐使用国内镜像
  * 配置全局 
  
    composer config -g repo.packagist composer https://packagist.phpcomposer.com
    
  * 配置单个项目
  
     cd /var/www/{your-project}
     
     composer config repo.packagist composer https://packagist.phpcomposer.com
     
     