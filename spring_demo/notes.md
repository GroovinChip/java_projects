Notes from the spring.io quickstart (found [here](https://spring.io/quickstart))

- The `@RestController` annotation tells Spring that this code describes an endpoint that should be made available over the web.
- The `@GetMapping(“/hello”)` tells Spring to use our `hello()` method to answer requests that get sent to the `http://localhost:8080/hello` address.
- The `@RequestParam` is telling Spring to expect a `name` value in the request, but if it’s not there, it will use the word “World” by default.
