# Games API <button name="button" onclick="http://localhost:5000/">See it in the browser!</button>

> This API provides a list of our favorite games along with their genres and release date. This is an open source API.

<br>

### API Endpoints

*   Below are all of the available endpoints for this API:

<br>

| Type     |        Endpoint         | Description                                                                                                                                 |
| -------- | :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------ |
| [POST]   |   `/api/game/create`    | Creates a new game in the database. Request body requires game title, genre, and releaseDate. Should give newly created game in response.   |
| [DELETE] | `/api/game/destroy/:id` | Deletes a game from the database. Requires one parameter, the id. Should give message "{titleOFGame} was removed from the DB`" in response. |
| [PUT]    |   `/api/game/update`    | Edits an existing game in the database. Should give edited game in response.                                                                |
| [GET]    |     `/api/game/get`     | Provides a list of all games in the database. Should give an array of games objects in response.                                            |
|          |

<br>

### [POST] method

*   The `POST` method should take in an object that looks like this

<br>

```
{
  title: 'California Games',
  genre: 'Sports',
  releaseDate: 'June 1987'
}
```

<br>

### Games Schema

*   Below is the structure of the `Schema`

<br>

```
const NESGameSchema = new Schema({
  title: {
    type: String,
    required: true
  },
  genre: {
    type: String,
    required: true
  },
  releaseDate: String
});
```

## Referencing Issues and Pull Requests

<br>

*   Coming Soon

<br>

## License

<br>

*   Look at our LICENSE.md for more information. We used the standard MIT license for this project.

<br>

## Contributors

<br>

*   [Johnathan Huggett](https://www.github.com/JohnathanHuggett)
