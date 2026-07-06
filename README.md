<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&color=gradient&customColorList=12&text=SYSDASH&fontSize=90&fontColor=fff&animation=twinkling&desc=A+Monitoring+Dashboard%2C+Not+Yet+Monitoring&descSize=16&descAlignY=65&stroke=FFFFFF&strokeWidth=1" alt="SysDash Banner" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&color=00D9FF&center=true&width=900&height=50&lines=Rust+%2B+TypeScript+(planned)+%C2%B7+%E2%9A%A0%EF%B8%8F+scaffold+stage" alt="Typing SVG" />

<br>

[![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white&labelColor=0D1117)](https://www.rust-lang.org)
[![Status](https://img.shields.io/badge/Status-Scaffold-FF4444?style=for-the-badge&labelColor=0D1117)](#status)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

### What it's meant to be
A modular system-monitoring dashboard — CPU/RAM/GPU metrics collection with a plugin architecture and a live-charting TypeScript UI.

> Note: this is a separate, unrelated experiment from [Astrotop](https://github.com/NoamFav/Astrotop), which also touches system monitoring but is a different (and further along) Rust project.

### Status: today vs. planned

| | Today | Planned |
|---|-------|---------|
| `main.rs` | Prints `"SysDash monitoring starting..."` and exits | App bootstrap, panel management |
| `metrics.rs` | Empty placeholder | CPU/RAM/GPU metrics collection |

> [!NOTE]
> No metrics collection or dashboard UI exists yet — this is a two-file scaffold, not a working tool.

```sh
git clone https://github.com/NoamFav/SysDash && cd SysDash
cargo run
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">
Made with ♥ by <a href="https://github.com/NoamFav">NoamFav</a>
<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=gradient&customColorList=12&section=footer" />
</div>
