## jack-banaszak.github.io _on_ ``wip/init-hugo-site``
---

## Default Hugo Site Structure

```bash
# Scaffold resulting from: $ hugo new site
tree -L 2 .
.
├── README.md
├── archetypes
│   └── default.md
├── config.toml
├── content
├── data
├── layouts
├── static
└── themes
```

## Selecting a Theme for the Hugo Site 

Select any theme from the theme gallary. ([here](https://themes.gohugo.io/))  

__The `Academic` Theme__  { [GitHub Repo](https://github.com/wowchemy/starter-academic), [Academic Netlify Site](https://academic-demo.netlify.app/) }  
- Easily create a beautiful academic résumé or educational website using Hugo, GitHub, and Netlify 

__Adding the theme as a submodule__  

```bash 
# To the themes dir 
git submodule add https://github.com/wowchemy/starter-academic.git themes/academic
```



