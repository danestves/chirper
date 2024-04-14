# Chirper

This project was made using the Laravel framework learning from [https://bootcamp.laravel.com/](https://bootcamp.laravel.com/)

Technologies used:

<a href="https://laravel.com" target="_blank">
  <img src="https://img.shields.io/badge/Laravel-v11-eb4432" alt="Laravel">
</a>
<a href="https://livewire.laravel.com" target="_blank">
  <img src="https://img.shields.io/badge/Livewire-v3-EE5D99" alt="Livewire">
</a>
<a href="https://tailwindcss.com" target="_blank">
  <img src="https://img.shields.io/badge/Tailwind-v3-0ea5e9" alt="Tailwind">
</a>

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs)

Clone the repository

```bash
git clone https://github.com/danestves/chirper.git
```

Switch to the repo folder

```bash
cd chirper
```

Install dependencies 

```bash
composer install
bun install
```

Copy .env.example to .env

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Run database migrations

```bash
php artisan migrate
```
