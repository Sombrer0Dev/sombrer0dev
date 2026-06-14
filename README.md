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
		Languages: []string{"ru_RU", "en_US", "fr_FR"},
		Company: "Positive Technologies",
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
