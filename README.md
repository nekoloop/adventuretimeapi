# Adventure Time API

The [Adventure Time API](https://adventuretimeapi.herokuapp.com) catalogs the people, places, and things found in the [Wikia](http://adventuretime.wikia.com/wiki/Adventure_Time_with_Finn_and_Jake_Wiki). It was created to help users discover resources, consume them via HTTP requests, and interact with them in whatever way makes sense. Navigation can be found on the left sidebar, and the right sidebar shows examples of returned objects for successful calls.

## Endpoints

- People
- Places

## Getting Started
Requests can be made with curl or other helper libraries by following regular REST calls. For example, here is how to GET the resource for the film My Neighbor Tororo:

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
