# delphin_api


## Admin staff
GET /admin_staff

```
{
  staff: [
     {id: 1, name: 'имя учителя', post: 'должность', photo: 'url', facebook: 'url'},
     {id: 2, name: 'имя учителя', post: 'должность', photo: 'url', facebook: 'url'}    
  ]
}
```

## Partners
GET /partners

```
{
  partners: [
    {id: 1, foto: 'url'},
    {id: 2, foto: 'url'}  
  ]
}
```


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
    {id: 1, photo: 'url', title: 'заголовок на слайдере', name: 'название на слайдере', descr: 'краткое описание на слайдере'},
    {id: 2, photo: 'url', title: '', name: '', descr: ''}
  ]
}
```
## Service
GET /service/{service_id}

```
{
  name: 'название сервиса',
  foto: 'url',
  descr: 'Детальное описание сервиса'
  staff: [
    {id: 1, name: 'имя учителя', post: 'должность', photo: 'url', facebook: 'url'},
    {id: 2, name: 'имя учителя', post: 'должность', photo: 'url', facebook: 'url'}    
  ]

}
```

