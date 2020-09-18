# TheRouter
A simple PHP Router

## Install
```
  composer require lpeil/therouter
```

## Usage

```
   use \TheRouter\Router;
   
   $routes = new Router();
   
   $routes->add('method', 'url', function ($params, $request, $headers) { result } );
   
   $routes->run();
```
