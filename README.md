# Computer Networks – Chapter 1: Introduction

### Interactive Study Website

**Authors**

* Harun Yetkin (22091015)
* Kadir Kızilyaprak (22091014)

**University:** Yıldız Technical University
**Department:** CEIT, 3rd Year
**Group:** 7

---

## About the Project

This project was prepared as part of the Computer Networks course. It presents the topics of Chapter 1, including the structure of the Internet, protocols, network layers, delay calculations, and security concepts, in an interactive and visual way.

---

## Update Notes (v2.0)

This update was prepared in line with our instructor’s feedback after the first presentation.

### Quiz Section – Major Revision

Based on our instructor’s feedback that student assessment needed to be improved, the quiz section was completely redesigned:

* **The number of questions was increased from 4 to 20.** The question pool was expanded fivefold so that students could test their understanding of the subject from a broader perspective. The new questions cover different topics such as packet switching, delay formulas, protocol layers, DNS, HTTP, physical transmission media, and network security.

* **The order of the answer choices was changed.** In the original version, the correct answers in some questions were always placed in the same option position, for example always option B. This could cause students to memorize the position of the correct answer instead of focusing on the content. In this update, the correct answer for each question was placed in different positions, such as A, B, C, or D.

* **Question variety was increased.** The newly added questions were designed not only for repetition but also to assess conceptual understanding and practical application skills.

### Other Improvements

* The quiz interface and feedback mechanism were preserved. Explanatory information is still displayed after each incorrect answer.
* The quiz can be restarted with the “Try Again” button. Each time the quiz is restarted, the questions are presented in order.

---

## Project Content

| Section            | Description                                                |
| ------------------ | ---------------------------------------------------------- |
| Internet Structure | End systems, network edge, network core, and ISP hierarchy |
| Protocol Layers    | The 5-layer Internet model: Application → Physical         |
| Switching Types    | Comparison of packet switching and circuit switching       |
| Delay Calculator   | Interactive simulator for d_trans, d_prop, and d_queue     |
| Topology Simulator | Canvas-based packet routing animation                      |
| Network Security   | Threats such as DoS, IP spoofing, and packet sniffing      |
| Quiz               | 20-question interactive assessment section                 |

---

## Technologies Used

* HTML5
* CSS3: Custom Properties, Grid, Flexbox
* Vanilla JavaScript, including Canvas API
* Google Fonts: Sora, Space Mono

---

## How to Run

Open the `index.html` file in any modern browser. No additional installation or server is required.

```text
index.html   ← open this file in your browser
```

---

## Demo

All sections of the project run through a single HTML file. An internet connection is only required for Google Fonts. If the fonts cannot be loaded, the system font will be used instead.
