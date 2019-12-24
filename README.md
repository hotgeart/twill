# [twill](https://twill.io/docs/#installation)

1. `laravel new PROJECT` or `composer create-project --prefer-dist laravel/laravel PROJECT "5.8.*"`
2. `cd PROJECT`
3. `composer require area17/twill:"1.2.*"` [check version](https://twill.io/docs/#installation)
4. Update the .env file

```
    MYSQL...
    
    MEDIA_LIBRARY_ENDPOINT_TYPE=local
    MEDIA_LIBRARY_IMAGE_SERVICE=A17\Twill\Services\MediaLibrary\Glide
```

5. php artisan twill:install
7. Add [scripts line](https://twill.io/docs/#npm) to package.json
8. `npm run twill-build --script-shell bash`. --script-shell bash is to avoid bugs in WIN10
 
