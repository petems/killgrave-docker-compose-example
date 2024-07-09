# killgrave-docker-compose-example 

## What is this?

An example of how to run Killgrove, which is a golang based JSON mocking server.

## Run locally

```shell
$ docker-compose up -d
$ curl http://localhost:8090/posts/123
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   294  100   294    0     0  72449      0 --:--:-- --:--:-- --:--:-- 73500
{
  "userId": 1,
  "id": 123,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}
```