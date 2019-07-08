## How to install
1. Clone the repository
`$ git clone https://github.com/Nann-Kavdavid/Blog.git`
2. Move to the directory
`$ cd Blog`
3. Install all dependencies
`$ composer install` make sure that you have composer installed
4. Create database and its schema
```
$ php bin/console doctrine:database:create
$ php bin/console doctrine:schema:create
```
5. Run dev server
`$ php bin/console server:start`
