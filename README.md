### Disclaimer: this project was uploaded by another account of mine in 2020, but I deleted that account, so I reuploaded it here. I rebased the git history because it was a mess back then.

# How AI can be used to improve traffic in big cities

### Problem
According to the UN World Urbanization Prospects, 55% of the world population inhabited urban areas in 2018. That figure is expected to reach 68% by 2050. While the rapid growth of urban communities undoubtedly has led to more convenience for some people, it is undeniable that it has also negatively impacted the life of millions around the globe. A symbol of the chaotic metropolitan lifestyle, traffic jams are a massive complication that threatens the whole unity of the urban network.

### Solution
Transportation has been an issue since the very inception of modern cities. Although efficient long-term solutions tend to require precise planning and a good deal of new infrastructure, it is possible to obtain great results by simply rethinking current systems. Our project seeks to improve traffic using an AI algorithm in order to estimate the ideal average time for every stoplight in the city. A neural network will be responsible for training the program based on simulations of the traffic. Without any major renovations, it would be possible to drastically decrease the travel time for many vehicles on the road.

### Target Audience And Possible Impact of the Project
Virtually everyone in the urban environment is affected either directly or indirectly by the pace of traffic in a specific day. As attested in the survey conducted in the very beginning of the project, 62% of people use cars as their primary mean of transportation in São Paulo which, by itself, would already translate to a huge impact. Taking also into account the ones indirectly impacted by the initiative, it is hard to point out someone that would not be positively affected. So, by decreasing the commuting time for nearly everyone, it would be possible to observe a drastic decline on their stress level, polluting gases emission, and, primarily, all the spheres of society would see an improvement.

### Alignment with the SDGs And Your Project Goals
Tackling SDG number 11 (Sustainable Cities and Communities), our initiative would highly benefit the urban environment as a whole. More than simply reducing commuting time, better transportation is crucial to make cities more inclusive and can even help reducing noise and air pollution.

## Video
[![Video Thumbnail](https://img.youtube.com/vi/6CjnweR4D6o/0.jpg)](https://www.youtube.com/watch?v=6CjnweR4D6o)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Prerequisites
- [Gym](https://pypi.org/project/gym/0.7.4/). Used for activating the environment.
- [Pygame](https://www.pygame.org/wiki/GettingStarted). Used in the rendering process.
- *[Numpy](https://pypi.org/project/numpy/). Used in gym's calculations and is already included with it.*

## Installing

If there is a need to use this environment, you can follow these steps:

1. First, download or clone this repo and install it with pip by running `pip install gym_mlsteam` at the specified directory. Or, if you want to make some changes to the code and see some different variables in action, run `pip install -e gym_mlsteam` instead.

2. Then, you can create an instance of the environment with `gym.make('gym_mlsteam:mlsteam-v1')` 

## Acknowledgemnts
- [Stable Baselines](https://github.com/hill-a/stable-baselines)
- [Gym](https://github.com/openai/gym)
- [OpenAI](https://openai.com/)
