# Author
![@suhitk1](https://avatars1.githubusercontent.com/u/20357099?v=3&u=4c1555ae5490d2155959e65c2dd930e782f1c703&s=400)

Created by Rafase282

[Github](https://github.com/suhitk1) | [FreeCodeCamp](http://www.freecodecamp.com/suhitk1) | [CodePen](http://codepen.io/suhitk1/) | [E-Mail](mailto:suhit.kmr1@gmail.com)

# FreeCodeCamp API Basejump: URL Shortener Microservice
## User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2. If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
3. When I visit that shortened URL, it will redirect me to my original link.

## Example creation usage:

```js
https://little-url.herokuapp.com/new/https://www.google.com
https://little-url.herokuapp.com/new/http://foo.com:80
```

## Example creation output:

```js
{"original_url":"http://foo.com:80","short_url":"https://little-url.herokuapp.com/8170"}
```

## Usage:

```
https://little-url.herokuapp.com/2871
```

### Will redirect to:

```
https://www.google.com/
```
