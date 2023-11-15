<img align="left" src="hellofriend.png">
<br>
<h3 align="middle"><img src = "hi.gif" width = 30px>
Hello Friend

I'm someone who is passionate about **GNU/Linux** and likes to **write code**.</h3>

<br><br><br><br><br>

```go
package main

import (
	"fmt"
)

type thearjunneupane struct {
	Username     string
	Name         string
	Code         map[string][]string
	Architecture []string
	Passion      []string
}

func Newthearjunneupane() *thearjunneupane {
	code := map[string][]string{
		"backend":  {"Go", "PHP"},
		"database": {"PostgreSQL", "MySQL"},
		"devops":   {"Docker", "Linux"},
		"frontend": {"HTML", "CSS", "Boostrap", "Tailwind"},
		"tools":    {"GIT", "GitHub"},
		"misc":     {"Firebase", "Netlify", "Postman", "Hugo"},
	}
	architecture := []string{"MVC", "Server"}
	passion := []string{"Computer", "Guitar", "Philosophy"}

	return &thearjunneupane{
		Username:     "thearjunneupane",
		Name:         "Arjun Neupane",
		Code:         code,
		Architecture: architecture,
		Passion:      passion,
	}
}

func (r *thearjunneupane) String() string {
	return fmt.Sprintf("%s >> %s", r.Name, r.Passion)
}

func main() {
	me := Newthearjunneupane()
	fmt.Println(me)
}

```


<!-- - 👀 I’m interested in ***Computer(Actually all).***<br>
- ⚙️ I use daily: ```.sh```, ```.py```, ```.html```, ```.css```, ```.c```<br>
- 📫 Reach me at ***My home*** in ***Nepal***<br>
- 🐱‍ ***UGNazi*** once coompletely disabled the Papa John's Website because their pizza was two hours late. -->
<!---
thearjnep/thearjnep is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
