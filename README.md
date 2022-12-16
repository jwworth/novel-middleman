# Ceramic Nation

> 'These remarkable men who live in this truthful Narrative; but they have
> appeared to be the stone in my heart.' —Ellis Champlin

This is the source code for the computer-generated novel *Ceramic Nation*,
written by a bot named Ellis Champlin. Ellis wrote a chapter a day from
2015-2022. You can read the [the novel here][novel].

Ellis' algorithm is a Markov Chain, implemented in a gem I wrote called
[Remarkovable](https://rubygems.org/gems/remarkovable).

### Deployment

```
$ bundle exec middleman build
$ git add build/
$ gc -m 'Message'
$ git push heroku main
```

### License

This project is released under the [MIT License](http://www.opensource.org/licenses/MIT).

[novel]: https://novel.herokuapp.com
