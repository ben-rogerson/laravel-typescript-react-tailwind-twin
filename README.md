# Laravel + TypeScript + React + Tailwind + Twin

This starter shows how to use Tailwind with a React frontend and a Laravel backend.
TypeScript is used for type checking and Babel is used for compiling. This improves the [compilation speed](https://iamturns.com/typescript-babel/) and works perfectly with [twin.macro](https://github.com/ben-rogerson/twin.macro).

## Getting started

1. Install composer: `composer install`
2. Install npm packages: `npm install`
3. Start the server: `php artisan serve`
4. Start the webpack dev server: `npm run hot`

## Notes

- The React app sits in: `resources/js`
- Run `tsc` to check for TypeScript errors

## Changes

This project is just a new laravel project with some adjustments. If you'd like to bring TypeScript + Twin into your project, here's a brief list of changes:

- Installed npm dependencies - see `package.json`
- Added `babelMacros` config in `package.json`
- Added types within `types` folder
- Added `.babelrc`
- Added `tailwind.config.js`
- Added `tsconfig.json`
- Added `.prettierrc`
- Added .tsx files in `resources/js`
- Adjusted `resources/views/welcome.blade.php`
- Adjusted `webpack.mix.js`
