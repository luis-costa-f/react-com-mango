# react-com-mango
Udemy:  ReactJS, Hooks, Recoil, TDD, Clean Architecture, SOLID

original repository: https://github.com/rmanguinho/clean-react
convetional commits: https://www.conventionalcommits.org/en/v1.0.0/

dependencias para serem instaladas
 - git-commit-msg-linter

 - eslint
 - eslint-config-standard-with-typescript
 - eslint-plugin-import
 - eslint-plugin-promise
 - eslint-plugin-standard
 - @typescript-eslint/eslint-plugin
 - eslint-plugin-node

 - lint-staged
 - husky

 - jest
 - @types/jest
 - ts-jest


/* npm i eslint@6.0.8 eslint-config-standard-with-typescript@11.0.1 eslint-plugin-import@2.20.2 eslint-plugin-promise@4.2.1 eslint-plugin-standard@4.0.1 @typescript-eslint/eslint-plugin@2.31.0*/


configuration git

[safe]
	directory = /home/luis-costa/estudos/beecrown-challenges
[core]
	autocrlf = input
	eol = lf
	editor = code --wait
[user]
	name = Luis Costa
	email = luiscosta.uva@gmail.com
[push]
    followTags = true
[alias]
    c = !git add --all && git commit -m
    s = !git status -s
    l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
    amend = !git add --all && git commit --amend --no-edit
    count = !git shortlog -s --grep

