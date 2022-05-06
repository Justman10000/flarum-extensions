# FlarumExtensions

## About

This repository aims to provide you with all extensions that exist for Flarum!

## Usage

1. Go to the root directory of your Flarum instance
2. Load both composer files into this directory, overwriting the existing ones

Then run:

```bash
composer install
composer update
php flarum cache:clear
```

# Extensions

Since it would be too much work to list all extensions, report any extensions that are missing or no longer present as a pull request

# Note

This installs literally hundreds of extensions, depending on performance it could slow down the forum or even crash it (the latter is unlikely)! It is also not suitable for those who only need a few extensions, but I appreciate any attention and use, I have been working on this collection for many months