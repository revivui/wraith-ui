### wraith-ui

#### Install

`$ bundle install`

#### Usage

`$ bundle exec wraith capture configs/capture.yaml`

`$ bundle exec wraith reset_shots configs/capture.yaml`

`$ docker run -P -v ${PWD}:/wraithy -w='/wraithy' bbcnews/wraith capture configs/capture.yaml`

`$ docker run -P -v ${PWD}:/wraithy -w='/wraithy' bbcnews/wraith reset_shots configs/capture.yaml`

#### Credits

https://bbc-news.github.io/wraith
