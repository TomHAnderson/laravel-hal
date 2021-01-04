Hypertext Application Language for Laravel
==========================================

[![Release](https://img.shields.io/github/v/release/api-skeletons/laravel-hal)](https://img.shields.io/github/v/release/api-skeletons/laravel-hal)
[![Documentation Status](https://readthedocs.org/projects/api-skeletons-laravel-hal/badge/?version=latest)](https://api-skeletons-laravel-hal.readthedocs.io/en/latest/?badge=latest)




HAL - Hypertext Application Language is a simple format which gives
a consistent and easy way to add HATEOAS to your API.

See the HAL Specification:
[http://stateless.co/hal_specification.html](http://stateless.co/hal_specification.html)


## [Read The Documentation](https://api-skeletons-laravel-hal.readthedocs.io/en/latest/index.html)


A brief output example

```json
{
  "_links":{
    "self":{
      "href":"https://apiskeletons.com/api/me"
    }
  },
  "id":1,
  "name":"Tom H Anderson",
  "email":"tom.h.anderson@gmail.com",
  "_embedded":{
    "roles":[
      {
        "id":1,
        "name":"admin",
        "guard_name":"web",
      }
    ]
  }
}
```
