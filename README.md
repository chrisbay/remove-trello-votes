# Remove All Trello Votes

A script to remove all [votes](https://help.trello.com/article/788-voting-on-cards) from all cards in a given Trello board.

## Setup

- Obtain Trello [API credentials](https://trello.com/app-key)
- Set environment variables `TRELLO_KEY` and `TRELLO_TOKEN`
- Install dependencies: `pip install -r requirements.txt`

The script requires Python 3.

## Usage

List all boards along with their IDs:

```
$ python run.py
```

Remove all votes on a given board:

```
$ python run.py BOARD_ID
```
