## General info
Server for the learning application for the YouTube channel https://www.youtube.com/channel/UC_AAFmSP9k5IW21hib-wjlg. Contains a database with a list of animes with name, genre, year, and rating.

## Technologies
Node.js
JSON-server

## Setup
To start using the project follow the link https://my-json-server.typicode.com/NameInTheSand/animeListSever

## Possible requests
# GET <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime - Get the list of the users <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime?id={$YOUR_ID} - get the anime by id <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime?year={$YOUR_YEAR} - get the anime by year <br />

# POST <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime - body - JSON object  { <br />
            "id": int, <br /> 
            "name": String,<br />
            "created_at": Time in Unix, <br />
            "review": String, <br />
            "main_genre": String, <br />
            "year": int, <br />
            "rating": int, <br />
            "poster_link": String <br />
}<br />

# PUT <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime/{$YOUR_ID} - body - JSON object <br />

# DELETE <br />
https://my-json-server.typicode.com/NameInTheSand/animeListSever/anime/{$YOUR_ID}
