# Adventure Time API

The [Adventure Time API](https://adventuretimeapi.herokuapp.com) catalogs the people, places, and things found in [Adventure Time Wikia](http://adventuretime.wikia.com/wiki/Adventure_Time_with_Finn_and_Jake_Wiki). It was created as a resource for REST API testing and prototyping purposes. 

## Endpoints

- People
- Places

## Getting Started
Requests can be made with curl or other helper libraries by following regular REST calls. For example, here is how to GET the resource for Jake:

`curl https://adventuretimeapi.herokuapp.com/people/53YK`

Calling this resource will respond with the following object:

```json
{
  "name": "Jake",
  "fullname": "Jake the Dog",
  "gender": "Male",
  "id": "53YK",
  "url": "https://adventuretimeapi.herokuapp.com/people/53YK"
}
```

## Resources
This API was built using [JSON Server](https://github.com/typicode/json-server), [ReDoc](https://github.com/Rebilly/ReDoc), and looking through [ghibliapi](https://github.com/janaipakos/ghibliapi)
