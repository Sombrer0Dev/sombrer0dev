## Hi there 👋

```go
package main

import "fmt"

type SoftwareDeveloper struct {
	Name string
	Role string
	Languages []string
	Company string
}

func (s *SoftwareDeveloper) HelloWorld(){
	fmt.Printf(`
		Thanks for dropping by, My name is %s and
		I'm currently employed as %s at %s.
		`, s.Name, s.Role, s.Company)
}

func main() {
	s := SoftwareDeveloper{
		Name: "Artem Sokolov",
		Role: "Software Developer",
		Languages: []string{"ru_RU", "en_US"},
		Company: "MTT",
	}
	s.HelloWorld()
}
```

### ⚙️ Software Stack
<div style="display:flex; gap: 0 50px; flex-wrap: wrap">
<div>

#### ⚒ Languages
[![My Skills](https://skillicons.dev/icons?i=go,py,lua)](https://skillicons.dev)
</div>
<div>

#### 🔧 Tools
[![My Skills](https://skillicons.dev/icons?i=linux,docker,jenkins,git,bash,pwsh,grafana)](https://skillicons.dev)
</div>
<div>

#### 📁 Databases
[![My Skills](https://skillicons.dev/icons?i=mongodb,postgresql,mysql)](https://skillicons.dev)
</div>
</div>

<!-- ### 🏢 Working on -->
<!-- <a href="https://github.com/Smbrer1/melon-back-end"> -->
<!--   <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=smbrer1&repo=melon-back-end&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="melon-back-end" /> -->
<!-- </a> -->


