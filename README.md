# 🚦 Stoplight UIG 📲

> With a stoplight, green means 'go' and yellow means 'slow down'. With a banana, however, it is quite the opposite. Yellow means 'go', green means 'whoa, slow down', and red means 'where the heck did you get that banana?' —Mitch Hedberg

User Interface Guiding (UIG) principals for providing system/callback feedback/states via 🚦-colored icons' fore/backgrounds.

# 📜 Principles

![](./StoplightUIG.drawio.svg)

- Tool-tips: `Brief (green: On) [APP-UIG-0001.00]`
- Status changes all shown in a log accessible from status bar
- Supports 👉 and 🖱️
- The accessibilites, colors, contrasts, timings, etc. are modifiable

# ✅ To-dos

- [ ] More thought into enums like modes
- [ ] Define length that yellow callback waits before failing, and how long to show red/green before fading back to gray (1-3sec)?
- [ ] Gray = Disconnected/not speaking? Or for state-less buttons -> add to chart above (also the grays above are too similar
- [ ] Blues?
- [ ] List specs for accessibility
- [ ] Distinguish Principles above between requirements and design hueristics

## Meta

- [ ] Why is the graphic blurry when it's an .svg?

# 🪪 License

[StoplightUIG](https://github.com/MrMattBusby/StoplightUIG) © 2022 by [@MrMattBusby](https://github.com/MrMattBusby) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
