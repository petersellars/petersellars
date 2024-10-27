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
    languages []string
    platforms []string
    tools     []string
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
            languages: []string{"Go"},
            platforms: []string{"AWS"},
            tools:     []string{"Docker","Terraform"},
        },
    }

    fmt.Println(me)
}
````
<table>
  <tr>
    <td valign="middle">
      <img width="20" src="./radar-icon-white.png" alt="Radar Icon"/>
    </td>
    <td valign="middle">
      <a href="https://petersellars.github.io/techradar/">
      View My Personal Technology Radar
      </a>
    </td>
  </tr>
</table>
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