# crud
Crud en Python

La Api la consumi por postman

Peticion POST
http://localhost:5000/api/v1.0/films/
  {
    "title": "Forrest Gump",
    "length": 8520,
    "year": 1994,
    "director": "Robert Zemeckis",
    "actors": [
        { "name": "Tom Hanks"},
        { "name": "Robin Wright"},
        { "name": "Gary Sinise"},
        { "name": "Mykelti Williamson"},
        { "name": "Sally Field"},
        { "name": "Michael Conner Humphreys"}
    ]
  }
  
Petision GET
[
    {
        "year": 1994,
        "actors": [
            {
                "name": "Gary Sinise",
                "id": 3
            },
            {
                "name": "Michael Conner Humphreys",
                "id": 6
            },
            {
                "name": "Mykelti Williamson",
                "id": 4
            },
            {
                "name": "Robin Wright",
                "id": 2
            },
            {
                "name": "Sally Field",
                "id": 5
            },
            {
                "name": "Tom Hanks",
                "id": 1
            }
        ],
        "length": 8520,
        "id": 1,
        "director": "Robert Zemeckis",
        "title": "Forrest Gump"
    }
]
