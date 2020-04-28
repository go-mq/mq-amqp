# AMQP Driver for mq ![Go](https://github.com/go-mq/mq-amqp/workflows/Go/badge.svg)

The initial driver that came with the fork of [github.com/src-d/go-queue](https://github.com/src-d/go-queue), added to a
separate repository to be used as a go module.

## Installation

`go get github.com/go-mq/mq-amqp/v1`

## Usage

Import mq and this driver to your project, and you should be good to go

```
import (
  "github.com/go-mq/mq/v2"
  _ "github.com/go-mq/mq-amqp/v1"
)

func main() {
   b, _ := mq.NewBroker("amqp://my-rabbitmq.example.com:5672")

  // now see docs of github.com/go-mq/mq for how to use it
}
```
