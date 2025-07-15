# Cadence-Flow

An ergonomic layout for columnar keyboards, designed for a natural typing rhythm and efficient Vim navigation.

## The Layout

![Keyboard Layout Image](cadence.jpg)

## Philosophy & Goals

- **Vim Navigation:** Keeps `HJKL` grouped on the right-hand bottom row for seamless navigation.
- **Bottom-Row Comfort:** Designed for typists who find curling fingers to the bottom row more comfortable than stretching to the top row.
- **Home-Row Centric:** Over 80% of English typing is done on the home row, with `ASET` and `IRON` forming the core.
- **Pianist-Inspired Agility:** Leverages strong, independent pinkies by placing frequent letters like `n` in their natural path.

## A Pragmatic Approach

This layout does not aim to be the _most_ ergonomic layout, and it will likely be less efficient for general prose than giants like Dvorak or Colemak.

Instead, Cadence aims to be a significant improvement over QWERTY for those who live in a terminal and use Vim motions extensively, while drastically lowering the learning curve. As an example, while I average 90 WPM in QWERTY, it took me only 3 days to reach 30 WPM in Cadence, and two weeks to reach a comfortable 60 WPM.

## Performance Metrics

To objectively measure the efficiency of this layout, it was analyzed and compared against QWERTY, Dvorak, Workman and Colemak-DH using a standard English text corpus.

| Metric                   | QWERTY | Dvorak | Workman | Colemak-DH | Cadence v1.0.1 | Cadence v1.0.0 | Cadence-Flow |
| ------------------------ | :----: | :----: | :-----: | :--------: | :------------: | :------------: | :----------: |
| **Home Row Usage**       | 32.30% | 67.85% | 65.65%  |   67.70%   |     65.20%     |     65.20%     |  **65.20%**  |
| **Same-Finger Bigrams**  | 4.39%  | 1.87%  |  1.97%  |   0.91%    |     4.50%      |     3.35%      |  **1.85%**   |
| **Skip Bigrams (2u)**    | 1.43%  | 0.45%  |  0.60%  |   0.41%    |     0.33%      |     0.36%      |  **0.41%**   |
| **Last Stretch Bigrams** | 4.55%  | 0.80%  |  1.11%  |   1.27%    |     0.35%      |     0.33%      |  **0.28%**   |
| **Scissors**             | 1.46%  | 0.08%  |  0.47%  |   0.15%    |     0.41%      |     0.10%      |  **0.28%**   |

![Heatmap](heatmap.jpg)

**A Note on Interpreting the Metrics:**

The data shows a massive improvement in home-row usage and overall finger effort compared to QWERTY.
The score for **Same-Finger Bigrams** is no longer as high as in previous versions. It is now less than that of Dvorak or Workman. We no longer preserve QWERTY fingers placement.

Furthermore, these analyzers use standard English prose for their calculations, and do not fully capture the unique typing patterns of programming or constant Vim navigation, which are the primary use cases for Cadence.

**Sources:**

- [QWERTY](https://cyanophage.github.io/playground.html?layout=qwertyuiop-asdfghjkl%3B%27zxcvbnm%2C.%2F%5C%5E&mode=ergo&lan=english&thumb=l)
- [Dvorak](https://cyanophage.github.io/playground.html?layout=%27%2C.pyfgcrl%2Faoeuidhtns-%3Bqjkxbmwvz%5C%5E&mode=ergo&lan=english&thumb=l)
- [Workman](https://cyanophage.github.io/playground.html?layout=qdrwbjfup%3B-ashtgyneoi%27zxmcvkl%2C.%2F%5C%5E&mode=ergo&lan=english&thumb=l)
- [Colemak-DH](https://cyanophage.github.io/playground.html?layout=qwfpbjluy%3B-arstgmneio%27zxcdvkh%2C.%2F%5C%5E&mode=ergo&lan=english&thumb=l)
- [Cadence v0.0.1](https://cyanophage.github.io/playground.html?layout=pwdfz%2Fmygq-aset%2C.iron%27bucv%3Bxhjkl%5C%5E&mode=ergo&lan=english&thumb=l)
- [Cadence v1.0.0](https://cyanophage.github.io/playground.html?layout=pwdfz%2Fmygq-aset%2C.rion%27ubcv%3Bxhjkl%5C%5E&mode=ergo&lan=english&thumb=l)
- [Cadence-Flow](https://cyanophage.github.io/playground.html?layout=pcudz%2Fqygm-aset%2C.rion%27fbwv%3Bxhjkl%5C%5E&mode=ergo&lan=english&thumb=l)

## Feedback & Contributing

Have you tried Cadence? I would love to hear about your experience. All feedback is welcomed, but I'm particularly interested in:

- Your typing background (QWERTY, Colemak, etc.).
- Any awkward or uncomfortable finger movements you've noticed.
- Your experience using it for programming languages vs. regular prose.

The best way to provide feedback is by **opening an issue** on GitHub.
