---
hide-toc: true
firstpage:
lastpage:
---

# MiniWoB++

<video width="100%" controls muted autoplay loop>
  <source src="_static/videos/miniwob.mp4" type="video/mp4">
</video>

The MiniWoB++ library contains a collection of over 100 **web interaction environments**,
along with JavaScript and Python interfaces for programmatically interacting with them.
The Python interface follows the [Gymnasium](https://gymnasium.farama.org/) API
and uses [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/)
to perform actions on the web browser. 

MiniWoB++ is an extension of the
[OpenAI MiniWoB benchmark](http://proceedings.mlr.press/v70/shi17a/shi17a.pdf),
and was introduced in the paper
[Reinforcement Learning on Web Interfaces using Workflow-Guided
Exploration](https://arxiv.org/abs/1802.08802).
If you use MiniWoB++ in your research, please use the following citation:

```bibtex
@inproceedings{liu2018reinforcement,
 author = {Evan Zheran Liu and Kelvin Guu and Panupong Pasupat and Tianlin Shi and Percy Liang},
 title = {Reinforcement Learning on Web Interfaces using Workflow-Guided Exploration},
 booktitle = {International Conference on Learning Representations ({ICLR})},
 url = {https://arxiv.org/abs/1802.08802},
 year = {2018},
}
```

```{toctree}
:hidden:
:caption: Python Interface

content/python_setup
content/python_usage
content/key_combinations
```

```{toctree}
:hidden:
:caption: Javascript Interface

content/javascript_api
```

```{toctree}
:hidden:
:caption: Environments

content/viewing
environments/list
content/demonstrations
```

```{toctree}
:hidden:
:caption: Development

content/dev_environment
Github <https://github.com/Farama-Foundation/miniwob-plusplus>
Contribute to the Docs <https://github.com/Farama-Foundation/miniwob-plusplus/blob/master/docs/README.md>
```
