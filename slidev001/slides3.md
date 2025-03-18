---
theme: default
background: https://cover.sli.dev
title: My first
class: text-center
drawings:
  persist: false

# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-up

# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview

overviewSnapshots: true
---

# This is the Intro

**Foo, Bar & Baz**

---

# Foo

Curabitur blandit tempus ardua ridiculus sed magna.

---

# Baz

Pellentesque habitant morbi tristique senectus et netus.

---

# Bar

A communi observantia non est recedendum.

---

# Javascript

```javascript
	if (!data) {
		return {
			redirect: {
				destination: "/no-data",
			},
		};
	}
```

---

# Python

````md magic-move {lines: true}
```python {1|2-9|*}
lstNumbers = [1,2,3,4,5,6,7,8,9,10]

lstOdds = [i for i in lstNumbers if i % 2 == 0]

lstEven = [i for i in lstNumbers if i not in lstOdds]

lstNumbers.extend([11,12,13,14,15,16,17,18,19,20])

lstNumbers.append(21)
```
````

---

# Code support

You can annotate <span v-mark.box.orange="1">snippets</span> , in  <span v-mark.box.orange="2">sequence</span>