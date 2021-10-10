<p align="center">
  A Go vanity import path server.
</p>

<p align="center">
  <a href="https://github.com/wager/go.wager.systems/actions/workflows/cd.yaml">
    <img
      src="https://github.com/wager/wager/workflows/cd/badge.svg?branch=main"
      alt="Continuous Delivery"
    />
  </a>
  <a href="https://go.wager.systems">
    <img
      src="https://img.shields.io/badge/go get-go.wager.systems-informational"
      alt="go.wager.systems"
    />
  </a>
</p>

```bash
go.wager.systems/
├── .github/    # Continuous integration and delivery workflows.
└── vangen.json # Vangen configuration.
```

Site is generated [Vangen].

```bash
go get 4d63.com/vangen && vangen
```

Site is hosted by [GitHub Pages].

```bash
curl -L go.wager.systems/wager?go-get=1
```

[GitHub Pages]: 
  https://go.wager.systems
[Vangen]: 
  https://github.com/leighmcculloch/vangen
