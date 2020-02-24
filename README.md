# Tinder Bot

## Setup

1. `$ pipenv install --dev`

1. download chromedriver, drop into main directory

1. create a `src/secrets.py` file with variables:

    ```python
    phone='phone_number_all_numbers'
    ```

1. create `./whitelist.txt`, `./starlist.txt`, and `./blacklist.txt` with keywords:

    Example:

    ```text
    hiking
    movies
    dogs
    ```

1. `$ pipenv run python src/tinder_bot.py`

## TODO

- [x] Add debug logging
- [x] Use regex match instead for white-/star-/blacklist
- [ ] Optimize profiles with flair badges
