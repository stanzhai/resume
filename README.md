## My resume generated from LaTeX

<https://github.com/stanzhai/resume/blob/master/resume.pdf>

## How to build

Environment：macOS + Sublime Text 3

1. Install `BasicTeX` from <http://tug.org/mactex/>
2. Install `latexmk` by TexLive package manager in your terminal:

	```
	sudo tlmgr update --self
	sudo tlmgr install latexmk
	```

3. Open `Sublime Text`, `Cmd + Shift + P` select install package, install `LaTeXTools` package, then restart `Sublime Text`
4. Install `Skim` to preview .pdf files
5. Open `resume.tex` with `Sublime Text`, use `Cmd + B` to build the resume

## References

1. <http://www.readern.com/sublime-text-latex-chinese-under-mac.html>
2. <https://www.zhihu.com/question/20928639>
3. <http://rpi.edu/dept/arc/training/latex/resumes/>
