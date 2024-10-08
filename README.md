# Not A Hotdog (NAH)

> [!NOTE]  
> This project is inspired by the [Boombox "not hot dog" example](https://hexdocs.pm/boombox/examples.html#not-hot-dog).

![Not A Hotdog](assets/logo-medium.svg?raw=true "Not A Hotdog")

A toy experiment to show how to build an Slack app and how to use the Bumblebee library to classify images.

[![Hot Dog Not Hot Dog](https://img.youtube.com/vi/vIci3C4JkL0/0.jpg)](https://www.youtube.com/watch?v=vIci3C4JkL0 "Hot Dog Not Hot Dog")

This project is meant to be used for educational purposes only and it would not have been possible without the amazing
work from the [Bumblebee](https://github.com/elixir-nx/bumblebee) and
[Slack Elixir](https://github.com/ryanwinchester/slack_elixir) libraries.


## Usage

```bash
cat <<EOF > .env
export SLACK_BOT_TOKEN=<YOUR_SLACK_BOT_TOKEN>
export SLACK_APP_TOKEN=<YOUR_SLACK_APP_TOKEN>
EOF

make
make shell
```


## Sample Images

In the [assets/cast](assets/cast) folder you will find a number of images you can use to test the app.

![](assets/the-cast.png?raw=true)


## Additional Resources

- [Legacy: Real Time Messaging API](https://api.slack.com/legacy/rtm)
- [Socket Mode](https://api.slack.com/apis/socket-mode)
- [Events API](https://api.slack.com/apis/events-api)
- [Web API](https://api.slack.com/web)
- [OpenXLA](https://openxla.org/xla)
- [Hugging Face](https://huggingface.co/)
- [microsoft/resnet-50](https://huggingface.co/microsoft/resnet-50)
- [google/vit-base-patch16-224](https://huggingface.co/google/vit-base-patch16-224)
