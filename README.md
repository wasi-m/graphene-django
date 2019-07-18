# graphene-django
Example creating GraphQL API using Django

<i>Tutes at</i> : https://docs.graphene-python.org/projects/django/en/latest/tutorial-plain/

### Accessing using Postman

<i>Image link</i> : https://drive.google.com/open?id=1jjp42uAgm01eN9NtyySakuVtrqadv6NW

### Accessing Using Curl
```curl
$ curl \
  -X POST \
  -H "Content-Type: application/json" \
  --data '{ "query": "{ allIngredients { name } }" }' \
  http://127.0.0.1:8000/graphql
```
