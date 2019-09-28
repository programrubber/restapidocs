# 모든 센터 정보 가져오기

센터의 모든 정보를 가져옴

**Method** : `GET`

**URL** : `/api/gym/all`

**Auth required** : YES

**Permissions required** : None

## Success Response

**Code** : `200 OK`

**Content examples**

```json
{
    "code": "ok",
    "result": [
        {
            "_id": "5d8f7c3eb9722f2d569dba61",
            "create_t": "2019-09-28T15:23:56.475Z",
            "id": "testCenter1",
            "name": "웰페리온1",
            "__v": 0
        },
        {
            "_id": "5d8f7bedb9722f2d569dba60",
            "create_t": "2019-09-28T15:23:56.475Z",
            "id": "testCenter",
            "name": "웰페리온",
            "__v": 0
        }
    ]
}
```

## Notes

* 속성값 중의 원하는 값으로 쿼리를 통해서 원하는 정보를 가지고 올 수 있다.

`/api/gym/all?_id=5d8f736195a8bd2bcc661cae`

_id의 5d8f736195a8bd2bcc661cae값을 검색하여 모든 데이터를 가져올 수 있다.
