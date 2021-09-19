# exerciseDB

Exercise DB is a collection of bodybuilding and fitness exercises, along with useful meta information.
It is intended to kickstart your project by providing a way to get all the data needed without painfully collecting it yourself.

## Usage

Just import the JSON files in `/collections` into your project and get going.

## The Data



### Format

```
{
  "id": "string",
  "name": {
    "en": "string"
  },
  "instructions": {
    "text": []{
      "en": "string"
    }
    "images": [
      "url", "url"
    ],
    "video": {
      "en": "url"
    }
  },
  "equipment": [
    "string", "string"
  ],
  "muscles": {

  }
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)