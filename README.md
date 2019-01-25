# delphin_api


## Directions
GET /directions   
```
{
  directions: [
    {id: 1, name: 'ГІМНАЗІЯ', descr: 'описание'},
    {id: 2, name: '', descr: ''}
  ]
}
```
## Services 
GET /services/{direction_id}

```
{
  services: [
    {id: 1, photo: 'url', title: '', name: '', descr: ''},
    {id: 2, photo: 'url', title: '', name: '', descr: ''}
  ]
}
```
## Service
GET /service/{id}

