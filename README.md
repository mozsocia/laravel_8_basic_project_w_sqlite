### run this commands to laragon www folder to complete the project init
**be sure to activate sqlite**
```
# Clone the repository
git clone https://github.com/mozsocia/laravel_8_basic_project_w_sqlite.git

# Change the current working directory to the root directory of the repository
cd laravel_8_basic_project_w_sqlite

# Install the dependencies
composer install

# Generate a new application key
php artisan key:generate

# Remove the .git file in powershell 
Remove-Item -Path .\.git\ -Recurse -force

# serve the project 
php artisan serve

```

<br>

### cmd 
```
# Clone the repository
git clone https://github.com/mozsocia/laravel_8_basic_project_w_sqlite.git

# Change the current working directory to the root directory of the repository
cd laravel_8_basic_project_w_sqlite

# Install the dependencies
composer install

# Generate a new application key
php artisan key:generate

# Remove the .git file in powershell 
rmdir /q /s .git

# serve the project 
php artisan serve
```
