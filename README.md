# ecb-maintenance-api
Backend para el control de mantemimientos automotriz

## Available Scripts for the API

In the project directory, you can run:

### `yarn`

To install dependencies

### `yarn start`

Runs the app in the development mode.\
it is running on [http://localhost:4000](http://localhost:4000)

save some data:

POST
http://localhost:4000/save

with this initial data:

{
  "draggedItem": "undefined",
  "lists": [
    {
      "id": 0,
      "text": "Waiting",
      "cars": [
        {
          "id": 3341,
          "description": "motor adjustment",
          "make": "Honda",
          "model": "CR-V",
          "estimatedate": "",
          "km": 45320,
          "image": ""
        },
        {
          "id": 3343,
          "description": "oil change",
          "make": "Volkswaguen",
          "model": "Tiguan",
          "estimatedate": "",
          "km": 13500,
          "image": "http://3.23.108.188/cars/tiguan.jpg"
        },
        {
          "id": 3344,
          "description": "change of pads",
          "make": "Nissan ",
          "model": "Sentra",
          "estimatedate": "",
          "km": 6000,
          "image": ""
        },
        {
          "id": 3345,
          "description": "change of pads",
          "make": "Volkswagen",
          "model": "Vento",
          "estimatedate": "",
          "km": 80050,
          "image": "http://3.23.108.188/cars/vento.jpg"
        },
        {
          "id": 3347,
          "description": "Change ligths",
          "make": "Chevrolet",
          "model": "Spark",
          "estimatedate": "",
          "km": 16098,
          "image": ""
        }
      ]
    },
    {
      "id": 1,
      "text": "In Maintenance",
      "cars": [
        {
          "id": 3340,
          "description": "change of suspension",
          "make": "Nissan",
          "model": "Versa",
          "estimatedate": "2021/12/01",
          "km": 33320,
          "image": ""
        },
        {
          "id": 3342,
          "description": "engine tuning",
          "make": "Honda",
          "model": "Civic",
          "estimatedate": "2020/20/12",
          "km": 90000,
          "image": ""
        },
        {
          "id": 3346,
          "description": "Change Transmission (CVT)",
          "make": "Chevrolet",
          "model": "Aveo NG",
          "estimatedate": "2021/09/07",
          "km": 30000,
          "image": ""
        }
      ]
    }
  ]
}
