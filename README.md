# Emojimuseet

The source code for [Emojimuseet](https://twitter.com/Emojimuseet), a local Swedish version of [NYPL Emoji Bot](https://github.com/lolibrarian/NYPL-Emoji-Bot)

The emojis reside in [images.json](https://github.com/Ambrosiani/Emojimuseet/blob/master/data/images.json). Feel free to contribute!

## To run your own copy

### Configuration

1. Install dependencies:

  ```shell
  npm install
  ```

2. Copy the example `.env` file:

  ```shell
  cp .env.example .env
  ```

2. [Get credentials for your bot](https://dev.twitter.com/) and complete the `.env`

### Usage

#### To post a status

```shell
npm run status
```

#### To reply to replies

```shell
npm run reply
```

#### Testing

```shell
npm test
```

### Contributing

Emoji additions, bug reports, fixes, and new features are welcomed. If you'd like to contribute code, please:

1. Fork the project

2. Start a branch named for your new feature or bug

3. Create a Pull Request
