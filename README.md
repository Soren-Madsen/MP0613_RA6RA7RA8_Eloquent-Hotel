# Hotel Management System

## Front End
![image](https://github.com/user-attachments/assets/9712f9f4-61a2-4e0f-9a4d-fefc70f7d2e2)

## Back End
![image](https://github.com/user-attachments/assets/921d0b7d-668e-4422-9255-beff8c5799c1)

## Database Tables
![image](https://github.com/user-attachments/assets/fa381905-ff06-4d96-b568-caca4a4b8b4d)


## Installation

Follow these instructions to set up and run the project locally on your machine.

### Prerequisites

-   [Git](https://git-scm.com/)
-   [Composer](https://getcomposer.org/)
-   [PHP](https://www.php.net/)

### Installation

1. Clone the repository:

```bash
   git clone https://github.com/Stucom-Pelai/MP0613_RA6RA7RA8_Eloquent-Hotel.git
```

2. Install Composer dependencies:

```bash
composer install
```

3. Copy the example enviroment file:

```bash
cp .env.example .env
```

4. Generate an application key

```bash
php artisan key:generate
```

5. Create a symbolic link from 'public/storage' to 'storage/app/public'

```bash
php artisan storage:link
```

6. Clear compiled view files

```bash
php artisan view:clear
```

9. Create mp0613_hotel database


10. Run migrations and seed the database

```bash
php artisan migrate:fresh --seed
```

11. Start the Laravel development server 

```bash
php artisan serve
```

12. You are all set



