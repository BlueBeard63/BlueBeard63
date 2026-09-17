<div align="center">

# Jack Morrison

Cyber Security student at Bournemouth University  
Software developer with a particular interest in Go, developer tooling, and building things from scratch.

[Website](https://jack-morrison.dev) · [GitHub](https://github.com/BlueBeard63)

</div>

---

## About me

I'm a Cyber Security student at Bournemouth University and spend a lot of my spare time working on software projects.

I enjoy experimenting with different technologies and tend to learn best by building things. Most of my recent work has been in Go, although I also work with TypeScript, React, Vue, and C#.

A lot of what I build starts because I want something that either does not exist yet, or does not quite work the way I want it to.

## Current projects

### [Bosun](https://github.com/BlueBeard63/Bosun)

A zero-ceremony web framework and platform toolkit for Go.

Bosun is built around keeping application code simple while handling a lot of the repetitive framework work automatically. Types register themselves where they are declared, with Bosun taking care of the dependency graph, routing, and OpenAPI generation.

It also includes tooling for events, tracing, object storage, multi-tenancy, deployments, typed client generation, and documentation through its CLI.

```go
type GreetService struct{}

func (s *GreetService) Hello(name string) string {
	return "hello, " + name
}

var _ = bosun.Service[GreetService]()
```

[View Bosun](https://github.com/BlueBeard63/Bosun)

### [Gantry](https://github.com/BlueBeard63/Gantry)

A Go framework for building native desktop applications with React frontends.

Gantry lets me keep application logic in Go while still using React and TypeScript for the UI. It includes native windows, custom titlebars, system tray support, notifications, widgets, testing tools, and cross-platform builds.

[View Gantry](https://github.com/BlueBeard63/Gantry)

## Other projects

| Project | Description | Tech |
| --- | --- | --- |
| [Archon](https://github.com/BlueBeard63/Archon) | Local TUI site management system | Go |
| [BPlugins.DiscordBot](https://github.com/BlueBeard63/BPlugins.DiscordBot) | Custom Discord bot for the BPlugins community | TypeScript |
| [BAnim](https://github.com/BlueBeard63/BAnim) | Frame-by-frame animation engine originally built for my A-Level Computer Science project | C# |
| [Savers](https://github.com/BlueBeard63/Savers) | Tool for generating DDL and SQL used in one of my A-Level projects | C# |

## Technologies

**Languages**

`Go` `TypeScript` `JavaScript` `C#` `HTML` `CSS`

**Frontend**

`React` `Vue`

**Tools**

`Git` `GitHub`

---

<div align="center">

Most of my projects are things I wanted to exist, so I built them.

[https://jack-morrison.dev](https://jack-morrison.dev)

</div>
