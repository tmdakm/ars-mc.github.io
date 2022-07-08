## Welcome to ARSMC
ARSMC是一个我的世界红石数电的一个研讨组，其中包括辰占鳌头等大佬在内。

### 数电基础
待更新，如有疑问，请发邮件至feedback@ars-mc.ml
# 逻辑门
非门：
（反转结果）
记号：¬p 或 NOT p
真值表：
	p   ¬p
	0     1
	1     0

或门：
（有一个是1则结果为1）
记号：p∨q 或 p OR q
真值表：
	p  q  p∨q
	0  0	0
	0  1	1
	1  0	1
	1  1	1

与门：
（全部为1才为1）
记号：p^q 或 p AND q
真值表：
	p  q  p^q
	0  0	0
	0  1	0
	1  0	0
	1  1 	1

通过或门和非门可以实现与门（根据De Morgan's Law）：
p^q = ¬(¬p∨¬q)

异或门：
（不同为1，相同为0）
记号：p⊕q 或 p XOR q（编程中，使用p^q）
真值表：
	p  q  p⊕q
	0  0	0
	0  1	1
	1  0	1
	1  1	0
根据定义，可以得出：
p⊕q=(¬p^q)∨(p^¬q)

```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tmdakm/ars-mc.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
