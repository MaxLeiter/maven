# maven.maxleiter.com

Max Leiter's Maven repository, served from this repo by GitHub Pages. Releases are pushed here by each project's
release workflow; nothing is edited by hand.

```groovy
repositories {
    maven {
        url = "https://maven.maxleiter.com"
        content { includeGroup("dev.vellum") }
    }
}
```

| Group | Project |
|---|---|
| `dev.vellum` | [Vellum](https://github.com/MaxLeiter/vellum), HTML/CSS/JS GUIs for Minecraft mods |
