
### Criando projeto
```bash
composer create-project laravel/laravel chirper
```

### Em um novo terminal

```bash
composer require laravel/breeze --dev
```
Depois
 ```bash
php artisan breeze:install blade
```


### Migração, Modelo e Controller

```bash
php artisan make:model -mrc Chirp
```

## Comandos

```bash
php artisan db:show
php artisan db:table users
```
### Tinker
> Cada linha é um comando!
```bash
php artisan tinker //eixt() ou ctrl+c para sair.
App\Models\Chirp::all();
```
