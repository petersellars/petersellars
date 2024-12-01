<a href="https://github.com/petersellars">
  <img align="center" width="49%" src="./header.svg" />
</a>

```go
package main

import "fmt"

type TechRadar struct {
    url string
}

type Technologies struct {
    techniques []string
    languages  []string
    platforms  []string
    tools      []string
}

type PersonalInfo struct {
    name         string
    currentFocus string
    mytechradar  TechRadar
    technologies Technologies
}

func main() {
    me := PersonalInfo{
        name:         "Peter Sellars",
        currentFocus: "Improving the development experience and process",
        mytechradar: TechRadar{
            url: "https://petersellars.github.io/techradar/",
        },
        technologies: Technologies{
            techniques: []string{"CI/CD","IaC"}
            languages:  []string{"Go"},
            platforms:  []string{"AWS","Node.js"},
            tools:      []string{"Docker","Terraform","Terragrunt"},
    }

    fmt.Println(me)
}
````
![metrics workflow](https://github.com/petersellars/petersellars/actions/workflows/metrics.yml/badge.svg) [![Static Badge](https://img.shields.io/badge/Personal_Technology_Radar-blue?logo=baserow&logoColor=white&labelColor=yellow)](https://petersellars.github.io/techradar)

<a href="https://github.com/petersellars">
  <img align="center" width="49%" src="./repositories.svg" />
</a>
<a href="https://github.com/petersellars">
  <img align="center" width="49%" src="./activity_community_stats.svg" />
</a>

<a href="https://github.com/petersellars">
  <img align="center" width="49%" src="./iso_calendar.svg" />
</a>
<a href="https://github.com/petersellars">
    <img align="center" width="49%" src="./issue_pr_lang.svg" />
</a>

<a href="https://github.com/petersellars">
  <img align="center" width="49%" src="./github-habits.svg" />
</a>
<a href="https://github.com/petersellars">
    <img align="center" width="49%" src="./achievements.svg" />
</a>