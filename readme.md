## N-Compass TV Weather

Description would go here

## Installation

Installation would go here

## Usage
After installing, you can start using different feeds:
    
_Example: Displaying a facebook feed (through inoreader)_
```
http://news.app/?type=fb&url=http://www.inoreader.com/stream/user/1005646937/tag/Primal%20Juice%20and%20Smoothies/
```

_Example: Displaying a json feed_
```
http://news.app/?type=json&url=http://news.app/?url=http://news.google.com/news&type=atom
```

_Example: Displaying a json feed, and limiting it to 3 items_
```
http://news.app/?type=json&url=http://news.app/?url=http://news.google.com/news&type=atom&limit=3
```
    
## Options
Options are specified with URL parameters.
    
###Limit

```
    ?limit=3
```

###Type

```
    ?type=json
    ?type=atom
    ?type=rss
    ?type=fb
```

###Background

```
    ?background=example.com/image.png
```
