# Yerassyl Otarov
### Junior Analyst

---

### Contact information:

**Phone:** + 7 705 528 17 17<br>
**E-mail:** otarov.logigue@gmail.com<br>
**Telegram:** @watasinomae<br>
[LinkedIn](https://www.linkedin.com/in/yotarov/)br>

---

### Briefly About Myself:

I'm a dedicated data analyst with a relentless curiosity for the world of analytics and machine learning. My journey in this dynamic field has been driven by a burning desire to unravel insights from data and transform them into actionable solutions.<br>

---

### Skills and Proficiency:

- HTML5, CSS3
- Go, Python Basics
- PostgreSQL
- Git, GitHub
- VS Code

---

### Code example:

**Split Whitespaces:**
*A function that separates the words of a string and puts them in a string slice. should be writed. The separators are spaces, tabs and newlines.*

```Go
func SplitWhiteSpaces(s string) []string {
	str := ""
	slice := []string{}
	for _, v := range s {
		if v != ' ' && v != '\n' && v != '	' {
			str = str + string(v)
		} else {
			if len(str) != 0 {
				slice = append(slice, str)
				str = ""
			}
		}
	}
	if len(str) != 0 {
		slice = append(slice, str)
		str = ""
	}
	return slice
}
```
---

### Courses:

- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
- EPAM Systems Data&Analytics Training

---

### Languages:

- English \- Intermediate/Upper-intermediate<br>
- Kazakh \- Native
- Russian \- Native


