# Ivan Kulikov

<img width="200" src=hey.png>

## About me

```swift
let me = Developer(
    about: About(
        name: "Ivan Kulikov",
        company: "Bolt",
        location: "Tallinn, Estonia"
    ),
    contacts: Contacts(
        telegram: "@kutchie_pelaez",
        email: "kulikovia.72@icloud.com"
    )
)
```

## My projects

```swift
let projects: [Project] = [
    .organisation(
        name: "Swift packages",
        link: "https://github.com/kutchie-pelaez-packages",
        description: "Set of small packages I use in several pet projects"
    ),
    .tool(
        name: "pkgen",
        link: "https://github.com/kutchie-pelaez/pkgen",
        description: "Tool to simplify SMP packages description"
    ),
    .tool(
        name: "wsgen",
        link: "https://github.com/kutchie-pelaez/wsgen",
        description: "Small tool to generate xcode workspace"
    ),
    .app(
        name: "Marble",
        link: "Still WIP",
        description: "Rich photo editor with huge variety of tools"
    )
]
```