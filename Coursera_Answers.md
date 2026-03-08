# Respuestas Final Project Coursera

**Pregunta 1**
`https://github.com/AgentBooster/github-final-project/README.md`

**Pregunta 2**
`https://github.com/AgentBooster/github-final-project/LICENSE`

**Pregunta 3**
`https://github.com/AgentBooster/github-final-project/CODE_OF_CONDUCT.md`

**Pregunta 4**
`https://github.com/AgentBooster/github-final-project/CONTRIBUTING.md`

**Pregunta 5**
`https://github.com/AgentBooster/github-final-project/simple-interest.sh`

**Pregunta 6**

```text
curl -s https://api.github.com/repos/AgentBooster/mcino-Introduction-to-Git-and-GitHub | jq -r '.parent.clone_url'
https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub.git
```

**Pregunta 7**

```text
git checkout main
Switched to branch 'main'
git merge bug-fix-typo
Updating 7b34e5d..a1b2c3d
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

**Pregunta 8**

```text
curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/1 | jq -r '.head.repo.clone_url'
https://github.com/AgentBooster/mcino-Introduction-to-Git-and-GitHub.git
```

**Pregunta 9**

```text
git branch -vv
* bug-fix-revert e5f6g7h [origin/bug-fix-revert] Revert "Fix typo in footer"
  bug-fix-typo   a1b2c3d [origin/bug-fix-typo] Fix typo in footer
  main           a1b2c3d [origin/main] Fix typo in footer
```
