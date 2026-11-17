# Lab 10 – Software Licensing

## Exercise 1: License Detective

**Objective:** To identify and compare different software licenses used in machine learning projects on GitHub.

| Project | License | Commercial Use | Attribution Required | Modify & Redistribute | Special Requirements |
|---|---|---|---|---|---|
| [TensorFlow](https://github.com/tensorflow/tensorflow) | Apache 2.0 | Yes | Yes | Yes | Keep license notices, state changes, and follow patent terms. |
| [Scikit-learn](https://github.com/scikit-learn/scikit-learn) | BSD 3-Clause | Yes | Yes | Yes | Cannot use the creators' names for promotion without permission. |
| [PyTorch](https://github.com/pytorch/pytorch) | BSD 3-Clause | Yes | Yes | Yes | Keep copyright notices and follow applicable third-party licenses. |
| [nanoGPT](https://github.com/karpathy/nanoGPT) | MIT | Yes | Yes | Yes | Keep the original copyright and license notice. |
| [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) | AGPL 3.0 | Yes, with conditions | Yes | Yes, with conditions | Must follow copyleft and applicable source-sharing requirements. |

### Comparison

MIT and BSD licenses are simple and flexible. They allow people to use, modify, and share software, including for commercial purposes.

Apache 2.0 also allows commercial use and provides explicit patent protection. AGPL 3.0 has stricter rules because it requires source code to be shared in certain situations, including when modified software is used over a network.

I learned that choosing a software license is important because it determines how other people can use and share a project.

## Exercise 2: Build Your Own License

For this exercise, we created a custom software license for EmotionAI, an AI model designed to recognize emotions in text.

Our license explains who can use the model, what modifications are allowed, the responsibilities of users, prohibited activities, and the consequences of violating the license.

We chose these rules to encourage innovation while protecting the original developers and respecting user privacy.

**Custom License:** [View LICENSE.md](LICENSE.md)
