<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

## About this project fork

On YouTube I had found <a href="https://www.youtube.com/watch?v=kR1zZBrp4yU">this nice little project for a recipe cookbook</a>, based on the Laravel-framework.

However, this would not run on a recent webhost with PHP 8 installed. Also, the base Laravel-framework used was quite old.

I have fiddled a bit with the original project on my localhost and decided to put up the updated version of it. It is now running on Laravel 9 framework.

## Changes

Updated components:
- Laravel/framework (v5.4 => v9.0)
- Laravel/tinker (v1.0 => v2.0)
- PHP (v5.4x => v8.0 or later)
- Bootstrap-sass (v3.3.7 => v3.4.1)
- Axios (v0.16.2 => v0.27.2)
- phpunit (v5.7 => v9.0)
- lavacollective/html (v5.4.0 => v6.0)

New/deleted components:
- fzaninotto/faker is no longer supported and removed
- laravel ui is added (v3.4)

Also edited the huge background / pagebanner file to a much smaller file and did some inline comment and layout cleanup where necessary.

## Note

Not all dependencies are updated to the latest or replaced. All project functions seem to work, although running a NPM RUN DEV-command is still outputting errors.

## Further development

I will not further develop this project myself, but feel free to fork or contribute to it, etc.

## Credits

Credits for the original idea go to the original author: Aldo Caamal (on github: <a href="https://github.com/AldoHub">AldoHub</a>).